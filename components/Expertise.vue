<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Frontend
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
         <li class="flex items-center">
          <Html class="h-10 w-10 rounded-sm drop-shadow-sm"></Html>
        </li>
        <li class="flex items-center">
          <Css class="h-10 w-10 rounded-sm drop-shadow-sm"></Css>
        </li> 
        <li class="flex items-center">
          <Javascript class="h-10 w-10"></Javascript>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Backend
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <cplus class="h-10 w-10"></cplus>
        </li>
        <li class="flex items-center">
          <c class="h-10 w-10"></c>
        </li>
        <li class="flex items-center">
          <Node class="h-10 w-10"></Node>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import c from "../assets/devicon/c.svg?inline";
import cplus from "../assets/devicon/cplus.svg?inline";
import Javascript from "../assets/devicon/javascript.svg?inline";
import Html from "../assets/devicon/html.svg?inline";
import Css from "../assets/devicon/css.svg?inline";
import Vuejs from "../assets/devicon/vuejs.svg?inline";
import TailwindCss from "../assets/devicon/tailwindcss.svg?inline";
import Nuxt from "../assets/devicon/nuxt.svg?inline";
import Bootstrap from "../assets/devicon/bootstrap.svg?inline";
import Laravel from "../assets/devicon/laravel.svg?inline";
import Node from "../assets/devicon/node.svg?inline";
export default {
  components: {
    c,
    cplus,
    Javascript,
    Html,
    Css,
    Bootstrap,
    Vuejs,
    TailwindCss,
    Nuxt,
    Laravel,
    Node,
  },
};
</script>
