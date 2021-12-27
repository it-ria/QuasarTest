<template>
  <div class="col-lg-3">
    <q-card class="my-card">
      <img :src="article.urlToImage" />

      <q-card-section>
        <div class="text-h6">{{ article.title }}</div>
        <div class="text-subtitle2">by {{ article.author }}</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ article.description }}
      </q-card-section>
    </q-card>
  </div>
</template>

<script>
export default {
  props: {
    article: null,
  },
};
</script>

<style></style>
