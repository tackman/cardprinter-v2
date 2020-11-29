<template>
  <div class="card-container box-border border-2 border-dashed">
    <h4>ECHO</h4>
    <h1 class="echo-text">{{ echo }}</h1>

    <svg height="10" width="88mm">
      <line
        x1="0"
        y1="0"
        x2="88mm"
        y2="0"
        style="stroke: rgb(0, 0, 0); stroke-width: 2"
      />
    </svg>
    <h2>{{ cardName }}</h2>
    <h2>効果：{{ effect }}</h2>

    <svg height="10" width="88mm">
      <line
        x1="0"
        y1="0"
        x2="88mm"
        y2="0"
        style="stroke: rgb(0, 0, 0); stroke-width: 2"
      />
    </svg>

    <h4>when</h4>
    <h2>{{ timing }}</h2>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default {
  props: {
    cardName: {
      type: String,
    },
    echo: {
      type: String,
    },
    timing: {
      type: String,
    },
    effect: {
      type: String,
    },
  },
}
</script>


<style>
.card-container {
  width: 88mm;
  height: 57mm;
  background-color: white;
}

.echo-text {
  font-size: 6mm;
}

.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
