<template>
  <section id="w" class="border-b-2 border-violet pb-6 pt-16">
    <h4>Width</h4>
    <p>
      La proprieta <strong>width</strong> va utilizata per la dimensione sulla
      <strong>asse X</strong> dello schermo. Può essere usato con diversi tipi
      di misure, le misure di Fucssia per questa proprieta sono di due tipi: il
      percentuale (%) è la misura in percentuale della window (vw). Anche se si
      asomigliano, le due percentiagli sono diverse come funzionamento. La prima
      prende la misura dal elemento tag che lo contiene è il secondo la misura
      del window (intera paggina web).
    </p>
    <p class="my-3">
      Per la classe <strong>width</strong> va semplicemente usato la lettera
      <strong>w</strong> piccola è per le misure si assegnano da 0 a 100 con
      step di 5.
    </p>
    <p class="mb-2 mt-4 violet-6">.w-(num) => num = 0 ---step 5--> 100 (%)</p>
    <div class="bg-gray-2 px-2 orange-6 w-25">.w-25</div>
    <div class="bg-gray-3 px-2 orange-6 w-50">.w-50</div>
    <div class="bg-gray-4 px-2 orange-6 w-75">.w-75</div>
    <p class="mb-2 mt-4 violet-6">
      .w-(num)vw => num = 0 ---step 5--> 100 (vw)
    </p>
    <div class="bg-gray-2 px-2 orange-6 w-25vw">.w-25vw</div>
    <div class="bg-gray-3 px-2 orange-6 w-50vw">.w-50vw</div>
    <div class="bg-gray-4 px-2 orange-6 w-65vw">.w-65vw</div>
    <h5 class="response">Response</h5>
    <div class="bg-gray-2 px-2 orange-6 w-25-sm">.w-25-sm</div>
    <div class="bg-gray-3 px-2 orange-6 w-40-md">.w-40-md</div>
    <div class="bg-gray-4 px-2 orange-6 w-55-lg">.w-55-lg</div>
    <div class="bg-gray-5 px-2 orange-6 w-70-xl">.w-70-xl</div>
    <div class="bg-gray-6 px-2 orange-6 w-85-xxl">.w-85-xxl</div>
  </section>
</template>


<script>
export default {};
</script>