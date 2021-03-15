<template>
    <section>
      <div class="container-lg">
        <card class="mb-2">
            <h4>Welcome!</h4>
            <p style="font-size: 18px;">
                This is the feedback site for <a href="https://experimental-learning.com">Experimental Learning</a>. <a href="">Patrons</a> can add ideas/requests/suggestions as issues, vote on polls and leave comments. Make sure to sign up for a <a href="https://github.com/join">GitHub account</a>!
            </p>
            <p>
            This site was built with <a href="https://github.com/alexis-/GitHub-Voice">GitHub Voice</a>.
            </p>

        </card>
      </div>
    </section>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  components: {
    /* user() { */
    /*   return this.$store.getters['auth/user']; */
    /* }, */
    /* isLoggedIn() { */
    /*   return this.$store.getters['auth/isAuthenticated']; */
    /* }, */
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
