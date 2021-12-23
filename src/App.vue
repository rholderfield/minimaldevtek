<template>
  <!-- Hero -->
  <div class="hero">
    <nav class="container-fluid">
      <ul>
        <li>
          <img alt="selfie" src="./assets/selfie.png" class="selfie" />
        </li>
        <li><b>Hi, I'm Ryan</b></li>
      </ul>
      <ul>
        <li>
          <a
            href="https://devtekstorage.blob.core.windows.net/treasurechest/RyanHolderfield.pdf"
            target="_blank"
            >Resume</a
          >
        </li>
        <li>
          <a
            href="https://www.linkedin.com/in/ryan-holderfield/"
            target="_aboutblank"
            ><img src=".\assets\linkedin.svg" alt="Linkedin" class="icon"
          /></a>
        </li>
        <li>
          <a href="https://github.com/rholderfield/" target="_aboutblank"
            ><img src=".\assets\pinned-octocat.svg" alt="Github" class="icon"
          /></a>
        </li>
      </ul>
    </nav>
    <header class="container">
      <hgroup>
        <img src="./assets/Meliodas_Demon_Mark_Anime.png" />
      </hgroup>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisqueet.</p>
      <p>
        <a href="#" role="button" onclick="event.preventDefault()"
          >View Project</a
        >
      </p>
    </header>
  </div>
  <!-- ./ Hero -->

  <!-- Main -->
  <main class="container">
    <div class="grid">
      <section>
        <div class="showcase">
          <a href="https://blockpager.digitaldevtek.com/#/" target="_blank"
            ><img src="./assets/blockpager.png" alt="buildspace web3 nft"
          /></a>
          <div class="container">
            <div class="description">
              <p>
                A project that used Solidity, Javascript, and Hardhat to deploy
                a smart contract in the Rinkeby Test Network (Etherum
                Blockchain). The Web3 client app was built using Vue and
                Ethers.js, allowing interaction with the deployed smart
                contract.
              </p>
            </div>
            <div class="buttonContainer">
              <a
                href="https://blockpager.digitaldevtek.com/#/"
                target="_blank"
                role="button"
                >View Project</a
              >
            </div>
          </div>
        </div>
      </section>
    </div>
  </main>
  <!-- ./ Main -->

  <!-- Footer -->
  <footer class="container">
    <small
      >Built with <a href="https://picocss.com">Pico</a> •
      <a href="https://vuejs.org/">Vue</a></small
    >
  </footer>
  <!-- ./ Footer -->
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style lang="scss">
#app {
  font-family: PT Serif, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

img.selfie {
  width: auto;
  height: 76px;
}

img.icon {
  width: 24px;
  height: 24px;
}

hgroup {
  img {
    height: 267px;
    width: 645px;
  }
}

main {
  padding-top: 28px;
}

div.showcase {
  display: flex;
  background-color: transparent;
  align-items: center;

  img {
    border-radius: 8px;
    height: auto;
    width: 160px;
  }

  p {
    margin: 0px;
    padding-left: 24px;
    text-align: justify;
  }

  .buttonContainer {
    display: flex;
    justify-content: flex-end;
  }
}
</style>
