<template>
  <div>
    <q-card class="body">
      <q-card-section>
        <!-- Área Header-->
        <header class="cb">
          <!-- cb = cabecalho-->
          <img class="cb-img" src="../assets/logo.svg" alt="logo" />
          <nav class="cb-menu">
            <a
              class="cb-menu-item"
              href="https://www.disneyplus.com/pt-br"
              target="_blank"
              >Disney+</a
            >
            <a
              class="cb-menu-item"
              href="https://disney.fandom.com/pt-br/wiki/Merida"
              target="_blank"
              >História Completa</a
            >
            <a
              class="cb-menu-item"
              href="https://www.legiaodosherois.com.br/2021/princesas-disney-todas-ordem.html"
              target="_blank"
              >Princess</a
            >
          </nav>
        </header>
      </q-card-section>

      <q-separator color="white" />

      <q-card-section>
        <!-- Área Main -->
        <main>
          <q-card-section class="ct-p">
            <!-- ct-p = conteudo principal -->
            <div>
              <h1 class="ct-p-titulo">Be Brave</h1>
              <h2 class="ct-p-subtitulo">Seja valente como a Merida!</h2>
              <a
                href="https://www.youtube.com/watch?v=5fPmKfcaaWk"
                target="_blank"
                ><button class="ct-p-botao">Venha conhece-lá</button></a
              >
            </div>
            <img class="ct-p-img" src="../assets/merida.svg" alt="merida" />
          </q-card-section>
          <q-card-section class="ct-s">
            <!-- ct-s = conteudo secundario -->
            <h3 class="ct-s-titulo">Quem é Merida?</h3>
            <p class="ct-s-paragrafo">
              A <strong>princesa Merida</strong> é uma das minhas princesas
              favoritas, por que ela mostra que você pode ir atrás do seu
              destino mesmo que a sua vida esteja sendo controlada por alguém.
              Ela é umas das princesas mais corajosas da disney de apenas 16
              anos que não concorda com a ideia de casamento que sua mãe quer
              pra ela, mas para isso ela decide competir pela sua própria mão,
              através dos jogos de arco e flecha, deixando sua mãe, a
              <strong>Rainha Elinor</strong> furiosa. Mas no fim, o vínculo de
              mãe e filha é maior que tudo que aconteceu, reconstruindo esse
              vínculo novamente.
            </p>
          </q-card-section>
        </main>
      </q-card-section>

      <q-separator color="white" />

      <q-card-section>
        <!-- Área Footer -->
        <footer class="rd">
          <!-- rd = rodape -->
          <img class="rd-img" src="../assets/merida-texto.svg" alt="Merida" />
        </footer>
      </q-card-section>
    </q-card>
  </div>
</template>
<script setup></script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Righteous&family=Sarala:wght@400;700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
}

.body {
  font-size: 100%;
  background: linear-gradient(68.15deg, #0a141e, #1f4d6e 85.61%);
}

.cb {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  padding: 24px;
}

.cb-img {
  height: 72px;
}

.cb-menu {
  display: flex;
  gap: 32px;
}

.cb-menu-item {
  font-family: "Sarala", sans-serif;
  color: #e7f9ff;
  font-weight: 400;
  font-size: 18px;
}

.ct-p {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
}

.ct-p-titulo {
  font-family: "Righteous", cursive;
  font-weight: 400;
  font-size: 64px;
  color: #e7f9ff;
}

.ct-p-subtitulo {
  font-family: "Sarala", sans-serif;
  font-weight: 400;
  font-size: 24px;
  color: #e7f9ff;
}

.ct-p-botao {
  background-color: #65e1ec;
  border-radius: 20px;
  width: 185px;
  height: 67px;
  border: none;
  box-shadow: 4px 5px 4px rgba(0, 0, 0, 0.25);
  font-family: "Sarala", sans-serif;
  font-weight: 400;
  font-size: 20px;
  color: #2f2325;
  cursor: pointer;
}

.ct-p-botao:hover {
  background-color: rgba(174, 227, 236, 0.897);
}
.ct-p-img {
  margin-top: 15px;
  height: 430px;
}

.ct-s {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
  margin-top: 48px;
}

.ct-s-titulo {
  border-top: 0.4px solid #e7f9ff;
  padding-top: 38px;
  font-family: "Righteous", cursive;
  font-weight: 400;
  font-size: 20px;
  color: #e7f9ff;
  margin-bottom: 16px;
}

.ct-s-paragrafo {
  font-family: "Sarala", sans-serif;
  margin-bottom: 20px;
  font-weight: 300;
  font-size: 18px;
  color: #e7f9ff;
  width: 800px;
  text-indent: 1.5em;
  text-align: center;
}

.rd {
  padding: 32px;
}

.rd-img {
  height: 48px;
  display: block;
  margin: 0 auto;
}
</style>
