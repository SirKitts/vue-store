<template>
  <div class="videos">
    {{msg}} <input v-model="selectedVideo.store.video.id">
    <pre>{{$data | json}}</pre>
  </div>
</template>

<script>
import store from '@/js/store'

export default {
  name: 'videos',
  data () {
    return {
      msg: 'Videos',
      selectedVideo: store
    }
  }
}
</script>
