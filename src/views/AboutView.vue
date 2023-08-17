<script setup>
import {useFlash} from "@/composables/useFlash.js";

let {flash} = useFlash()

</script>

<template>
  <main>
    <p>
      <button @click="flash('Yay!', 'It Works On the About Page!', 'info')">Click Me!</button>
    </p>
  </main>
</template>
