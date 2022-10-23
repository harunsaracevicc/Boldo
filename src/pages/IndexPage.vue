<template>
  <q-header class="bg-primary text-white flex justify-center q-pb-md">
    <div class="container q-pt-md q-mb-md">
      <div class="navigation flex justify-between items-center">
        <div class="logo flex items-center">
          <img src="./../../public/images/logo/boldo-logo.png" alt="" />
          <span class="q-ml-sm">Boldo</span>
        </div>

        <div class="navigation-menu flex items-center">
          <q-list class="flex q-ml-md q-mr-md">
            <q-item clickable>
              <q-item-section>Product</q-item-section>
            </q-item>

            <q-item clickable>
              <q-item-section>Services</q-item-section>
            </q-item>

            <q-item clickable>
              <q-item-section>About </q-item-section>
            </q-item>
          </q-list>

          <q-btn
            dense
            flat
            rounded
            no-caps
            class="nav-btn bg-white text-primary q-pr-xl q-pl-xl"
            size="md"
          >
            Log in
          </q-btn>
        </div>
      </div>
    </div>
  </q-header>

  <section class="hero-section">
    <q-header class="bg-primary text-white flex justify-center q-pb-md">
      <div class="container q-pt-md q-mb-md">
        <div class="navigation flex justify-between items-center">
          <div class="logo flex items-center">
            <img src="./../../public/images/logo/boldo-logo.png" alt="" />
            <span class="q-ml-sm">Boldo</span>
          </div>

          <div class="navigation-menu flex items-center">
            <q-list class="flex q-ml-md q-mr-md">
              <q-item clickable>
                <q-item-section>Product</q-item-section>
              </q-item>

              <q-item clickable>
                <q-item-section>Services </q-item-section>
              </q-item>

              <q-item clickable>
                <q-item-section>About </q-item-section>
              </q-item>
            </q-list>

            <q-btn
              dense
              flat
              rounded
              no-caps
              class="nav-btn bg-white text-primary q-pr-xl q-pl-xl"
              size="md"
            >
              Log in
            </q-btn>
          </div>
        </div>
      </div>
    </q-header>

    <q-page-container>
      <div class="container flex row justify-between items-center" gap="93px">
        <div class="left">
          <div class="left-text">
            <p class="primary-text text-white">
              Save time by building <br />
              fast with Boldo Template
            </p>
            <p class="secondary-text">
              Funding handshake buyer business-to-business metrics iPad
              partnership. <br />
              First mover advantage innovator success deployment non-disclosure.
            </p>
          </div>
          <div class="left-buttons q-mt-xl">
            <q-btn
              dense
              text-color="primary"
              align="center"
              rounded
              no-caps
              color="secondary"
              label="Buy template"
              class="q-pl-xl q-pr-xl q-pt-md q-pb-md"
            />

            <q-btn
              dense
              align="center"
              outline
              rounded
              no-caps
              color="white"
              label="Explore"
              class="q-ml-lg q-pl-xl q-pr-xl q-pt-md q-pb-md"
            />
          </div>
        </div>
        <div class="right">
          <q-img
            src="./../../public/images/logo/hero-graphics.png"
            alt=""
            width="480px"
          />
        </div>
      </div>

      <div
        class="sponsors container flex q-mt-xl q-pt-xl q-pb-xl justify-center items-center no-wrap"
        width="100%"
      >
        <img src="./../../public/images/logo/Logo.png" href="" />
        <img src="./../../public/images/logo/Presto-logo.png" />
        <img src="./../../public/images/logo/Logo.png" href="" />
        <img src="./../../public/images/logo/Presto-logo.png" />
        <img src="./../../public/images/logo/Logo.png" href="" />
        <img src="./../../public/images/logo/Presto-logo.png" />
      </div>
    </q-page-container>
  </section>

  <section class="main-section q-pa-xl">
    <q-page-container>
      <div class="container">
        <div class="heading-text">
          <div class="flex column justify-center text-center">
            <p class="text-subtitle2 text-weight-light">Our Services</p>
            <p class="text-h3 text-weight-light">
              Handshake infographic mass market <br />
              crowdfunding iteration.
            </p>
          </div>
        </div>
        <div class="feature-cards flex justify-between q-pt-xl q-ma-xl">
          <q-card flat class="my-card">
            <img src="./../../public/images/card-image1.png" />

            <q-card-section>
              <div class="text-h6">Our Changing Planet</div>
            </q-card-section>

            <q-card-section class="q-pt-none text-weight-light">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi
              dignissimos qui fugiat.
            </q-card-section>

            <q-card-section>
              <q-btn text-primary no-caps flat dense size="lg" href="/">
                Explore page ->
              </q-btn>
            </q-card-section>
          </q-card>

          <q-card flat class="my-card">
            <img src="./../../public/images/card-image2.png" />

            <q-card-section>
              <div class="text-h6">Our Changing Planet</div>
            </q-card-section>

            <q-card-section class="q-pt-none text-weight-light">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi
              dignissimos qui fugiat.
            </q-card-section>
            <q-card-section>
              <q-btn text-primary no-caps flat dense size="lg" href="/">
                Explore page ->
              </q-btn>
            </q-card-section>
          </q-card>
          <q-card flat class="my-card">
            <img src="./../../public/images/card-image3.png" />

            <q-card-section>
              <div class="text-h6">Our Changing Planet</div>
            </q-card-section>

            <q-card-section class="q-pt-none text-weight-light">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi
              dignissimos qui fugiat.
            </q-card-section>
            <q-card-section>
              <q-btn text-primary no-caps flat dense size="lg" href="/">
                Explore page ->
              </q-btn>
            </q-card-section>
          </q-card>
        </div>
      </div>
    </q-page-container>
  </section>

  <section class="connect-section q-pa-xl">
    <q-page-container>
      <div class="container flex column q-pa-xl">
        <div class="first flex no-wrap items-center" style="gap: 150px">
          <img src="./../../public/images/connect1.png" alt="" />

          <div class="text flex">
            <p class="text-h4 text-weight-light q-pb-lg">
              We connect our customers with the best, and help them keep up-and
              stay open.
            </p>
            <div
              class="text-h6 text-weight-light text-items flex column"
              style="gap: 15px"
            >
              <div class="flex items-center" style="gap: 20px">
                <svg
                  width="32"
                  height="32"
                  viewBox="0 0 36 36"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <circle cx="18" cy="18" r="18" fill="#0A2640" />
                  <path
                    d="M26 12L15 23L10 18"
                    stroke="white"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
                <span>We connect our customers with the best.</span>
              </div>
              <div class="flex items-center" style="gap: 20px">
                <svg
                  width="32"
                  height="32"
                  viewBox="0 0 36 36"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <circle cx="18" cy="18" r="18" fill="#0A2640" />
                  <path
                    d="M26 12L15 23L10 18"
                    stroke="white"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
                <span>Advisor success customer launch party.</span>
              </div>
              <div class="flex items-center q-pb-xl" style="gap: 20px">
                <svg
                  width="32"
                  height="32"
                  viewBox="0 0 36 36"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <circle cx="18" cy="18" r="18" fill="#0A2640" />
                  <path
                    d="M26 12L15 23L10 18"
                    stroke="white"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
                <span>Business-to-consumer long tail.</span>
              </div>
            </div>

            <q-btn
              dense
              flat
              no-caps
              rounded
              class="cta-btn bg-primary text-white q-pa-md q-pl-xl q-pr-xl"
              size="md"
              label="Start now"
            >
            </q-btn>
          </div>
        </div>
        <div class="second"></div>
      </div>
    </q-page-container>
  </section>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",

  setup() {},
});
</script>

