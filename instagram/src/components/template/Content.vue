<template>
  <div class="content-wrapper">
    <div class="content">
      <div class="cellphone">
        <img src="../../assets/cellphone.png" alt="CellPhone" />
      </div>
      <div class="box-login">
        <div class="boxes">
          <img
            src="../../assets/instagramText.png"
            alt="Instagram"
            height="50px"
          />
          <div class="profile-photo">
            <img
              src="../../assets/profilephoto.jpg"
              alt="Profile-Photo"
              height="130px"
              width="130px"
            />
          </div>
          <a href="https://www.instagram.com/" target="_blank" class="login"
            >Continuar como luizarthur.fortunato</a
          >
          <a href="https://www.instagram.com/" target="_blank" class="logout"
            >Trocar de conta</a
          >
        </div>
        <hr />
        <div class="boxes">
          <p class="not-account">Não é luizarthur.fortunato?</p>
          <p class="not-account">
            <span class="link-blue">
              <a
                href="https://www.instagram.com/accounts/emailsignup/"
                target="v_blank"
                >Alternar contas</a
              >
            </span>
            ou
            <span class="link-blue">
              <a
                href="https://www.instagram.com/accounts/emailsignup/"
                target="v_blank"
                >Inscreva-se</a
              >
            </span>
          </p>
        </div>
        <div class="get-the-app">
          <p class="get-app">Baixe o aplicativo</p>
          <div class="download">
            <a
              href="https://apps.apple.com/app/instagram/id389801252?vt=lo"
              target="_blank"
              class="app-download"
            >
              <img
                src="../../assets/app-store.png"
                alt="app-store"
                class="apple"
              />
            </a>
            <a
              href="https://play.google.com/store/apps/details?id=com.instagram.android&referrer=utm_source%3Dinstagramweb%26utm_campaign%3DloginPage%26ig_mid%3D1CDE93CE-0EA5-4434-815F-A40B407BC28B%26utm_content%3Dlo%26utm_medium%3Dbadge"
              target="_blank"
              class="app-download"
            >
              <img
                src="../../assets/googlePlay.png"
                alt="google-play"
                class="google-play"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content",
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: nopne;
  font-family: sans-serif;
  font-size: 14px;
}

.content-wrapper {
  grid-area: content-wrapper;
  width: 100%;
  min-height: 90vh;
  background-color: #f3f3f3;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
}

.content {
  display: flex;
  align-items: center;
  justify-content: start;
  width: 60%;
}

.cellphone {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50%;
}

.cellphone img {
  height: 45rem;
}

.box-login {
  display: flex;
  flex-direction: column;
  width: 38%;
  height: 40rem;
}

.box-login hr {
  border: transparent;
}

.boxes {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: column;
  background-color: #fff;
  width: 100%;
  padding: 1.3rem 0;
  border: 1px solid lightgray;
}

.boxes .login:hover {
  text-decoration: none;
  color: #fff;
}
.boxes .logout:hover {
  text-decoration: none;
  color: #0095f6;
}

.boxes:nth-child(1) {
  height: 22rem;
}

.instagram-text {
  height: 3rem;
}

.profile-photo {
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  overflow: hidden;
}

.login {
  background-color: #0095f6;
  color: #fff;
  padding: 5px 30px;
  border-radius: 4px;
  margin-top: 1rem;
}

.logout {
  color: #0095f6;
  margin-top: 1rem;
}

.not-account {
  color: #a0a0a0;
}

.link-blue {
  color: #0095f6;
}

.link-blue a:hover {
  color: #0095f6;
  text-decoration: none;
}

.get-the-app {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  padding: 1.3rem 0;
}

.download {
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  align-items: center;
  padding: 1rem;
}

.app-download img {
  display: flex;
  align-items: center;
}

.app-download .apple {
  height: 4rem;
  width: 12.5rem;
}

.app-download .google-play {
  height: 3.5rem;
  width: 12rem;
}

@media (max-width: 1024px) {
  .content {
    width: 90%;
  }
}

@media (max-width: 650px) {
  .body {
    background-color: #fff;
  }
  .content {
    width: 90%;
  }
  .cellphone {
    display: none;
  }
  .box-login {
    width: 100%;
  }
}
</style>
