<template>
    <!-- Crie um container com flex; Layout colunar; Seis itens com cores diferentes -->
    <h2 class="flex justify-center my-10">Exercício Flexbox</h2>

    <div class="flex flex-col bg-yellow-300">
        <div class="bg-orange-400 p-6 m-2">1</div>
        <div class="bg-orange-500 p-6 m-2">2</div>
        <div class="bg-orange-600 p-6 m-2">3</div>
        <div class="bg-orange-700 p-6 m-2">4</div>
        <div class="bg-orange-800 p-6 m-2">5</div>
        <div class="bg-orange-900 p-6 m-2">6</div>
    </div>

    <h2 class="flex justify-center my-10">Ex Order</h2>

    <div class="flex container bg-yellow-300">
        <div class="bg-blue-400 p-6 m-4 lg:order-3">1</div>
        <div class="bg-blue-500 p-6 m-4 lg:order-2">2</div>
        <div class="bg-blue-600 p-6 m-4 lg:order-1">3</div>
    </div>
</template>