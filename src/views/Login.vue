<template>
  <div id="login">
            <form class="comeco">
                <div class="card-header">
                    <h2>Login</h2>
                </div>
                <div class="conteudo">
                    <div class="card-content-area">
                        <label for="usuario">Usuário</label>
                        <input type="text" id="usuario" autocomplete="off">
                    </div>
                    <div class="card-content-area">

                        <label for="password">Senha</label>

                        <input type="password" id="password" autocomplete="off">
                    </div>
                </div>
                <div class="footer">

                    <input type="submit" value="login" class="submit">

                    <a href="#" class="recuperar_senha">Esqueceu a senha?</a>
                </div>
            </form>
        </div>
</template>

<script>
export default {

}
</script>

<style>

</style>