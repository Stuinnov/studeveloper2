<template>
  <div class="productPage btn-shade">
    <div class="myPage" id="menu">
      <Navbar />
    </div>
    <section>
      <div class="page-heder">
        <h1 class="page-heder-H">
          Welcome To <span class="text-color">STU Innovations</span>
        </h1>
        <p class="page-heder-description">
          "For the benefit of the whole group here at STU Innovations",<br />
          I need to thank you for the chance to acquire your business as your
          supplier of website composition administrations.
        </p>
      </div>
      <div class="page-banaer" style="text-align: center">
        <img style="width: 145px; height: 123px;" src="/images/poptin-bird-flying.gif" 
        loading="lazy" alt="" width="120" height="120">
        <h1 style="margin-bottom: -1.5rem">Welcome</h1>

        <p
          class="page-heder-description"
          style="color: rgb(0 0 0); font-size: 21px"
        >
          "For the benefit of the whole group here at STU Innovations", I need
          to thank you for the chance to acquire your business as your supplier
          of website composition administrations. There are a great many
          organizations offering these administrations that you could have
          picked, but here we are, with a chance to win your business. I can't
          downplay the amount we value having the option to place this
          proposition before you today.
        </p>
      </div>
      <div class="page-heder-rro row container">
        <div class="Efficiency">
          <div class="Efficiency-box">
            <div class="Efficiency-heading">
              <h4>Workforce Efficiency</h4>
            </div>
            <div class="Efficiency-subheading">
              <p>
                Fully mobile work orders and smart <br />
                maintenance management
              </p>
            </div>
          </div>
          <div class="Efficiency-box">
            <div class="Efficiency-heading">
              <h4>Asset Efficiency</h4>
            </div>
            <div class="Efficiency-subheading">
              <p>
                Real-time performance monitoring<br />
                with fault detection and diagnostics
              </p>
            </div>
          </div>
          <div class="Efficiency-box">
            <div class="Efficiency-heading">
              <h4>Energy Efficiency</h4>
            </div>
            <div class="Efficiency-subheading">
              <p>
                Predictive energy analytics and <br />
                actionable insights across portfolio
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "../components/Navbar";

