<template>
  <div id="app">
    <div class="con">
      <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/2986A72E-C556-41FF-A567-919D5018D66B.png" alt="" class="produc">
      <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/B4E592C0-11D3-4DF8-BA41-34753CCAF527.png" alt="" class="poster">
      <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/EEA17D56-28AE-47E8-8B8D-50B9C3EF248E.png" alt="" class="screen">
      <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/54A342F4-94F2-4480-9C20-3A2FD68EDF2A.png" alt="" class="back">
      <div class="show">
        <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/B55759EC-13AA-4DA5-9FFD-1B2E8DB2F4CC.png" alt="" class="logo">
        <span class="Text-Style">流亞科技股份有限公司</span>
        <span class="Text-Style-2">Logic Art Automation Co., Ltd</span>
      </div>
      <div class="text">
        <img src="https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/302FB59C-7A13-4A4F-829B-0622C025E4CD.png" alt="" class="web">
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
 position: relative;
 height: 1080px;
}

body {
  background-image: url(https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/6F573C6F-BE6F-4A87-9474-E0C4CB3EE5A1.png);
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-position: center;
  background-size: cover;
  position: relative;
 
  width: 1920px;
  margin-top: 68.2px;
  padding-bottom: 0;
}

.con {
  position: relative;
  background-image: url(https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/7D5AC662-CBFA-48C5-8989-C2437D30BCDF.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: auto;
  height: 950px;
  display: flex;
  .produc {
    width: 357.1px;
    height: 87.6px;
    position: relative;
    left: 38%;
    margin-top: 43%;
    top: 8px;
    cursor: pointer;
  }

  .poster {
    position: relative;
    width: 170.2px;
    height: 170.2px;
    margin-top: 22%;
    right: 59px;
  }

  .back {
    position: relative;
    width: 66.7px;
    height: 66.7px;
    right: 53%;
    top: 20px
  }

  .screen {
    width: 713.7px;
    height: 399.6px;
    margin: 20% 0 0 44px;

  }

  .show {
    position: absolute;
    margin-left: 40%;
    display: flex;
    flex-direction: column;
    top: 75px;
    .Text-Style {
      position: relative;
      font-size: 41.7px;
      margin: 0;
    }
    .Text-Style-2 {
      font-size: 30.1px;
      position: relative;
      right: 15px;
    }

    .logo {
      position: absolute;
      left: -123px;
      top: -28px;
      width: 124.9px;
      height: 81.9px;
    }

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
  background-size: cover;
  align-items:center;
  right: 290px;
  top: 391px;
  background-image: url(https://cdn.zeplin.io/5f6c76fac15e3f84d938b754/assets/204093F3-6EC9-463C-8B98-C28DE8BD737C.png);
  height: 374px;
  width: 278px;
  box-sizing: border-box;

  .web {
    width: 52.6px;
    height: 52.6px;
    position: absolute;
    margin-left: 60%;
  }

  .row {
    position: relative;
    display:flex;
    flex-direction: column;
    box-sizing: border-box;
    width: 260px;
    height: 30px;
    padding: 20px;
    box-sizing: border-box;
    margin: 10px;
    justify-content: space-between;
    top: 40px;
    font-size: 14px;
  }

  .email {
    margin-top: 0px;

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
  position: relative;
  width: 57.4px;
  height: 21.1px;
  margin:0;
  object-fit: contain;
  }

}

}
</style>
