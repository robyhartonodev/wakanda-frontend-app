<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
    <button
      v-show="showButton"
      class="rounded-sm bg-blue-700 fixed bottom-5 right-5 text-white hover:bg-blue-500"
      :class="showButton ? 'animate__animated animate__slideInUp animate__slow': ''"
      @click="onScrollToTop"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-12 w-12"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        stroke-width="2"
      >
        <path stroke-linecap="round" stroke-linejoin="round" d="M5 15l7-7 7 7" />
      </svg>
    </button>
  </div>
</template>

<script>
export default {
  name: 'LayoutDefault',
  data () {
    return {
      windowTop: window.scrollY,
      showButton: false
    }
  },
  mounted () {
    window.addEventListener('scroll', this.onScroll, true)
  },
  beforeDestroy () {
    window.removeEventListener('scroll', this.onScroll, true)
  },
  methods: {
    debounce (func, timeout = 500) {
      let timer
      return (...args) => {
        clearTimeout(timer)
        timer = setTimeout(() => { func.apply(this, args) }, timeout)
      }
    },
    onScrollToTop () {
      window.scrollTo({ top: 0, behavior: 'smooth' })
    },
    onScroll () {
      this.windowTop = window.scrollY
      if (this.windowTop > 100) {
        this.showButton = true
      } else {
        this.showButton = false
      }
    }
  }
}
</script>
