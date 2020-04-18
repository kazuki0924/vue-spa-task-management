<template>
  <div class="task-view">
    <div class="flex flex-col flex-grow items-start justify-between px-4">
      {{ task.name }}
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style>
  .task-view {
    @apply relative flex flex-row bg-white pin mx-4 m-32 mx-auto py-4 text-left rounded shadow;
    max-width: 700px;
  }
</style>
