<template>
  <section
    id="Get-Start"
    class="overflow-hidden border-b-2 border-violet pb-6 pt-16"
  >
    <h3 class="mb-3">Iniziamo</h3>
    <h4>Intro</h4>
    <p>
      <span>Fucssia</span> è un framework open source, svilupato con il
      <strong>CSS</strong> per la facilitazione dei sviluppatori con il
      <strong>style</strong> della paggina web. Ricorda che Fucssia non ti
      toglie tutto il lavoro di scrivere del CSS fatto a mano, è solo un
      strumento con varie <span>class</span> <strong>classi</strong> che tu
      semplicemento le puoi aggiungere nel tuo HTML, è spero che tu sapia
      qualcosa di CSS, sapento il minimo CSS vedrai che le classi le sai gia
      scrivere.
    </p>
    <p class="mt-2">
      <strong>Class</strong> classi? Si hai visto bene, Fucssia usa solo le
      classi con diverse combinazioni, che fidati non sono dificili da sapere se
      conosci del CSS ovviamente.
    </p>
    <h4 class="mt-7">Instalazione</h4>
    <p>
      Nel tag <strong> {{ head }} </strong> del file desiderato, inserire la
      seguente stringa, in un posto che ti piace:
    </p>
    <p class="auto bg-gray-7 p-2 aqua my-3">{{ link }}</p>
    <p>
      Inutile dire che ogni classe che vedrai, va inserito nel attributo
      <strong class="azure-7">class</strong> del elemento tag nel tuo codice
      HTML tra gli apici.
    </p>
    <p class="bold my-2">{{ es }}</p>
    <p>
      Metti del contenuto in qualche tag che desideri è si comincia con le
      classi.
    </p>
  </section>
</template>


<script>
export default {
  data() {
    return {
      link: '<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/M6Irinel/Framkcss@7afed426c3eb96b21f164839fc10279163084c3c/Framkcss.css>',
      es: '<div class="here-class-Fucssia"> --content-- </div>',
      head: "<head> --here Fucssia-- </head>",
    };
  },
};
</script>