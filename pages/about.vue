<template>
  <div id="about">
    <Navigation />
    <h3>About</h3>
    <div id="current-time">
      {{ currentTime }}
    </div>
  </div>
</template>

<script>
export default {
  layout: 'blog',
  data() {
    return {
      currentTime: new Date().toLocaleString('ko-KR')
    }
  }
}

</script>
