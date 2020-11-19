<template>
  <div class="card-container box-border border-2 border-dashed">
    <h1>強引なアプローチ</h1>
    <h2>
      <span class="text-red-400">好感度+2</span>
      <span class="text-blue-400">不満度+1</span>
    </h2>

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
    <h2>アプローチ時</h2>
  </div>
</template>

<style>
.card-container {
  width: 88mm;
  height: 57mm;
  background-color: white;
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
