<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header>
    <nav class="container">
      <div class="branding">
        <RouterLink to="/">
          <img src="../../assets/to-do-list.png" alt="brand image" />
          <h1>Todo App</h1>
        </RouterLink>
      </div>
      <ul class="nav-routes">
        <RouterLink to="/todoOne">One</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #f1f1f1;
  nav {
    display: flex;
    align-items: center;
    padding: 25px 16px;

    .branding {
      a {
        display: flex;
        align-items: center;
        gap: 8px;
        text-decoration: none;
        color: black;
        img {
          max-width: 50px;
        }

        h1 {
          font-size: 24px;
        }
      }
    }

    .nav-routes {
      display: flex;
      flex: 1;
      justify-content: flex-end;
      gap: 12px;
      list-style: none;

      a {
        text-decoration: none;
        color: inherit;
        padding: 5px;
        border: 1px solid #000000;
      }
    }
  }
}
</style>
