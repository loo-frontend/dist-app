<template>
  <div id="home">
    <site-header></site-header>
    <side-menu></side-menu>
    <page-content></page-content>
    <side-menu-panel-container></side-menu-panel-container>    
  </div>  
</template>

<script>

import SiteHeader from './components/Shared/Header/SiteHeader';
import SideMenuDefault from './components/Shared/Sidebar/SideMenuDefault';
import PageContent from './components/PageContent/PageContent';
import SideMenuPanelContainer from './components/Shared/Sidebar/SideMenuPanelContainer';

export default {
  name: 'home',
  components: {
    'site-header': SiteHeader,
    'side-menu': SideMenuDefault,
    'page-content': PageContent,
    'side-menu-panel-container': SideMenuPanelContainer
  }
}
</script>

<style scope>

</style>
