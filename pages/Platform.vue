<template>
  <div class="productPage btn-shade">
    <div class="myPage" id="menu">
      <Navbar />
    </div>
    <div class="service-banner">
      <div class="service-banner-h">
        <h1 style="font-size: 76px; margin-block: auto">Platform</h1>
        <p style="font-size: 23px">
          We deliver extremely responsive cross-platform apps that improve user
          engagement and enhance the user experience across platforms
        </p>
      </div>
      <img class="img-platform" src="/images/Platform-1.png" />
    </div>
    <section class="platform-update" style="padding-bottom: 70px">
      <div class="st-container">
        <div class="row" style="margin-right: 0px; margin-left: 0px">
          <div class="col-md-4 col-sm-6" style="padding: 42px">
            <a href="#">
              <div class="platform-update-card">
                <div
                  class="platform-card-placeholder"
                  style="background-color: #A4C3B2"
                >
                  <div class="platform-image-inner">
                    <img
                      src="/images/Platform-image-1.jpeg" 
                      class="pt-upd-img"
                      style="height: 198px"
                    />
                  </div>
                </div>
                <div class="platform-desc-set">
                  <div class="month-float">version-2020</div>
                  <h1>Pawn shop</h1>
                  <h3>a store that lends money in exchange for a valuable thing that they can sell if the person leaving it does</h3>
                </div>
                <div class="read-more">read-more</div>
              </div>
            </a>
          </div>
          <div class="col-md-4 col-sm-6" style="padding: 42px">
            <a href="#">
              <div class="platform-update-card">
                <div
                  class="platform-card-placeholder"
                  style="background-color: #BDE0FE"
                >
                  <div class="platform-image-inner">
                    <img
                      src="/images/Platform-image-2.jpeg"
                      class="pt-upd-img"
                      style="height: 198px"
                    />
                  </div>
                </div>
                <div class="platform-desc-set">
                  <div class="month-float">version-2021</div>
                  <h1>STU D Point</h1>
                  <h3>d POINT is a point program that allows you to earn and use d POINTs in a variety of stores like fast-food restaurants x</h3>
                </div>
                <div class="read-more">read-more</div>
              </div>
            </a>
          </div>
          <div class="col-md-4 col-sm-6" style="padding: 42px">
            <a href="#">
              <div class="platform-update-card">
                <div
                  class="platform-card-placeholder"
                  style="background-color: #F7EDE2"
                >
                  <div class="platform-image-inner">
                    <img
                      src="/images/Platform-image-3.jpeg"
                      class="pt-upd-img"
                      style="height: 198px"
                    />
                  </div>
                </div>
                <div class="platform-desc-set">
                  <div class="month-float">version-2020</div>
                  <h1>STU mob ERP</h1>
                  <h3> ERP solution designed for mobile devices such as iOS and Android tablets or smartphones.</h3>
                </div>
                <div class="read-more">read-more</div>
              </div>
            </a>
          </div>
          <div class="col-md-4 col-sm-6" style="padding: 42px">
            <a href="#">
              <div class="platform-update-card">
                <div
                  class="platform-card-placeholder"
                  style="background-color: #FCA311"
                >
                  <div class="platform-image-inner">
                    <img
                      src="/images/Platform-image-4.jpeg"
                      class="pt-upd-img"
                      style="height: 198px"
                    />
                  </div>
                </div>
                <div class="platform-desc-set">
                  <div class="month-float">version-2020</div>
                  <h2>STU Jewellery ERP</h2>
                  <h3>multi-module application software that helps retailers who need an efficient solution to automate Jewellery retailing.</h3>
                </div>
                <div class="read-more">read-more</div>
              </div>
            </a>
          </div>
          <div class="col-md-4 col-sm-6" style="padding: 42px">
            <a href="#">
              <div class="platform-update-card">
                <div
                  class="platform-card-placeholder"
                  style="background-color:#E09F3E"
                >
                  <div class="platform-image-inner">
                    <img
                      src="/images/whatsnew/img_11.png"
                      class="pt-upd-img"
                      style="height: 198px"
                    />
                  </div>
                </div>
                <div class="platform-desc-set">
                  <div class="month-float"></div>
                  <h3></h3>
                </div>
                <div class="read-more">read-more</div>
              </div>
            </a>
          </div>
          <div class="col-md-4 col-sm-6" style="padding: 42px">
            <a href="#">
              <div class="platform-update-card">
                <div
                  class="platform-card-placeholder"
                  style="background-color: #DAD7CD"
                >
                  <div class="platform-image-inner">
                    <img
                      src="/images/whatsnew/img_11.png"
                      class="pt-upd-img"
                      style="height: 198px"
                    />
                  </div>
                </div>
                <div class="platform-desc-set">
                  <div class="month-float"></div>
                  <h3></h3>
                </div>
                <div class="read-more">read-more</div>
              </div>
            </a>
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
      title: "Platform|STU Innovations Private Limited",
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
.service-banner {
  height: 650px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: center;
  align-items: center;
  background-color: #2a9d8f;
  border: 0.8px sienna;
}
.read-more:after {
  content: "";
  display: inline-block;
  width: 15px;
  height: 15px;
  position: absolute;
  margin-top: 1px;
  margin-left: 7px;
  opacity: 1;
  transition: 0.3s ease;
  background: url(/images/light-violet.svg) 50% / contain no-repeat;
}
.read-more {
  position: absolute;
  bottom: 50px;
  right: 115px;
  color: #5969e4;
  text-transform: uppercase;
  font-size: 14px;
  font-family: "ProximaNovaSemiBold";
}
.platform-desc-set h3 {
  max-width: 300px;
  width: 100%;
  font-family: ProximaNovaBold;
  text-align: left;
  font-size: 20px;
  margin-top: 10px;
  line-height: 28px;
  color: #181b3b;
}
.platform-desc-set {
  padding: 25px;
  position: relative;
}
.month-float {
  text-transform: uppercase;
  font-size: 13px;
  font-family: "ProximaNovaSemiBold";
  color: #898ab2;
}
.fc-platform-desc-set h3 {
  max-width: 300px;
  width: 100%;
  font-family: ProximaNovaBold;
  text-align: left;
  font-size: 20px;
  margin-top: 10px;
  line-height: 28px;
  color: #181b3b;
}
.pt-upd-img {
  width: 100%;
  max-width: 270px;
  -o-object-fit: contain;
  object-fit: contain;
  position: relative;
  top: 10px;
}
.platform-card-placeholder {
  height: 220px;
  border-top-left-radius: 14px;
  border-top-right-radius: 14px;
  position: relative;
}
.platform-image-inner {
  height: 100%;
  max-width: 310px;
  margin: 0 auto;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
}
.platform-update-card {
  margin: 50px 10px 0;
  height: 500px;
  width: 320px;
  border-radius: 15px;
  border: 1px solid #e0e2ec;
  background-color: #fff;
}
.platform-update {
  padding: 40px 0 150px;
}
.platform-update-card {
  margin: 50px 10px 0;
  height: 465px;
  border-radius: 15px;
  border: 1px solid #e0e2ec;
  background-color: #fff;
}

