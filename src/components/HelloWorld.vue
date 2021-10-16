<template>
  <div class="hello">
    <h3>Made With Lottifiles</h3>
    <lottie :options="defaultOptions" :width="500" :height="500" />
  </div>
</template>

<script>
import * as animationData from '@/assets/animations/loading.json'

export default {
  name: 'HelloWorld',
  data() {
    return {
      defaultOptions: {
        animationData: animationData.default,
      },
    }
  },
}
</script>
