<template>
  <panel title="YouTube Video" class="ml-2">
    <youtube
      :video-id="youtubeId"
      :player-width="800"
      :player-height="315">
    </youtube>
  </panel>
</template>

<script>
export default {
  props: ['youtubeId']
}
</script>

<style scoped>
</style>
