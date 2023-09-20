<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>Repaso de química</h1>

  <div>
    <p>Kahoot:</p>
    <audio controls>
      <source src="https://quimica.s3.amazonaws.com/kahoot-lobby.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div>
    <p>Crickets:</p>
    <audio controls>
      <source src="https://quimica.s3.amazonaws.com/crickets.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div>
    <p>Cheering:</p>
    <audio controls>
      <source src="https://quimica.s3.amazonaws.com/Cheering.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>

</template>

<style scoped>

</style>
