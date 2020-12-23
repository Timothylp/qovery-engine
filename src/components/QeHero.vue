<template>
  <section class="qe-hero">
    <div class="container">
      <div class="qe-hero__logo">
        <img src="../assets/img/Logotype.svg" alt="logo" />
      </div>
      <div class="qe-hero__content">
        <div class="qe-hero__text">
          <h1>Qovery Engine <span>gitlab stars</span></h1>
          <p class="qe-hero__headline">
            Abstraction layer to deploy microservices applications on any Cloud
            provider.
          </p>
          <p class="qe-hero__summary">
            Qovery Engine is an open-source abstraction layer product that turns
            easy apps deployment on AWS, GCP, Azure and others Cloud providers.
          </p>
          <div class="qe-hero__ctas">
            <a href="" class="qe-btn qe-btn--dark">See on GitHub</a>
            <a href="" class="qe-btn qe-btn--primary">Join us on Discord</a>
          </div>
        </div>
        <div class="qe-hero__images">
          <img src="../assets/img/hero-illustrations.svg" alt="Illustrations" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "QeHero",
  components: {},
};
</script>

<style lang="scss" scoped>
.qe-hero {
  background: #151b2b;
  color: white;
  padding-top: 41px;
  height: 80vh;
}

.qe-hero__logo {
  width: 158px;
}

.qe-hero__content {
  display: flex;
  justify-content: center;
  align-items: center;
}

.qe-hero__text {
  h1 {
    font-family: hk_grotesk;
    font-size: 46px;
    font-weight: 800;
    line-height: 110px;
    margin-bottom: 24px;
  }

  .qe-hero__headline {
    font-family: hk_grotesk;
    font-weight: 600;
    font-size: 25px;
    line-height: 140%;
    margin-bottom: 24px;
  }

  .qe-hero__summary {
    font-size: 16px;
    line-height: 150%;
    color: #8686B3;
    margin-bottom: 48px;
  }
}

.qe-hero__ctas {
    display: flex;
    gap: 24px;
}
</style>