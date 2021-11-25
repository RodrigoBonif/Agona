<template>
<div>
    <nav class="menu">
        <a href="/">Home</a>
        <a href="/">Comunidades</a>
        <a href="/about">Sobre</a>
    </nav>
    <div class="perfil">
        <ion-icon @click="isDisplay = !isDisplay" class="icone-user" name="person-outline"></ion-icon>
    </div>
    <div class="box-perfil" :class="{'open-display': isDisplay}">
        <h2 class="text-green">Perfil</h2>
         <p class="text-white">/*Nome*/</p>  <!-- ou user, caso a pessoa não esteja logado  -->
        <a href="/" class="link-perfil text-white">Gerenciar Perfil</a>
    </div>

    <main class="corpo">
      <router-view/>
    </main>

</div>
</template>

<script>
export default {
  data() {
    return {
      isDisplay: false
    }
  }
}
</script>
