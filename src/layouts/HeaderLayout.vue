<template>
  <div>
    <nav>
      <router-link id="home-link" to="/">paula.</router-link>
      <router-link class="router-link" to="/projects">projects</router-link>
      <router-link class="router-link" to="/about">about</router-link>
    </nav>

    <router-view />
  </div>
</template>
<style scoped>
nav {
  padding-top: 2rem;

  display: flex;
  justify-content: flex-end;
  gap: 2rem;
  font-size: 1.5rem;
}
.router-link:hover {
  text-decoration: underline;
  text-decoration-color: var(--color-purple);
  cursor: pointer;
}

#home-link {
  font-weight: 100;
  margin-right: auto;
}
@media (max-width: 600px) {
  .router-link {
    display: none;
  }
}
</style>
