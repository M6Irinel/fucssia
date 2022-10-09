<template>
  <section id="container" class="border-b-2 border-violet pb-6 pt-16">
    <h4>Container</h4>
    <p>
      La classe <span>container</span> viene usato per adattare in modo reativo
      il contenuto della tua paggina web, questo tipo di addatamento viene usato
      anche in altri diversi <strong>framwork</strong>.
    </p>
    <table class="my-3 mx-auto collapse">
      <thead>
        <tr>
          <th class="border p-1 t-center">name class</th>
          <th class="border p-1 t-center">sm >= 576px</th>
          <th class="border p-1 t-center">md >= 768px</th>
          <th class="border p-1 t-center">lg >= 992px</th>
          <th class="border p-1 t-center">xl >= 1200px</th>
          <th class="border p-1 t-center">xxl >= 1400px</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="border p-1 t-center">.container + dimension</td>
          <td class="border p-1 t-center">540px</td>
          <td class="border p-1 t-center">720px</td>
          <td class="border p-1 t-center">960px</td>
          <td class="border p-1 t-center">1140px</td>
          <td class="border p-1 t-center">1320px</td>
        </tr>
      </tbody>
    </table>
    <div class="bg-gray-1 orange-6 px-2 container">.container</div>
    <div class="bg-gray-2 orange-6 px-2 container-sm">.container-sm</div>
    <div class="bg-gray-3 orange-6 px-2 container-md">.container-md</div>
    <div class="bg-gray-4 orange-6 px-2 container-lg">.container-lg</div>
    <div class="bg-gray-5 orange-6 px-2 container-xl">.container-xl</div>
    <div class="bg-gray-6 orange-6 px-2 container-xxl">.container-xxl</div>
    <h3 class="mt-7">
      <span class="orange-6">Attenzione</span>: Fucssia usa il metodo
      mobile-first, l'estensione della classe in varie dimensioni va pensato
      solo in mobile first, tradotto come, "da una dimensione fissa la classe
      viene eseguita verso una dimensione infinita con l'estensione aggiunta
      delle varie dimensioni".
    </h3>
  </section>
</template>


<script>
export default {};
</script>