@media screen and (max-width: 500px) {
  .platform-update-card {
    margin: -14px !important;
    height: 489px;
  }

  .st-container {
    max-width: 1250px;
    width: 100%;
    margin: 0 auto;
  }
  .read-more {
    position: absolute;
    bottom: 46px;
    right: 79px;
    color: #5969e4;
    text-transform: uppercase;
    font-size: 14px;
    font-family: ProximaNovaSemiBold;
  }
  .service-banner-h {
    width: 372px;
    color: rgb(0, 0, 0);
    font-family: "Merriweather";
    font-weight: 500;
    text-align: center;
}
  .service-banner-h {
    width: 389px;
    color: rgb(255, 255, 255);
    font-family: "Merriweather";
    font-weight: 500;
    text-align: center;
  }
  .img-platform {
    width: auto;
  }
}
.service-banner-h {
  float: left;
  width: 578px;
  color: #ffffff;
  font-family: "Merriweather";
  font-weight: 500;
}
@media only screen and (max-width: 480px) {
  .service-banner {
    height: 300px;
    background-color: #2a9d8f;
    border: none;
    display: block;
  }
  .service-banner-h {
    width: 389px;
    color: rgb(255, 255, 255);
    font-family: "Merriweather";
    font-weight: 500;
    text-align: center;
  }
  .img-platform {
    display: none;
  }
}
</style>
