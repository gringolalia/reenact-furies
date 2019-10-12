<template lang="pug">
.home
  vk-grid
    div
      img(alt='Vue logo' src='../assets/biohazard.svg' width="125px;")
      HelloWorld(msg='Reenact Furies')
      h2 A Vuerified User Interface 
      vk-button(type="secondary") Imprints
      vk-button(type="primary") Offprints
      h3
        i.fas.fa-chess.fa-5x
    div
      img(alt='Vue logo' src='../assets/biohazard.svg' width="125px;")
      HelloWorld(msg='Reenact Furies')
      h2 A Vuerified User Interface 
      vk-button(type="secondary") Imprints
      vk-button(type="primary") Offprints
      h3
        i.fas.fa-chess.fa-5x
    div
      img(alt='Vue logo' src='../assets/biohazard.svg' width="125px;")
      HelloWorld(msg='Reenact Furies')
      h2 A Vuerified User Interface 
      vk-button(type="secondary") Imprints
      vk-button(type="primary") Offprints
      h3
        i.fas.fa-chess.fa-5x
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style>

.home {
  margin-top: 10vh;
}

</style>