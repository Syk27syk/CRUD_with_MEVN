<template>
  <div>
    <header class="grid grid-cols-2 bg-black py-5 text-white">
      <div id="logo" class="flex flex-row">
        <img src="/logo.png" class="h-16 w-16 mx-5 my-2" alt="" />
        <p class="my-auto text-3xl font-bold">Recipes DB</p>
      </div>
      <div id="navigation" class="grid grid-cols-4 gap-5 text-xl font-bold">
        <span>nav item 1</span>
        <span>nav item 2</span>
        <span>nav item 3</span>
      </div>
    </header>
    <div id="hero" class="flex h-screen h-[100vh]  bg-[url('/hero-bg.jpg')] bg-cover bg-center align-middle text-white text-center">
      <div class="m-auto bg-black py-10 px-10">
        <h1 class="text-5xl">Build your Own Database of Recipes</h1>
        <p class="mt-5 text-3xl">CRUD app with MEVN stack</p>
      </div>
    </div>
    <div id="section 1" class="py-32 m-auto">
        <p class="m-auto"> content section 1</p>
    </div>
    <div id="footer" class="bg-black py-5 text-white m-auto">
        <p class="m-auto"> footer </p>
    </div>
  </div>
</template>
