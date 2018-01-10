<template>
<div id="app">
  <nav class="navbar is-transparent has-shadow">
    <div class="navbar-brand">
      <router-link to="/" class="navbar-item"><strong>MyCompany</strong></router-link>
      <div class="navbar-burger burger" @click="toggleNav" v-bind:class="{ 'is-active': isActive }">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
    <div class="navbar-menu" v-bind:class="{ 'is-active': isActive }">
      <div class="navbar-start">
        <router-link to="/" class="navbar-item">Home</router-link>
        <router-link to="faq" class="navbar-item">FAQ</router-link>
      </div>
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="field is-grouped">
            <p class="control">
              <a class="button is-primary" href="#">
                <span class="icon">
                  <i class="fa fa-download"></i>
                </span>
                <span>Join Now</span>
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </nav>
  <router-view></router-view>
</div>
</template>

<script>
export default {
  name: 'app',
  data: function() {
    return {
      isActive: false
    }
  },
  methods: {
    toggleNav: function() {
      this.isActive = !this.isActive;
    }
  }
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import 'mq'
</style>
