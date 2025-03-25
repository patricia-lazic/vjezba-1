<template>
  <div class=" bg-gradient-to-br from-cyan-900 to-gray-950 text-white h-screen">
    <div class="text-center py-12">
      <h1 class="text-4xl">Pozdrav, ja sam <span class=" font-bold text-amber-300">Patricia Lazić</span></h1>
    </div>
    <hr class="w-[1024px] mx-auto border-2 rounded-full opacity-75">
    <div>
      <div class="w-[1024px] mx-auto p-4">
        <span class="text-2xl text-amber-400/75">Moji omiljeni filmovi:</span>
      </div>
      <div class="flex items-center justify-center gap-6">
        <div class="flex flex-col gap-4">
          <div class="h-[480px] w-[320px]">
            <img class="w-full h-full object-cover rounded-md" src="./assets/changeling.jpeg" alt="Changeling">
          </div>
          <div class="text-center">
            <h3 class="text-xl">Changeling</h3>
          </div>
        </div>
        <div class="flex flex-col gap-4">
          <div class="h-[480px] w-[320px]">
            <img class="w-full h-full object-cover rounded-md" src="./assets/prisoners.jpg" alt="Prisoners">
          </div>
          <div class="text-center">
            <h3 class="text-xl">Prisoners</h3>
          </div>
        </div>
        <div class="flex flex-col gap-4">
          <div class="h-[480px] w-[320px]">
            <img class="w-full h-full object-cover rounded-md" src="./assets/thesixthsense.jpg" alt="The Sixth Sense">
          </div>
          <div class="text-center">
            <h3 class="text-xl">The Sixth Sense</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
