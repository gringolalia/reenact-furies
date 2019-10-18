<template lang="pug">
#app
  vk-navbar
    vk-navbar-nav
      vk-navbar-logo.with.dignity 
        i.fas.fa-sun.fa-2x
        | &nbsp; Engenho Novo LLC
      vk-navbar-nav
        vk-navbar-nav-item(icon='git-fork' title='Working Forks')
        vk-navbar-nav-item(icon='git-branch' title='Branch Office')
      vk-navbar-item
        form.with.dignity(action='javascript:void(0)')
          input.uk-input.uk-form-width-medium.uk-margin-small-right(type='text' placeholder='Curiosidade')
          vk-button.vk-button-primary.with.dignity(type="secondary") Enviar
  router-view.
    
    </template>

<style lang="scss">

@import url('https://fonts.googleapis.com/css?family=News+Cycle|Material+Icons');
@import "../node_modules/@vuikit/theme/dist/vuikit.css";

#app, html, body, .dignity  {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

vk-navbar-logo {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif;
}

</style>
