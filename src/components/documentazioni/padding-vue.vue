<template>
  <section id="p" class="border-b-2 border-violet pb-6 pt-16">
    <h4>Padding</h4>
    <p>
      La proprieta <strong>padding</strong> serve per la spaziatura dal bordo
      dell'elemanto verso il contenuto interno.
    </p>
    <p class="my-3">
      Per la classe <strong>padding</strong> va usato la lettera
      <strong>p</strong> piccola è per le misure si assegnano da 0 a 20.
    </p>
    <p class="mb-2 mt-4 violet-6">.p-(num) => num = 0 ---step 1--> 20</p>
    <div class="bg-green-6 p-3 my-3">
      <div class="orange-6 bg-gray-2 px-2">.p-3</div>
    </div>
    <div class="orange-6 px-2 bg-gray-2">.p-5 | .p-16 | etc.</div>
    <h5 class="response">Response</h5>
    <div class="orange-6 px-2 bg-gray-2">.p-7-sm | .p-12-xl | etc.</div>
    <h5 class="response">Scelta direzione</h5>
    <p>
      Si può scegliere anche la direzione come nella spiegazione del margin.
    </p>
    <p>Basta aggiungere un altra lettera vicino alla prima.</p>
    <table class="mx-auto my-3 collapse">
      <thead>
        <tr>
          <th class="border t-center p-1">TOP</th>
          <th class="border t-center p-1">RIGHT</th>
          <th class="border t-center p-1">BOTTOM</th>
          <th class="border t-center p-1">LEFT</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="border t-center p-1">t</td>
          <td class="border t-center p-1">r</td>
          <td class="border t-center p-1">b</td>
          <td class="border t-center p-1">l</td>
        </tr>
        <tr>
          <td class="border t-center p-1">pt-5</td>
          <td class="border t-center p-1">pr-10</td>
          <td class="border t-center p-1">pb-15</td>
          <td class="border t-center p-1">pl-20</td>
        </tr>
      </tbody>
    </table>
  </section>
</template>


<script>
export default {};
</script>