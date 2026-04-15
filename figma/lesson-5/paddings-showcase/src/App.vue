<script setup>

</script>

<template>
  <main class="main cont">
    <section class="anek">
      <!-- <h2 class="anek__title">Анекдот дня</h2> -->
      <p>— Товарищ капитан, мне на место происшествия одному выехать или с собакой?</p>
      <p>— С собакой, сержант. Один ум – хорошо, а два – лучше.</p>
    </section>
  </main>
</template>

<style>
  .anek {
    display: flex;
    flex-direction: column;
    /* row-gap: 10px; */

    /* padding: 30px 15px; */

    background-color: #F5EDD6;
  
    max-width: 550px;
    margin-left: auto;
    margin-right: auto;
  }
  .anek > * {
    margin: 0;
  }
  .anek__title {
    text-align: center;
    margin: 0;

    /* margin-bottom: 13px; */

    font-weight: 500;
  }
</style>