<script setup lang="ts">
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
</script>
<template>
  <div>
    <h1>hallo ich bin paula <span>.</span></h1>

    <p class="profession">frontend developer | sport scientist</p>
    <article class="about">
      <h2><span>M</span>eine Reise - so far</h2>
      <p>
        Ich habe vor 3 Jahren durch eine glückliche Fügung die Faszination des Codings für mich
        entdeckt. Meine ersten Schritte mit HTML und CSS führten zu Algorithmen Knobelei in C# bis
        zu Taschenrechner Frimelei mit Javascript, jQuery und Knockout. Wie umständlich das war,
        habe ich dann in einem 9-monatigen Coding Bootcamp zur Frontend Developerin erfahren.
        Außerdem habe ich erfahren, wie viel mehr man in kurzer Zeit lernt, wenn der Pfad vorgegeben
        und der Stoff didaktisch aufbereitet ist. Ich hatte sehr viel Freude mit barrierfreien HTML
        und CSS, Knobeleien mit Javascript. Mit Vue.js hat sich dann eine neue Welt eröffnet. Was
        ich gelernt habe sind die Skills auf der einen Seite, aber vor allem auch den Weg der
        Problemlösung der damit beginnt ein Problem richtig zu formulieren, sprich ich habe gelernt
        gut und effektiv zu Googeln. Apropos Google, meinen Einstieg in die Welt der IT begann in
        einer Firma die eine SEO Software programmiert und vertreibt. SEO ist mir bestens bekannt
        sowie Lernen, Teamgeist und Empathie.
      </p>
    </article>
    <article>
      <h2><span>T</span>ech-Stack</h2>
      <p class="icon-container">
        <font-awesome-icon :icon="['fab', 'vuejs']" />
        <font-awesome-icon :icon="['fab', 'js']" />
        <font-awesome-icon :icon="['fab', 'html5']" />
        <font-awesome-icon :icon="['fab', 'css3']" />
        <font-awesome-icon :icon="['fab', 'github']" />
        <font-awesome-icon :icon="['fab', 'cloudflare']" />
        <font-awesome-icon :icon="['fab', 'figma']" />
      </p>
    </article>
    <article>
      <h2><span>W</span>as ich mag</h2>
      <p class="icon-container">
        <fa icon="coffee"></fa>
        <font-awesome-icon :icon="['fas', 'mountain-sun']" />
        <font-awesome-icon :icon="['fas', 'tree']" />
        <font-awesome-icon id="icon-basketball" :icon="['fas', 'basketball']" />
      </p>
    </article>
  </div>
</template>

<style scoped>
div {
  text-align: left;
  padding-top: 5rem;
}
h1 {
  font-size: 2rem;
  font-weight: 400;
}
h2 span {
  font-weight: 700;
  color: var(--color-purple);
}
h2 {
  font-weight: 500;
}
span {
  color: var(--color-purple);
}
.profession {
  font-size: 1.5rem;

  color: var(--color-purple);
}
article {
  padding-top: 2rem;
}
p {
  font-size: 1.25rem;
}
.icon-container {
  display: flex;
  font-size: 4rem;
  color: var(--color-purple);
  gap: 1.5rem;
  padding-top: 1rem;
}
#icon-basketball {
  color: var(--color-orange);
}

@media (max-width: 1000px) {
  h1 {
    font-size: 3rem;
    font-weight: 400;
  }
}
@media (max-width: 600px) {
  h1 {
    font-size: 1rem;
    font-weight: 300;
  }
  h2 {
    font-size: 1rem;
    font-weight: 300;
  }
  .profession {
    font-size: 1rem;
    color: var(--color-purple);
  }
  p {
    font-size: 0.7rem;
    text-align: justify;
  }
  .icon-container {
    flex-wrap: wrap;
  }
}
</style>
