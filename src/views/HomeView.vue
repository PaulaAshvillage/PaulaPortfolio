<template>
  <div class="home-container">
    <h1>Welcome to my portfolio<span id="dot">.</span></h1>
    <div class="link-container">
      <router-link id="project-shape" class="shaped-link" to="/projects">projects </router-link>
      <div id="about-shape-container">
        <router-link id="about-shape" class="shaped-link" to="/about">about </router-link>
      </div>
    </div>
  </div>
</template>
<style scoped>
.home-container {
  height: 100%;
  padding-top: 30dvh;
  display: flex;
  align-items: flex-end;
}

h1 {
  font-size: 7rem;
  text-align: left;
}
#dot {
  color: var(--color-purple);
}
.link-container {
  display: flex;
  margin-left: 2rem;
  gap: 2rem;
  flex-direction: column;
}
.shaped-link {
  font-weight: 600;
  font-size: 1.75rem;
  height: 14rem;
  width: 14rem;
}
#project-shape {
  color: var(--color-beige);
  background-color: var(--color-orange);

  border-radius: 14rem 0 0 0;
  display: flex;
  align-items: flex-end;
  justify-content: end;
}

#about-shape {
  color: var(--color-beige);

  background-color: var(--color-yellow);

  border-radius: 0 14rem 0 0;
  display: flex;
  align-items: flex-end;
  justify-content: start;
}
@media (max-width: 1000px) {
  h1 {
    font-size: 5rem;
    font-weight: 400;
    text-align: left;
  }
  .shaped-link {
    font-weight: 400;
    font-size: 1.5rem;
    height: 11rem;
    width: 11rem;
  }
}
@media (max-width: 600px) {
  .home-container {
    padding-top: 10dvh;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 2rem;
  }
  h1 {
    font-size: 3rem;
    font-weight: 300;
  }
  .link-container {
    margin-left: 0;
  }

  .shaped-link {
    font-weight: 400;
    font-size: 1.5rem;
    height: 10rem;
    width: 10rem;
    border-radius: 10rem 0 0 0;
  }
  #project-shape {
    justify-content: center;
    z-index: 1;
  }
  #about-shape {
    display: flex;
    justify-content: center;
    border-radius: 10rem 0 0 0;
  }
  #about-shape-container {
    display: block;
    position: relative;
    bottom: 5rem;
    left: 5rem;
  }
}
</style>
<script></script>
