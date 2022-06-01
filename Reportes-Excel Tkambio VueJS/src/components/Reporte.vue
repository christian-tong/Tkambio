<template>
  <div class="frame">
    <div class="container">
      <div class="header">
        <img class="lazy loaded" src="https://tkambio.com/wp-content/themes/tkambio/inc/assets/img/logo-tkambio.svg"
          data-src="https://tkambio.com/wp-content/themes/tkambio/inc/assets/img/logo-tkambio.svg" alt="TKambio"
          width="206" height="40" data-was-processed="true" />
      </div>

      <div class="title">Generador de reportes TK</div>

      <div class="reportes">
        <div class="booton">
          <a href="https://app.tkambio.com/register" class="booton-text">Crear reporte</a>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.frame {
  border: 50px solid white;
  width: 992px;
  padding: 50px;
  margin: 20px auto;
}

.container {
  border: 1px solid black;
  position: relative;
  background-color: #ffffff;
  width: 992px;
  height: 720px;
}

.header {
  display: grid;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 20px auto;
  gap: 10px;
  width: 992px;
  height: 74px;
  left: 0px;
  top: 0px;
  background: linear-gradient(180deg,
      #02adf1 -2.37%,
      #4562e6 124.84%,
      #4563e6 124.84%);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.header-title {
  width: 180px;
  height: 34px;
  left: calc(50% - 360px / 2);
  top: 129px;
  font-size: 28px;
  line-height: 33px;
  text-align: center;
  color: #181818;
}

.title {
  position: absolute;
  width: 360px;
  height: 33px;
  left: calc(50% - 360px / 2);
  top: 129px;
  font-family: "Argentum Sans", Helvetica;
  font-size: 28px;
  font-weight: 700;
  line-height: 33px;
  text-align: center;
  color: #181818;
}

.reportes {
  border: 1px solid black;
  position: relative;
  background-color: #ffffff;
  top: 50px;
  width: 592px;
  height: 220px;
  justify-content: center;
  display: grid;
}

.booton {
  display: grid;
  justify-content: center;
  align-items: center;
  width: 992px;
  height: 950px;
}

.booton-text {
  display: grid;
  text-decoration: none;
  background: #ffbd12;
  color: #000 !important;
  font-family: "Argentum Sans", Helvetica;
  font-weight: 700;
  border: 1px solid #ffbd12;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 187px;
  height: 43px;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 50px;
}
</style>
