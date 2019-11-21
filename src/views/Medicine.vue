<template>
  <div class="medicine flex h-screen">
    <!-- <aside class="px-6 bg-own-100">
      <div class="mt-12 relative">
        <svg class="absolute h-12 ml-3" fill="#718097" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/></svg>
        <input class="h-12 w-80 pl-12 pr-5 border border-gray-400 rounded-lg text-gray-600 font-light placeholder-gray-600 bg-gray-300 shadow-inner focus:outline-none" type="text">
      </div>
      <div class="mt-10">
        <div v-for="(medicine, index) in medicines" :key="index">
          <button v-if="index == selectedMedicine" class="w-80 block text-left rounded-lg py-5 px-4 bg-gray-100 shadow-md focus:outline-none">
            <div class="flex justify-between">
              <span class="text-gray-700 font-bold text-lg">ABACAVIR</span>
              <div class="w-12 flex justify-center bg-gray-300 rounded-full py-px">
                <span class="text-gray-700 font-bold">17</span>
              </div>
            </div>   
            <span class="text-gray-600 mt-1">J05AF06</span>
          </button>
          <button v-else class="w-80 block text-left rounded-lg py-5 px-4 bg-gray-100 border border-gray-300 mt-5 focus:outline-none">
            <div class="flex justify-between">
              <span class="text-gray-700 font-bold text-lg">ABACEPT</span>
              <div class="w-12 flex justify-center bg-gray-300 rounded-full py-px">
                <span class="text-gray-700 font-bold">17</span>
              </div>
            </div>
            <span class="text-gray-600 mt-1">J05AF06</span>
          </button>
        </div>
      </div>
    </aside>
    <div class="w-grow">
      <div class="h-30 bg-gray-800 py-8 pb-6">
        <p class="text-big font-bold text-white ml-12">ABACAVIR</p>
        <span class="text-gray-600 mt-3 ml-12">J05AF06</span>
      </div>
      <div class="h-16 bg-gray-300 flex items-center font-light">
        <p class="ml-12">Este medicamento tiene <span class="font-bold text-lg text-indigo-700">10</span> registros</p>
      </div>
      <div class="bg-gray-100 pt-4 text-lg">
        <div class="flex py-6 mx-12">
          <div class="flex w-a items-center">
            <span class="uppercase font-bold text-gray-600">Nombre Elemento</span>
          </div>
          <div class="flex w-1/4 items-center justify-end pr-10">
            <span class="uppercase font-bold text-gray-600">Registro</span>
          </div>
          <div class="flex w-b items-center pl-3">
            <span class="uppercase font-bold text-gray-600">Razon Social</span>
          </div>
        </div>
        <div class="overflow-y-scroll">
          <div class="flex h-16 px-12 text-gray-700 hover:bg-blue-200 hover:text-gray-800">
            <div class="flex w-a items-center">
              <span class="font-light">Abacavir Sulfato</span>
            </div>
            <div class="flex w-1/4 items-center justify-end pr-6">
              <span class="font-light">12 de en. de 2010</span>
            </div>
            <div class="flex w-b items-center pl-3">
              <span class="font-light">Laboratorios Recalcine S.A</span>
            </div>
          </div>
        </div>

      </div>
    </div> -->
  </div>
</template> 

<script>
export default {
  name: 'medicine',
  data() {
    return {
      selectedMedicine: 0,
      medicines: [
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]},
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]},
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]},
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]},
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]},
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]},
        {name: "Abacavir", atc: "J05AF06", registers: 17, elements: [{name: "Abacavir Sulfato", register: "12 de en. de 2010", isp: "F-17883/15", provider: "Laboratorios Recalcine S.A", left: 0, expired: "2 semanas", formule: ["Solución inyectable", "500mg"]},]}
      ]
    }
  }
}
</script>

<style>
.w-grow {
  width: calc(100vw - 608px);
}
</style>
