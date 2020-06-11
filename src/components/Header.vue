<template>
  <header>
    <img class="logo" src alt="logo" />
    <nav>
      <ul class="nav__links">
        <li>
          <nuxt-link to="./pages/About">About</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style lang="sass" scoped>
</style>