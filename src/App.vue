<template>
  <div id="app">
    <nav>
        <ul class="section justify--end">
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/example1">Example1</router-link></li>
        </ul>
  </nav>
    <router-view></router-view>
  </div>
</template>

<style lang="scss">
    @import './spark/loader.scss';
</style>
