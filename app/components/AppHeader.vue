<template>
  <div class="headerWrapper">
    <div class="subcontent">promo value here (insert carosel here)</div>
    <div class="headerMain">
      <NuxtImg class="logoWebsite" src="/logo.svg" alt="logo" />
    </div>
  </div>
</template>

<style scoped lang="scss">
.headerWrapper {
  margin-bottom: 50px;
  width: 100dvw;

  .subcontent {
    text-align: center;
    background-color: var(--color-accent);
  }

  .headerMain {
    margin: 10px var(--page-gutter);
    .logoWebsite {
      height: 20px;
      width: auto;
      margin-left: 10px;
    }
  }
}
</style>
