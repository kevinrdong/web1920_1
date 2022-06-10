<template>
  <div id="app">
    <div class="con">
      <div class="show">
        <span class="Text-Style">流亞科技股份有限公司</span>
        <span class="Text-Style-2">Logic Art Automation Co., Ltd</span>
      </div>
      <div class="text">
        <div class="email row">
          <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/DE82AA11-DC14-43F8-8653-DEB546146EA1.png" alt="" class="smp">
          joseph.lo@logicart.com.tw
        </div>
        <div class="tel row">
          <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/4B5E0CF4-5673-4564-95BE-AD47CD982F4E.png" alt=""  class="smp">
          +886-2-2999-2899

        </div>
        <div class="fax row">
          <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/9CBE64FF-19F7-4AA4-A241-E940245DA7CE.png" alt="" class="smp">
          +886-2-2999-2893
        </div>
        <div class="add row">
          <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/61003AA2-3127-4B04-979C-54252E6B5694.png" alt="" class="smp">
          8F-7, No.16, Lane 609, Sec.5, Chung-Shin Road, San-Chung Dist., New Taipei City, Taiwan
        </div>
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
.text {
  position: absolute;
  display:flex;
  flex-direction: column;
  justify-content:center; 
  align-items:center;
  right: 103px;
  top: 391px;
  background-image: url(https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/204093F3-6EC9-463C-8B98-C28DE8BD737C.png);
  height: 374px;
  width: 274px;

  .row {
    width: 260px;
    height: 30px;
  }

  .bord {
    position: relative;
    width: 273.1px;
    height: 353.8px;
    margin: 239.6px 0 78px 67.9px;
    padding: 77.8px 22.3px 39.8px 35.8px;
    object-fit: contain;
    
  }


  .smp {
  width: 57.4px;
  height: 21.1px;
  margin: 31.4px 104.2px 29.8px 0;
  object-fit: contain;
  }

}

}
</style>
