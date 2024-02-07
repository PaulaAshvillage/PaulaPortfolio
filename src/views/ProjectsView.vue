<template>
  <div class="content-wrapper">
    <div class="headline-wrapper">
      <h1>projects made with</h1>
      <img src="../assets/heart.png" alt="heart icon" />
    </div>
    <div class="link-wrapper">
      <a id="link-purple" class="project-link" href="https://gmx.de" target="_blank"
        >MealPlan App <img src="../assets/plus-purple.png" alt="plus icon in purple"
      /></a>
      <a id="link-orange" class="project-link" href="https://gmx.de" target="_blank"
        >To do App <img src="../assets/plus-orange.png" alt="plus icon in orange"
      /></a>
    </div>
    <div class="link-wrapper">
      <a id="link-orange" class="project-link" href="https://gmx.de" target="_blank"
        >Bandpage <img src="../assets/plus-orange.png" alt="plus icon in orange" /></a
      ><a id="link-purple" class="project-link" href="https://gmx.de" target="_blank"
        >CV Barrierefrei <img src="../assets/plus-purple.png" alt="plus icon in purple"
      /></a>
      <a id="link-orange" class="project-link" href="https://gmx.de" target="_blank"
        >Git Hub <img src="../assets/plus-orange.png" alt="plus icon in orange"
      /></a>
    </div>
  </div>
</template>
<style scoped>
.content-wrapper {
  padding: 0;
  padding-top: 5rem;
}
h1 {
  font-weight: 400;
}
.headline-wrapper {
  display: flex;
  justify-content: start;
  align-items: center;
  gap: 0.75rem;
}
img {
  height: 1.8rem;
  width: 1.8rem;
}
.link-wrapper {
  display: flex;
  justify-content: start;
  padding-top: 2rem;
  gap: 2rem;
}
.project-link {
  font-size: 1.25rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  padding: 2rem;
  border-radius: 1.75rem;
}
#link-purple {
  color: var(--color-purple);
  border: 2px solid var(--color-purple);
}
#link-orange {
  color: var(--color-orange);
  border: 2px solid var(--color-orange);
}
</style>
