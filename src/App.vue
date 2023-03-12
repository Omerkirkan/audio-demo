<template>
  <div>
    <av-line
      :line-width="2"
      line-color="lime"
      :src="audio"
    ></av-line>
  </div>
</template>
<script>
export default {
  name: 'App',
  data() {
    return {
      audio: "https://surah-sound-file.fra1.digitaloceanspaces.com/Raad-Al_Kurdi/001.mp3",
    }
  }
}
</script>