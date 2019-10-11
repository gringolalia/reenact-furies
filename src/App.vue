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
        form(action='javascript:void(0)')
          input.uk-input.uk-form-width-medium.uk-margin-small-right(type='text' placeholder='Insumo')
          vk-button(type="secondary") Apertar
  router-view.
    
    </template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=News+Cycle|Material+Icons');

#app, html {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
