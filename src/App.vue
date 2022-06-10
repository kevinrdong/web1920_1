<template>
  <div id="app">
    <div class="con">
      <div class="show">
        <span class="Text-Style">流亞科技股份有限公司</span>
        <span class="Text-Style-2">Logic Art Automation Co., Ltd</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="scss">
html {
  height: 100%;
}

body {
  background-image: url(https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/6F573C6F-BE6F-4A87-9474-E0C4CB3EE5A1.png);
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
}

.con {
  background-image: url(https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/7D5AC662-CBFA-48C5-8989-C2437D30BCDF.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: auto;
  height: 950px;
  .show {
    span {
      width: 563.3px;
      height: 34px;
      margin: 15.5px 18.8px 225.3px 32.8px;
      font-family: MicrosoftYaHeiGBpc-EUC-H;
      font-size: 30.1px;
      font-weight: normal;
      font-stretch: normal;
      font-style: normal;
      line-height: 0.81;
      letter-spacing: normal;
      text-align: center;
      color: #333;
    }
  }
}
</style>
