<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <header>
    <img alt="Profile" class="photo" src="./assets/Profile.JPG.jpg" width="236" height="355" />

    <div class="wrapper">
      <HelloWorld msg="Nurul Ikhsan S, S.T (Soon)" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.photo {
  display: block;
  margin: 0 auto 2rem;
  border-radius: 100%;
  border: 10px solid #fff;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .photo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
