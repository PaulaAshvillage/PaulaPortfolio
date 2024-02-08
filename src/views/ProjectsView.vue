<template>
  <div class="content-wrapper">
    <div class="headline-wrapper">
      <h1>projects made with</h1>
      <img src="../assets/heart.png" alt="heart icon" />
    </div>
    <div class="link-wrapper">
      <a id="link-1" class="project-link" href="https://gmx.de" target="_blank"
        >MealPlan App <img src="../assets/link-purple.png" alt="link icon in purple"
      /></a>
      <a id="link-2" class="project-link" href="https://gmx.de" target="_blank"
        >To do App <img src="../assets/link-orange.png" alt="link icon in orange"
      /></a>
    </div>
    <div class="link-wrapper">
      <a id="link-3" class="project-link" href="https://gmx.de" target="_blank"
        >Bandpage Käpt'n Picus<img src="../assets/link-orange.png" alt="link icon in orange"
      /></a>

      <a id="link-4" class="project-link" href="https://gmx.de" target="_blank"
        >CV Barrierefrei <img src="../assets/link-purple.png" alt="link icon in purple"
      /></a>
      <a id="link-5" class="project-link" href="https://gmx.de" target="_blank"
        >Git Hub <img src="../assets/link-orange.png" alt="link icon in orange"
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
  padding-bottom: 3rem;
}
img {
  height: 2rem;
  width: 2rem;
}
.link-wrapper,
.link-wrapper-responsive,
#link-3 {
  display: flex;
  justify-content: start;
  padding-top: 2rem;
  gap: 2rem;
}

.project-link {
  font-size: 1.25rem;
  font-weight: 300;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  padding: 2rem;
  border-radius: 1.75rem;
}
#link-1,
#link-4 {
  color: var(--color-purple);
  border: 2px solid var(--color-purple);
}
#link-2,
#link-3,
#link-5 {
  color: var(--color-orange);
  border: 2px solid var(--color-orange);
}
@media (max-width: 600px) {
  .content-wrapper {
    padding-top: 3rem;
  }
  .headline-wrapper {
    padding-bottom: 0;
    font-size: 0.75rem;
  }

  .link-wrapper {
    display: flex;
    flex-direction: column;
    margin-right: 5rem;
    align-items: start;
    gap: 0.5rem;
    padding-top: 0.5rem;
  }
  .link-wrapper-responsive {
    padding-top: 0.5rem;
    display: flex;
    flex-direction: row;
  }
  .link-wrapper > * img {
    display: none;
  }
  .project-link {
    font-size: 1rem;
    font-weight: 200;
    gap: 0.25rem;
    padding-inline: 2rem;
    padding-block: 1rem;
    border-radius: 1.5rem;
  }
  #link-1 {
    align-self: center;
  }
  #link-3 {
    align-self: center;
    padding-block: 1rem;
  }
}
</style>
