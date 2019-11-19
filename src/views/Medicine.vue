<template>
  <div class="medicine flex h-screen">
    <aside class="px-10 bg-gray-200">
      <div class="mt-12 relative">
        <svg class="absolute h-12 ml-3" fill="#718097" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/></svg>
        <input class="h-12 w-64 pl-12 pr-5 border-2 border-gray-400 rounded-lg text-gray-600 font-light placeholder-gray-600 bg-gray-300 focus:outline-none" type="text">
      </div>
      <div class="mt-10">
        <div class="rounded-lg py-5 px-4 bg-gray-100 shadow-md">
          <div class="flex justify-between">
            <span class="text-gray-700 font-bold">ABACAVIR</span>
            <div class="w-12 flex justify-center bg-gray-300 rounded-full py-px">
              <span class="text-gray-700 font-bold">17</span>
            </div>
          </div>
        </div>
      </div>
    </aside>
  </div>
</template> 

<script>
// @ is an alias to /src

export default {
  name: 'medicine',
  components: {
  }
}
</script>
