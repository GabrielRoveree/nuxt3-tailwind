<template>
  <!-- flex-row -->
  <div class="flex flex-row bg-red-300">
    <div class="bg-red-600 p-6 m-2">1</div>
    <div class="bg-red-600 p-6 m-2">2</div>
    <div class="bg-red-600 p-6 m-2">3</div>
  </div>

  <!-- flex column -->
  <div class="flex flex-col bg-blue-300">
    <div class="bg-blue-600 p-6 m-2">1</div>
    <div class="bg-blue-600 p-6 m-2">2</div>
    <div class="bg-blue-600 p-6 m-2">3</div>
  </div>

  <!-- flex row reverse -->
  <div class="flex flex-row-reverse bg-green-300">
    <div class="bg-green-600 p-6 m-2">1</div>
    <div class="bg-green-600 p-6 m-2">2</div>
    <div class="bg-green-600 p-6 m-2">3</div>
  </div>

  <!-- flex column reverse -->
  <div class="flex flex-col-reverse bg-pink-300">
    <div class="bg-pink-600 p-6 m-2">1</div>
    <div class="bg-pink-600 p-6 m-2">2</div>
    <div class="bg-pink-600 p-6 m-2">3</div>
  </div>

  <!-- Wrap -->
  <div class="flex flex-wrap bg-red-300">
    <div class="bg-red-400 p-6 m-2">1</div>
    <div class="bg-red-500 p-6 m-2">2</div>
    <div class="bg-red-600 p-6 m-2">3</div>
    <div class="bg-red-700 p-6 m-2">4</div>
    <div class="bg-red-800 p-6 m-2">5</div>
    <div class="bg-red-900 p-6 m-2">6</div>
  </div>

  <div class="flex container bg-teal-400 p-8">
    <div class="flex-1 bg-teal-900">1</div>
    <div class="flex-1 bg-teal-700">2</div>
    <div class="flex-none bg-teal-500">3</div>
  </div>

  <!-- Order -->
    <div class="flex flex-wrap bg-purple-300 my-5">
    <div class="bg-purple-400 p-6 m-2 order-last">1</div>
    <div class="bg-purple-500 p-6 m-2 order-5">2</div>
    <div class="bg-purple-600 p-6 m-2 order-4">3</div>
    <div class="bg-purple-700 p-6 m-2 order-3">4</div>
    <div class="bg-purple-800 p-6 m-2 order-2">5</div>
    <div class="bg-purple-900 p-6 m-2 order-first">6</div>
  </div>

  <!-- Exercícios Flex-box -->
  <FlexboxExercicios />
</template>