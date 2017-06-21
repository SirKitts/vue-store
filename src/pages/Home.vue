<template>
  <div class="home">
    {{msg}}
    <Videos/>
    <Collections/>
  </div>
</template>

<script>
import Videos from '@/components/Videos.vue'
import Collections from '@/components/Collections.vue'

export default {
  name: 'home',
  components: {
    Videos,
    Collections
  },
  data () {
    return {
      msg: 'Home'
    }
  }
}
</script>
