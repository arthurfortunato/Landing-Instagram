<template>
  <footer class="footer">
    <div class="tags">
      <p>
        <a href="https://about.instagram.com/">Sobre </a>
        <a href="https://about.instagram.com/pt-br/blog"> Blog </a>
        <a href="https://help.instagram.com/"> Ajuda </a>
        <a href="https://www.instagram.com/developer/"> API </a>
        <a href="https://help.instagram.com/519522125107875"> Privacidade </a>
        <a href="https://help.instagram.com/581066165581870"> Termos </a>
        <a href="https://www.instagram.com/directory/profiles/">
          Contas mais relevantes
        </a>
        <a href="https://www.instagram.com/directory/hashtags/"> Hashtags </a>
        <a href="https://www.instagram.com/explore/locations/">
          Localizações
        </a>
        <a href="https://www.instagram.com/topics/beauty/"> Beleza </a>
        <a href="https://www.instagram.com/topics/dance-and-performance/">
          Dança e apresentação
        </a>
        <a href="https://www.instagram.com/topics/fitness/"> Fitness </a>
        <a href="https://www.instagram.com/topics/food-and-drink/">
          Comida e bebida
        </a>
        <a href="https://www.instagram.com/topics/home-and-garden/">
          Casa e jardim
        </a>
        <a href="https://www.instagram.com/topics/music/"> Música </a>
        <a href="https://www.instagram.com/topics/visual-arts/">
          Artes visuais
        </a>
      </p>
      <div class="merchan">
        <span>
          Desenvolvido com <i class="fa fa-heart text-danger"></i> por
          <strong>@luizarthur. <i class="text-danger">F</i>ortunato </strong>
        </span>
        <div class="icone">
          <a
            href="https://www.linkedin.com/in/arthur-forturnato-643828187/"
            target="_blank"
          >
            <img
              src="../../assets/linkedin.png"
              alt="Linkedin"
              height="17px"
              width="17px"
            />
          </a>
          <a
            class="instagram"
            href="https://www.instagram.com/luizarthur.fortunato/"
            target="_blank"
          >
            <img
              src="../../assets/instagram.png"
              alt="Instagram"
              height="17px"
              width="17px"
            />
          </a>
          <a href="https://github.com/arthurfortunato" target="_blank">
            <img
              src="../../assets/gitlogo.png"
              alt="GitHub"
              height="17px"
              width="30px"
            />
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style>
.footer {
  grid-area: footer;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 10vh;
  background-color: #f3f3f3;
  display: flex;
  justify-content: center;
  align-items: center;
}

.tags p {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  width: 75%;
  padding-left: 30rem;
}

.tags a {
  padding-right: 20px;
  color: #857f7f;
}

.tags a:hover {
  text-decoration: none;
  color: #857f7f;
}

.merchan {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.icone {
  padding-left: 10px;
}
.icone a {
  padding-right: 5px;
}
</style>