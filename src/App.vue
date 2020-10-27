<template>
  <h1>hello</h1>
  <div>
    hello
    <router-link to="/">hello1</router-link>
    <router-link to="/2">hello2</router-link>
  </div>
  <router-view></router-view>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>
