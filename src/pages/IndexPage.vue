<template>
  <q-header class="bg-primary text-white flex justify-center">
    <div class="container q-pt-lg q-mb-lg">
      <div class="navigation q-pb-xl flex justify-between items-center">
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
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>

<style lang="scss">
.container {
  margin-left: auto;
  margin-right: auto;
  position: relative;
  width: 100%;
  max-width: 12git 00px !important;
}
.navigation {
  max-height: 42px !important;
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

header::after {
  z-index: -1;
  content: "";
  border-radius: 50%;
  position: absolute;
  width: 1293px;
  height: 1293px;
  left: 914px;
  top: -789px;
  background: #1c3d5b;
}

.q-page-container {
  background: $primary;
}

.left {
  max-width: 567px;
}
.right {
  max-width: 500px;
  z-index: 2001;
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
</style>