export default {
  components: {
    Navbar,
  },
  head() {
    return {
      title: "STU Innovations Private Limited",
      meta: [
        {
          name: "description",
          content:
            "Join us on our mission to reimagine the facilities experience and transform the built environment.",
        },
        {
          hid: "fb-share-title",
          property: "og:title",
          content: "stuinnov.com | platform",
        },
        {
          hid: "fb-share-description",
          property: "og:description",
          content: "Join us on our mission to reimagine the facilities",
        },
        {
          hid: "fb-share-image",
          property: "og:image",
          rel: "icon",
          type: "image/png",
          sizes: "16x16",
          href: "/images/logo-s.png",
        },
        {
          hid: "fb-share-url",

          property: "og:url",
          content: "https://stuinnov.com/platform/",
        },
        {
          hid: "twitter-meta",
          name: "twitter:card",
          content: "summary_large_image",
        },
        {
          hid: "twitter-title",
          name: "twitter:title",
          content: "stuinnov.com | platform",
        },
        {
          hid: "twitter-description",
          name: "twitter:description",
          content:
            "Join us on our mission to reimagine the facilities experience and transform the built environment.",
        },
        {
          hid: "twitter-image",
          name: "twitter:image",
          content: "",
        },
        {
          hid: "twitter-url",
          name: "twitter:url",
          content: "hhttps://stuinnov.com/platform/",
        },
      ],
      link: [
        {
          rel: "canonical",
          href: "https://stuinnov.com/platform/",
        },
      ],
      script: [
        { src: "../js/page.js" },
        { src: "../js/waypoints.min.js" },
        { src: "../js/includes.js" },
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.text-color {
  color: #ff50ac;
}
.page-banaer {
  background-color: #f6f9fb;
  padding: 60px 70px;
  margin: 0;
  justify-content: center;
}
.Efficiency-subheading {
  font-size: 18px;
  font-family: "ProximaNovaRgRegular";
  line-height: 1.39;
  text-align: left;
  color: #302930;
}
.Efficiency-heading h4 {
  font-family: "ProximaNovaRgRegular";
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 0.2px;
  text-align: left;
  color: #342d4f;
}
.Efficiency-box {
  width: 30.3%;
  padding-right: 60px;
}
.box-text {
  max-width: 75px;
  background-color: rgba(89, 144, 255, 0.16);
  color: #5990ff;
  border-radius: 4px;
  padding: 5px;
  font-size: 13px;
}

.Efficiency {
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding-bottom: 60px;
  padding-bottom: 0 !important;
  padding-top: 1px;
  padding-left: 101px;
}
.paera {
  width: 100% !important;
  margin: 23px auto;
  font-family: "ProximaNovaLtLight";
  font-size: 18px;
  line-height: 1.61;
  letter-spacing: 0px;
  text-align: center;
  max-width: 500px;
  color: #302930;
  max-width: 700px;
  margin-top: 35px;
}
.work-together-title {
  color: #342d4f;
  font-family: merriweather;
  font-size: 2.5rem;
  line-height: 60px;
  letter-spacing: -1.2px;
  margin: 0;
  text-align: center;
}
html {
  scroll-behavior: smooth;
}

@media only screen and (max-width: 768px) {
  .work-together {
    padding-left: 30px;
    padding-right: 30px;
    margin-left: 0;
    padding-bottom: 0;
  }
  .Efficiency-box {
    width: 100%;
    display: grid;
  }
  .Efficiency {
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    padding-bottom: 60px;
    padding-bottom: 0 !important;
    padding-top: 78px;
    padding-left: 67px;
  }
  .bennar {
    padding-top: 60px;
    padding-bottom: 60px;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }
  .bennar p {
    padding-left: 30px;
    padding-right: 30px;
  }
}
.btn {
  color: rgb(247, 11, 109);
  background-color: #ffffff;
  border-color: #f71b64;
  margin-top: 2px;
  margin-left: 21px;
}

.btn:hover {
  background-color: deeppink;
  color: #fff;
}
.apply-link {
  margin-left: 120px;
}

.job-title {
  margin-right: 0;
  margin-bottom: 40px;
  margin-left: 0;
  color: #151f34;
  font-size: 48px;
  line-height: 60px;
  font-weight: 600;
  text-align: center;
  font-family: "ProximaNovaSemibold";
  padding-top: 90px;
}

.job-wey {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-width: 875px;
  margin-right: auto;
  margin-left: auto;
  padding-bottom: 40px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-top: 60px;
}

.heder-title {
  font-family: "playfair_displayregular";
  text-transform: uppercase;
  font-size: 35px;
  color: #fff;
  font-weight: 700;
  line-height: 1.1;
  margin: 0 0 17px;
  text-align: center;
  letter-spacing: 1.4px;
  line-height: 1.3;
}

.subtitle {
  font-family: ProximaNovaLtLight;
  font-size: 24px;
  max-width: 830px;
  margin-left: auto;
  margin-right: auto;
  font-weight: 400;
  color: #fff;
  line-height: 1.61;
  letter-spacing: 0.6px;
  margin-top: 40px;
}
.work-together-subtitle {
  font-family: playfair_displayregular;
  font-size: 1.2rem;
  line-height: 30px !important;
  color: #575263;
  margin: 10px 0 0;
  text-align: center;
}
.jobs-button {
  font-family: "ProximaNovaLtLight";
  padding: 21px 43px;
  border: none;
  text-decoration: none;
  text-transform: uppercase;
  border-radius: 0;
  position: relative;
  top: 37px;
  background-color: rgb(255, 49, 133);
  font-size: 16px;
  font-weight: 600;
  letter-spacing: 1px;
  text-align: center;
  color: #ffffff;
  box-shadow: 0px 29px 79px 0px rgb(47 46 72 / 10%);
  transition: all 0.15s linear 0s;
}
.box-body {
  max-width: 90%;
  max-height: 150px;
  padding: 20px 20px 20px 20px;
}
.box-title {
  font-size: 18px;
}
.box-text-subtitle {
  margin-top: 7px;
}
@media screen and (max-width: 900px) {
  .box {
    padding-left: 0px;
  }
  .apply-link {
    padding-left: 0px;
  }
  .btn {
    margin-top: -136px;
    margin-left: 61px;
  }
  .job-content {
    margin-left: -10px;
  }
  .box-title {
    font-size: 13px;
  }
}
.Efficiency-subheading {
  font-size: 18px;
  font-family: "ProximaNovaRgRegular";
  line-height: 1.39;
  text-align: left;
  color: #302930;
}
.Efficiency-heading h4 {
  font-family: "ProximaNovaRgRegular";
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 0.2px;
  text-align: left;
  color: #342d4f;
}
.Efficiency-box {
  width: 32.3%;
  padding-right: 63px;
}
.box-text {
  max-width: 75px;
  background-color: rgba(89, 144, 255, 0.16);
  color: #5990ff;
  border-radius: 4px;
  padding: 5px;
  font-size: 13px;
}

.Efficiency {
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding-bottom: 60px;
  padding-bottom: 0 !important;
  padding-top: 45px;
  padding-left: 40px;
}
.paera {
  width: 100% !important;
  margin: 23px auto;
  font-family: "ProximaNovaLtLight";
  font-size: 18px;
  line-height: 1.61;
  letter-spacing: 0px;
  text-align: center;
  max-width: 500px;
  color: #302930;
  max-width: 700px;
  margin-top: 35px;
}
.work-together-title {
  color: #342d4f;
  font-family: merriweather;
  font-size: 2.5rem;
  line-height: 60px;
  letter-spacing: -1.2px;
  margin: 0;
  text-align: center;
}
html {
  scroll-behavior: smooth;
}

@media only screen and (max-width: 768px) {
  .work-together {
    padding-left: 30px;
    padding-right: 30px;
    margin-left: 0;
    padding-bottom: 0;
  }
  .Efficiency-box {
    width: 100%;
    display: grid;
  }
  .Efficiency {
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    padding-bottom: 60px;
    padding-bottom: 0 !important;
    padding-top: 78px;
    padding-left: 67px;
  }
  .bennar {
    padding-top: 60px;
    padding-bottom: 60px;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }
  .bennar p {
    padding-left: 30px;
    padding-right: 30px;
  }
}
.btn {
  color: rgb(247, 11, 109);
  background-color: #ffffff;
  border-color: #f71b64;
  margin-top: 2px;
  margin-left: 21px;
}

.btn:hover {
  background-color: deeppink;
  color: #fff;
}
.apply-link {
  margin-left: 120px;
}

.job-title {
  margin-right: 0;
  margin-bottom: 40px;
  margin-left: 0;
  color: #151f34;
  font-size: 48px;
  line-height: 60px;
  font-weight: 600;
  text-align: center;
  font-family: "ProximaNovaSemibold";
  padding-top: 90px;
}

.job-wey {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-width: 875px;
  margin-right: auto;
  margin-left: auto;
  padding-bottom: 40px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  margin-top: 60px;
}

.heder-title {
  font-family: "playfair_displayregular";
  text-transform: uppercase;
  font-size: 35px;
  color: #fff;
  font-weight: 700;
  line-height: 1.1;
  margin: 0 0 17px;
  text-align: center;
  letter-spacing: 1.4px;
  line-height: 1.3;
}

.subtitle {
  font-family: ProximaNovaLtLight;
  font-size: 24px;
  max-width: 830px;
  margin-left: auto;
  margin-right: auto;
  font-weight: 400;
  color: #fff;
  line-height: 1.61;
  letter-spacing: 0.6px;
  margin-top: 40px;
}
.work-together-subtitle {
  font-family: playfair_displayregular;
  font-size: 1.2rem;
  line-height: 30px !important;
  color: #575263;
  margin: 10px 0 0;
  text-align: center;
}
.jobs-button {
  font-family: "ProximaNovaLtLight";
  padding: 21px 43px;
  border: none;
  text-decoration: none;
  text-transform: uppercase;
  border-radius: 0;
  position: relative;
  top: 37px;
  background-color: rgb(255, 49, 133);
  font-size: 16px;
  font-weight: 600;
  letter-spacing: 1px;
  text-align: center;
  color: #ffffff;
  box-shadow: 0px 29px 79px 0px rgb(47 46 72 / 10%);
  transition: all 0.15s linear 0s;
}
.box-body {
  max-width: 90%;
  max-height: 150px;
  padding: 20px 20px 20px 20px;
}
.box-title {
  font-size: 18px;
}
.box-text-subtitle {
  margin-top: 7px;
}
@media screen and (max-width: 900px) {
  .box {
    padding-left: 0px;
  }
  .apply-link {
    padding-left: 0px;
  }
  .btn {
    margin-top: -136px;
    margin-left: 61px;
  }
  .job-content {
    margin-left: -10px;
  }
  .box-title {
    font-size: 13px;
  }
}
.page-heder-rro {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 90px auto;
}
.page-heder {
  margin-top: 0;
  padding: 200px 10px;
  height: auto;
  position: relative;
  background-size: cover;
  background-repeat: no-repeat;
  background-color: #264653;
}
.page-heder .page-heder-H {
  font-size: 49px;
  font-family: "Merriweather";
  max-width: 1200px;
  line-height: 1;
  margin: 0 auto;
  font-stretch: normal;
  font-weight: 600;
  font-style: normal;
  text-align: center;
  color: rgb(237, 228, 228);
}
.page-heder-description {
  font-size: 29px;
  font-family: "ProximaNovaRgRegular";
  color: rgb(237, 228, 228);
  max-width: 867px;
  margin: 50px auto 0;
  text-align: center;
}
</style>
