<template>
  <div class="container">
    <div class="grid grid-cols-2 gap-4">
      <Card
        :cardName="cardName"
        :echo="echo"
        :timing="timing"
        :effect="effect"
      />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default {
  data() {
    return {
      cardName: '気まずい関係',
      echo: '告白不可',
      timing: '駆け引き成立かつ、どちらかが交際を断った時',
      effect: 'なし',
    }
  },
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  width: 210mm;
  height: 297mm;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: white;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