<style lang="scss">
.cta-btn {
  width: 160px !important;
}
.q-page {
  height: 100vh !important;
}
.q-card__section span.q-btn__content {
  color: $primary;
}
.my-card {
  max-width: 300px;
  border-radius: 20px;
}

.container {
  margin-left: auto;
  margin-right: auto;
  position: relative;
  width: 100%;
  max-width: 1200px !important;
}
.navigation {
  max-height: 42px !important;
  z-index: 1;
}

.logo {
  span {
    font-size: 43px;
    font-weight: 500;
    align-items: center;
  }
}

.nav-btn {
  height: 40px !important;
}
.q-header {
  z-index: 9999 !important;
}

// .q-header::after {
//   content: "";
//   border-radius: 50%;
//   position: absolute;
//   width: 1293px;
//   height: 1293px;
//   left: 862px;
//   top: -789px;
//   background: #1c3d5b49;
// }

.hero-section .q-page-container {
  background: $primary;
}

.left {
  max-width: 567px;
}
.right {
  max-width: 500px;
}
.primary-text {
  font-style: normal;
  font-weight: 300;
  font-size: 48px;
  line-height: 72px;
}
.secondary-text {
  font-weight: 300;
  font-size: 16px;
  line-height: 28px;
  color: #f1f1f1;
}
.sponsors {
  gap: 60px;
  overflow: hidden;
}

.sponsors {
  -webkit-mask-image: linear-gradient(
    to right,
    transparent 0%,
    black 50%,
    transparent 100%
  );

  mask-image: linear-gradient(
    to center,
    transparent 0%,
    black 50%,
    transparent 100%
  );
}
p.text-h3 {
  line-height: 4.5rem;
}
</style>
