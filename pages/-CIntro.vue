<template>
  <section class="pt-16 pb-10">
    <div class="container mx-auto">
      <h2 class="section-title">
        <span class="text-primary text-7xl">W</span>e are thinking about Web
      </h2>
      <div class="c-intro__bg">
        <div class="c-intro__box py-12 pl-10">
          <h3 class="text-primary text-2xl">
            作るだけなく、伝え語り合う会社でありたい
          </h3>
          <p class="leading-9 mt-4">
            株式会社 chatbox は大阪の小さなWeb制作会社です。
            様々なWeb制作の現場で、「Webのこれからを語り合う」をテーマにWebの可能性を追求し続けています。
            Web制作という「作る」業務だけでなく、Webの技術を「伝える」「語り合う」会社として、
            制作現場での技術指導や、イベント・セミナーなどの交流活動にも積極的に取り組んでいます。
            身の回りにありふれたWebだからこそ、そこにしか無い、そこだけのWebの形を。
            現場と、お客様と、ユーザーと、一緒に考えていくのがchatboxのWeb制作のあり方です。
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.c-intro {
  &__bg {
    padding-top: 250px;
    background-image: url(~assets/image/intro/intro__bg.jpg);
    background-size: contain;
    background-repeat: no-repeat;
  }

  &__box {
    padding-right: 10%;
    background: -webkit-gradient(
      linear,
      right top,
      left top,
      from(hsla(0, 0%, 99%, 0)),
      color-stop(10%, hsla(0, 0%, 99%, 0.5)),
      color-stop(20%, hsla(0, 0%, 100%, 0.8)),
      color-stop(25%, hsla(0, 0%, 100%, 0.85)),
      color-stop(61%, hsla(0, 0%, 100%, 0.9)),
      color-stop(80%, #fff)
    );
  }
}
</style>
