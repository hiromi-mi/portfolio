<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        portfolio
      </h1>
      <h2 class="subtitle">
        Portfolio Page of hiromi-mi
      </h2>
      <div class="links">
      <!--
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">
          Documentation
        </a>
        -->
        <a
          href="https://github.com/hiromi-mi"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
      <div class="langs">
      <div class="content"><strong>hanando-fukui</strong><br>
   Small C/C++ subset Compiler
      </div>
      <div class="content"><strong>online-hf</strong><br>
      Online-based Compiler on Hanando-fukui
      </div>
      <div class="content"><strong>zovtyj</strong> <br> Small Mastodon Viewer written in Golang</div>
      </div>
      <div class="content"><strong>zoltyj</strong> <br> Small Mastodon Viewer written in Ruby</div>
      </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '~/components/Logo.vue'

export default Vue.extend({
  components: {
    Logo
  }
})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

@extend media-content
.langs {
  justify-content: center;
}
</style>
