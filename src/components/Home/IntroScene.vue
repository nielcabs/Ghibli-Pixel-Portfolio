<template>
  <section class="scene-intro" id="intro">
    <div class="static-container">
      <h1 class="title">
        <span class="iuri">Undeci</span>
        <span class="func">Dev(?)</span>
      </h1>

      <TextBlock>
        <p class="-purple">Juniel Cabo</p>
        <p class="-gray">Full Stack Developer</p>
      </TextBlock>
    </div>
  </section>
</template>

<script>
import TextBlock from '../TextBlock.vue'

export default {
  name: 'IntroScene',
  components: { TextBlock },
}
</script>
