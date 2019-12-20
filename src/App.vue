<template lang="pug">
#app
  vk-navbar
    vk-navbar-full
      vk-navbar-logo.with.dignity 
        i.fas.fa-sun.fa-2x
        | &nbsp; Engenho Novo LLC
      vk-navbar-nav
        vk-navbar-nav-item
          vk-icon-button.uk-margin-small-right(href='#' icon='twitter')
          vk-icon-button.uk-margin-small-right(href='#' icon='facebook')
          vk-icon-button(href='#' icon='google-plus')  

  router-view
    
</template>

<style lang="scss">

@import url('https://fonts.googleapis.com/css?family=News+Cycle|Material+Icons');
@import "../node_modules/@vuikit/theme/dist/vuikit.css";

html, body, .dignity  {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

vk-navbar-logo, vk-navbar-nav-item {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif;
}

</style>
