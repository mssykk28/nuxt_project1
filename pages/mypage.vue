<template>
  <div class="wrap">
    <h1>こんにちは、{{ username }}さん!</h1>
    <button v-if="loggedIn" class="button" @click="logout">ログアウト</button>
  </div>
</template>

<script>
export default {
  name: 'MyPage',
  computed: {
    username() {
      if (this.$auth.$state.user && this.$auth.$state.user.name) {
        return this.$auth.$state.user.name
      } else {
        return null
      }
    },
    loggedIn() {
      return this.$auth.loggedIn
    },
    methods: {
      logout() {
        this.$auth.logout()
      },
    },
  },
}
</script>

<style scoped>
.wrap {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.button {
  font-size: 2rem;
}
</style>
