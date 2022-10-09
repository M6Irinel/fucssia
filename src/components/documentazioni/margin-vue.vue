<template>
  <section id="m" class="border-b-2 border-violet pb-6 pt-16">
    <h4>Margin</h4>
    <p>
      La proprieta <strong>margin</strong> serve per la spaziatura dal bordo
      dell'elemanto verso altri elementi esterni.
    </p>
    <p class="my-3">
      Per la classe <strong>margin</strong> va usato la lettera
      <strong>m</strong> piccola è per le misure si assegnano da 0 a 20.
    </p>
    <p class="mt-4 violet-6">.m-(num) => num = 0 ---step 1--> 20</p>
    <div class="bg-green-6 p-1 my-3">
      <div class="orange-6 px-2 bg-gray-2 m-3">.m-3</div>
    </div>
    <p>
      Si puo andare anche in <strong>negativo</strong> basta che si aggiunge un
      meno al inizio.
    </p>
    <div class="orange-6 px-2 bg-gray-2 my-3">.-m-3 | .-m-18 | etc.</div>
    <h5 class="response">Response</h5>
    <div class="orange-6 px-2 bg-gray-2">.-m-5-sm | .-m-14-xl | etc.</div>
    <h5 class="response">Scelta direzione</h5>
    <p>
      Si può scegliere anche la direzione per il spazio, come ad esempio voglio
      solo del spazio sopra e in basso, o sinistra e destra, o sinistra e sopra,
      o solo in basso, etc.
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
          <td class="border t-center p-1">mt-5</td>
          <td class="border t-center p-1">-mr-10</td>
          <td class="border t-center p-1">-mb-15</td>
          <td class="border t-center p-1">ml-20</td>
        </tr>
      </tbody>
    </table>
  </section>
</template>


<script>
export default {};
</script>