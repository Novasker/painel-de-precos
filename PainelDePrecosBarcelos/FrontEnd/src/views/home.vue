<template>
  <div class="home-container">
    <div class="home-container01">
      <div class="home-container02">
        <div class="home-container03">
          <div class="home-container04">
            <span class="home-text">Imperdível</span>
          </div>
        </div>
        <div class="home-container05">
          <img
            alt="image"
            src="/playground_assets/promocao-300h.jpg"
            class="home-image"
          />
          <img
            alt="image"
            src="/playground_assets/promocao-300h.jpg"
            class="home-image1"
          />
          <img
            alt="image"
            src="/playground_assets/promocao-300h.jpg"
            class="home-image2"
          />
          <img
            alt="image"
            src="/playground_assets/promocao-300h.jpg"
            class="home-image3"
          />
        </div>
      </div>
      <div class="home-container06">
        <div class="home-container07">
          <div class="home-container08">
            <img
              alt="image"
              src="/playground_assets/logo-200h.png"
              class="home-image4"
            />
          </div>
        </div>
        <div class="home-container09">
          <div class="home-container10">
            <div class="home-container11">
              <span class="home-text01">Aves</span>
            </div>
            <div class="home-container12">
              <div class="home-container13">
                <span class="home-text02">Código</span>
              </div>
              <div class="home-container14">
                <span class="home-text03">Produto</span>
              </div>
              <div class="home-container15">
                <span class="home-text04">Preço</span>
              </div>
            </div>
            <div class="home-container16">
              <div class="home-container17">
                <span class="home-text05">123456</span>
              </div>
              <div class="home-container18">
                <span class="home-text06">Contra Filé</span>
              </div>
              <div class="home-container19">
                <span class="home-text07">30,99 KG</span>
              </div>
            </div>
          </div>
          <div class="home-container20">
            <div class="home-container21">
              <span class="home-text08">Bovinos</span>
            </div>
            <div class="home-container22">
              <div class="home-container23">
                <span class="home-text09">Código</span>
              </div>
              <div class="home-container24">
                <span class="home-text10">Produto</span>
              </div>
              <div class="home-container25">
                <span class="home-text11">Preço</span>
              </div>
            </div>
            <div class="home-container26">
              <div class="home-container27">
                <span class="home-text12">123456</span>
              </div>
              <div class="home-container28">
                <span class="home-text13">Contra Filé</span>
              </div>
              <div class="home-container29">
                <span class="home-text14">30,99 KG</span>
              </div>
            </div>
          </div>
          <div class="home-container30">
            <div class="home-container31">
              <span class="home-text15">Suínos</span>
            </div>
            <div class="home-container32">
              <div class="home-container33">
                <span class="home-text16">Código</span>
              </div>
              <div class="home-container34">
                <span class="home-text17">Produto</span>
              </div>
              <div class="home-container35">
                <span class="home-text18">Preço</span>
              </div>
            </div>
            <div class="home-container36">
              <div class="home-container37">
                <span class="home-text19">123456</span>
              </div>
              <div class="home-container38">
                <span class="home-text20">Contra Filé</span>
              </div>
              <div class="home-container39">
                <span class="home-text21">30,99 KG</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  metaInfo: {
    title: 'Sistema de Painel de Preços',
    meta: [
      {
        name: 'description',
        content:
          'O Sistema de Painel de Preços pode ser utilizado em Açougues, Padarias e Comércios de modo geral.',
      },
      {
        property: 'og:title',
        content: 'Sistema de Painel de Preços',
      },
      {
        property: 'og:description',
        content:
          'O Sistema de Painel de Preços pode ser utilizado em Açougues, Padarias e Comércios de modo geral.',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-container01 {
  flex: 1;
  width: 100%;
  height: 100%;
  display: flex;
  position: relative;
  flex-wrap: wrap;
  align-self: center;
  margin-top: 0px;
  align-items: flex-start;
  margin-left: 0px;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-halfunit);
  margin-bottom: 0px;
  padding-right: var(--dl-space-space-halfunit);
  padding-bottom: var(--dl-space-space-halfunit);
  background-size: cover;
  justify-content: center;
  background-image: url("/playground_assets/background-min-1500w.jpg");
}
.home-container02 {
  flex: 0;
  width: 273px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-container03 {
  width: 100%;
  height: 150px;
  margin: var(--dl-space-space-unit);
  display: flex;
  opacity: 0.75;
  align-self: center;
  margin-top: var(--dl-space-space-halfunit);
  align-items: center;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
  background-color: var(--dl-color-gray-black);
}
.home-container04 {
  display: flex;
  position: relative;
}
.home-text {
  color: white;
  z-index: 100;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
  padding-left: var(--dl-space-space-halfunit);
  padding-right: var(--dl-space-space-halfunit);
}
.home-container05 {
  gap: var(--dl-space-space-fourunits);
  height: var(--dl-size-size-maxwidth);
  display: flex;
  align-self: center;
  margin-top: 0px;
  align-items: flex-start;
  margin-left: 0p0x;
  margin-right: 0p0x;
  margin-bottom: 0px;
  flex-direction: column;
  justify-content: flex-start;
}
.home-image {
  width: 100%;
  height: 259px;
  margin-top: var(--dl-space-space-unit);
  object-fit: cover;
}
.home-image1 {
  width: 100%;
  height: 254px;
  object-fit: cover;
}
.home-image2 {
  width: 100%;
  height: 254px;
  object-fit: cover;
}
.home-image3 {
  width: 100%;
  height: 254px;
  object-fit: cover;
}
.home-container06 {
  flex: 1;
  width: 926px;
  height: 100%;
  display: flex;
  position: relative;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-container07 {
  flex: 0;
  width: 100%;
  display: flex;
  align-self: center;
  margin-top: var(--dl-space-space-halfunit);
  align-items: center;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.home-container08 {
  flex: 1;
  width: var(--dl-size-size-xxlarge);
  height: 150px;
  display: flex;
  position: relative;
  margin-top: var(--dl-space-space-halfunit);
  align-items: center;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: column;
  justify-content: center;
  background-color: white;
}
.home-image4 {
  width: auto;
  height: 100%;
  align-self: center;
  object-fit: cover;
}
.home-container09 {
  flex: 1;
  width: 100%;
  height: 853px;
  display: flex;
  flex-wrap: wrap;
  margin-top: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-container10 {
  flex: 1;
  width: var(--dl-size-size-xxlarge);
  height: var(--dl-size-size-maxwidth);
  display: flex;
  opacity: 0.75;
  z-index: 1;
  align-self: flex-start;
  margin-top: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: column;
  justify-content: flex-start;
  background-color: var(--dl-color-gray-black);
}
.home-container11 {
  width: 100%;
  height: 70px;
  display: flex;
  opacity: 1;
  align-items: center;
  justify-content: center;
}
.home-text01 {
  color: white;
  z-index: 1000;
  font-size: 35px;
  font-style: normal;
  font-weight: 700;
}
.home-container12 {
  width: 100%;
  height: 67px;
  display: flex;
  opacity: 1;
  align-items: flex-start;
  justify-content: flex-start;
}
.home-container13 {
  flex: 1;
  width: 100%;
  height: 70px;
  display: flex;
  align-self: center;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
.home-text02 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-end;
}
.home-container14 {
  flex: 2;
  width: 133px;
  height: 70px;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text03 {
  color: var(--dl-color-gray-white);
  z-index: 100;
  font-size: 25px;
  align-self: flex-start;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-container15 {
  flex: 1;
  width: 133px;
  height: 70px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text04 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
}
.home-container16 {
  width: 100%;
  height: 46px;
  display: flex;
  position: relative;
  align-items: flex-start;
  justify-content: flex-start;
}
.home-container17 {
  flex: 1;
  width: 100%;
  height: 50px;
  display: flex;
  align-self: center;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
.home-text05 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-end;
}
.home-container18 {
  flex: 2;
  width: 133px;
  height: 50px;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text06 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-start;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-container19 {
  flex: 1;
  width: 133px;
  height: 50px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text07 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
}
.home-container20 {
  flex: 1;
  width: var(--dl-size-size-xxlarge);
  height: var(--dl-size-size-maxwidth);
  display: flex;
  opacity: 0.75;
  z-index: 1;
  align-self: flex-start;
  margin-top: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: column;
  justify-content: flex-start;
  background-color: var(--dl-color-gray-black);
}
.home-container21 {
  width: 100%;
  height: 70px;
  display: flex;
  opacity: 1;
  align-items: center;
  justify-content: center;
}
.home-text08 {
  color: white;
  z-index: 1000;
  font-size: 35px;
  font-style: normal;
  font-weight: 700;
}
.home-container22 {
  width: 100%;
  height: 67px;
  display: flex;
  opacity: 1;
  align-items: flex-start;
  justify-content: flex-start;
}
.home-container23 {
  flex: 1;
  width: 100%;
  height: 70px;
  display: flex;
  align-self: center;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
.home-text09 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-end;
}
.home-container24 {
  flex: 2;
  width: 133px;
  height: 70px;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text10 {
  color: var(--dl-color-gray-white);
  z-index: 100;
  font-size: 25px;
  align-self: flex-start;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-container25 {
  flex: 1;
  width: 133px;
  height: 70px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text11 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
}
.home-container26 {
  width: 100%;
  height: 46px;
  display: flex;
  position: relative;
  align-items: flex-start;
  justify-content: flex-start;
}
.home-container27 {
  flex: 1;
  width: 100%;
  height: 50px;
  display: flex;
  align-self: center;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
.home-text12 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-end;
}
.home-container28 {
  flex: 2;
  width: 133px;
  height: 50px;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text13 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-start;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-container29 {
  flex: 1;
  width: 133px;
  height: 50px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text14 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
}
.home-container30 {
  flex: 1;
  width: var(--dl-size-size-xxlarge);
  height: var(--dl-size-size-maxwidth);
  display: flex;
  opacity: 0.75;
  z-index: 1;
  align-self: flex-start;
  margin-top: var(--dl-space-space-halfunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: column;
  justify-content: flex-start;
  background-color: var(--dl-color-gray-black);
}
.home-container31 {
  width: 100%;
  height: 70px;
  display: flex;
  opacity: 1;
  align-items: center;
  justify-content: center;
}
.home-text15 {
  color: white;
  z-index: 1000;
  font-size: 35px;
  font-style: normal;
  font-weight: 700;
}
.home-container32 {
  width: 100%;
  height: 67px;
  display: flex;
  opacity: 1;
  align-items: flex-start;
  justify-content: flex-start;
}
.home-container33 {
  flex: 1;
  width: 100%;
  height: 70px;
  display: flex;
  align-self: center;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
.home-text16 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-end;
}
.home-container34 {
  flex: 2;
  width: 133px;
  height: 70px;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text17 {
  color: var(--dl-color-gray-white);
  z-index: 100;
  font-size: 25px;
  align-self: flex-start;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-container35 {
  flex: 1;
  width: 133px;
  height: 70px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text18 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
}
.home-container36 {
  width: 100%;
  height: 46px;
  display: flex;
  position: relative;
  align-items: flex-start;
  justify-content: flex-start;
}
.home-container37 {
  flex: 1;
  width: 100%;
  height: 50px;
  display: flex;
  align-self: center;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
.home-text19 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-end;
}
.home-container38 {
  flex: 2;
  width: 133px;
  height: 50px;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-text20 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
  align-self: flex-start;
  margin-left: var(--dl-space-space-oneandhalfunits);
}
.home-container39 {
  flex: 1;
  width: 133px;
  height: 50px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text21 {
  color: var(--dl-color-gray-white);
  font-size: 25px;
}
@media(max-width: 1600px) {
  .home-container01 {
    padding-top: var(--dl-space-space-halfunit);
    padding-left: var(--dl-space-space-halfunit);
    padding-right: var(--dl-space-space-halfunit);
    padding-bottom: var(--dl-space-space-halfunit);
  }
  .home-container03 {
    height: 150px;
    margin-top: var(--dl-space-space-unit);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text {
    padding-left: var(--dl-space-space-halfunit);
    padding-right: var(--dl-space-space-halfunit);
  }
  .home-container05 {
    margin-top: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: 0px;
  }
  .home-image {
    margin-top: var(--dl-space-space-unit);
  }
  .home-container06 {
    position: relative;
  }
  .home-container07 {
    flex: 0;
    width: 100%;
    margin: 0px;
    align-self: center;
    margin-top: var(--dl-space-space-halfunit);
    margin-left: var(--dl-space-space-halfunit);
    margin-right: var(--dl-space-space-halfunit);
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .home-container08 {
    flex: 1;
    width: var(--dl-size-size-xxlarge);
    height: 150px;
    margin-top: var(--dl-space-space-halfunit);
    margin-left: var(--dl-space-space-halfunit);
    margin-right: var(--dl-space-space-halfunit);
    margin-bottom: var(--dl-space-space-halfunit);
    background-color: white;
  }
  .home-image4 {
    width: auto;
    height: 100%;
    align-self: center;
  }
  .home-container09 {
    flex: 1;
    align-items: flex-start;
    justify-content: flex-start;
  }
}
@media(max-width: 1200px) {
  .home-container13 {
    flex: 1;
    width: 179px;
    align-self: flex-start;
    align-items: center;
  }
  .home-text02 {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-container14 {
    flex: 2;
    width: 162px;
  }
  .home-text05 {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-container18 {
    flex: 2;
  }
  .home-container23 {
    flex: 1;
    width: 179px;
    align-self: flex-start;
    align-items: center;
  }
  .home-text09 {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-container24 {
    flex: 2;
    width: 162px;
  }
  .home-text12 {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-container28 {
    flex: 2;
  }
  .home-container33 {
    flex: 1;
    width: 179px;
    align-self: flex-start;
    align-items: center;
  }
  .home-text16 {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-container34 {
    flex: 2;
    width: 162px;
  }
  .home-text19 {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-container38 {
    flex: 2;
  }
}
@media(max-width: 991px) {
  .home-container06 {
    width: 100%;
    align-self: flex-start;
    margin-right: var(--dl-space-space-halfunit);
    flex-direction: column;
  }
  .home-container09 {
    align-items: flex-start;
    justify-content: flex-start;
  }
  .home-container10 {
    flex: 1;
  }
}
@media(max-width: 767px) {
  .home-image4 {
    width: 100%;
  }
  .home-container10 {
    align-self: flex-start;
  }
}
</style>
