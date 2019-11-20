<template>
  <div id="app" class="flex"> 
    <aside class="h-screen w-60 bg-gray-700">
      <div class="h-20 bg-gray-800"></div>
      <div class="mt-16">
        <button class="flex w-full text-left focus:outline-none">
          <div class="w-1 h-12 bg-indigo-400"></div>
          <div class="w-full h-12 bg-gray-800 py-3">
            <span class="text-white ml-5">Medicamentos</span>
          </div>
        </button>
        <button class="flex w-full text-left focus:outline-none">
          <div class="w-full h-12 py-3">
            <span class="text-white ml-5">Alertas</span>
          </div>
        </button>
      </div>
    </aside>
    <router-view/>
  </div>
</template>