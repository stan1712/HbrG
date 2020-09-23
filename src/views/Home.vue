<template>
  <div class="home">
    <h1 style="margin-top: 20%;">Bientôt ici, un nouveau site tout beau d'hébergement de fichier</h1>
  </div>
</template>

<script>

export default {
  data: () => ({
    test: process.env.VUE_APP_TITLE
  })
}
</script>
