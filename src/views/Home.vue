<template>
  <div class="home">
    <h1 style="margin-top: 20%;">Bientôt ici, un nouveau site tout beau d'hébergement de fichier</h1>
    <h3>Dans le meilleur des cas, je vais essayer de faire un host avec des comptes utilisateurs comme ça vous retrouverez vos fichiers.</h3>
  </div>
</template>

<script>

export default {
  data: () => ({
    test: process.env.VUE_APP_TITLE
  })
}
</script>
