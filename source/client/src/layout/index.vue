<template>
  <div class="app-wrapper">
    <sidebar class="sidebar-container" />
    <div class="main-container">
      <div>
        <navbar />
      </div>
      <app-main />
    </div>
  </div>
</template>

<script>
import { Navbar, Sidebar, AppMain } from './components';
export default {
  name: 'Layout',
  components: {
    Navbar,
    Sidebar,
    AppMain,
  },
};
</script>

<style>
</style>