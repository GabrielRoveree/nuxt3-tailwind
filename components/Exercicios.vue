<template>
  <!-- Ex1 Crie um container com o fundo verde que ao atingir o bp md mude para azul -->
  <div class="container mx-auto p-5 my-5 bg-green-500 md:bg-blue-500">
    <p>Exercício 1</p>
  </div>

  <div class="container mx-auto p-10 my-5 bg-teal-500 border-box">
    <p>Border box</p>
  </div>

  <!-- Box content mantém o tamanho inicial e soma com paddings, bordas e etc -->
  <div class="container mx-auto p-10 my-5 bg-purple-500 box-content">
    <p>Box content</p>
  </div>

  <!-- Ex2 Crie um container com 3 divs com display inline e todas com um bgc diferente -->
  <div class="container bg-orange-400">
    <div class="bg-slate-500 inline-block">Div 1</div>
    <div class="bg-pink-500 inline-block">Div 2</div>
    <div class="bg-green-500 inline-block">Div 3</div>
  </div>

  <!--  -->

  <div class="overflow-hidden h-16 m-6 bg-red-300">
    <p>testando overflow Hidden</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
  </div>

  <div class="overflow-auto h-16 m-6 bg-red-300">
    <p>testando overflow Auto</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
    <p>testando overflow</p>
  </div>

  <div class="overflow-x-auto h-16 m-6 bg-green-300">
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
  </div>

  <!-- Positions -->

  <div class="container relative bg-blue-700 h-10">
    <div class="absolute top-0 right-0 bg-pink-900">absolute</div>
  </div>

  <!-- Ex3 crie uma div com altura determinada e ppsicione uma div no canto inferior direito dessa div -->
  <div class="container relative bg-blue-400 h-10 my-10 mx-auto">
    <div class="absolute bottom-0 right-0 bg-pink-700">absolute</div>
  </div>

  <!-- Ex4 cria 3 divs; Cada div deve sobrepor a outra atraves do z-index; iclua cores diferentes -->
  <div class="container relative h-20">
    <div class="bg-red-400 absolute z-1 h-10">INDEX 1</div>
    <div class="bg-red-600 absolute z-2 h-10 m-4">INDEX 2</div>
    <div class="bg-red-800 absolute z-3 h-10 m-8">INDEX 3</div>
  </div>
</template>