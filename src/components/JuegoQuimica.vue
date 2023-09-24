<script setup>
import { ref, computed } from 'vue'
import Joda from './Joda.vue'

</script>

<template>
  <Joda />

  <section class="audio">
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
  </section>

</template>

<style scoped>
.audio {
  margin-top: 12em;
}
</style>
