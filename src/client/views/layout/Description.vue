<template>
    <section>
      <div class="container-lg">
        <card>
        </card>
      </div>
    </section>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  components: {
    user() {
      return this.$store.getters['auth/user'];
    },
    isLoggedIn() {
      return this.$store.getters['auth/isAuthenticated'];
    },
  },
  computed: {
  },
});
</script>

<style scoped lang="scss">
.btn.btn-user {
    text-align: center;
    max-width: 2.0rem;
    padding: 0;
    border-radius: 0;

    img {
      max-width: 100%;
      max-height: 100%;
      border-radius: 50%;
    }
}
.btn.btn-signin span {
  color: white;
}
.btn.btn-signin:hover span {
  color: black;
}
</style>
