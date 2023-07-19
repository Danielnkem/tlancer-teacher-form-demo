<template>
  <div class="div">
    <div class="footer">
      <div class="box" />
      <img class="footer-child" alt="" src="/vector-36.svg" />
      <img class="footer-item" alt="" src="/vector-37.svg" />
      <div class="footer-copyright">
        <div class="social-icons">
          <img class="social-icon" alt="" src="/social-icon.svg" />
          <img class="social-icon" alt="" src="/social-icon1.svg" />
        </div>
        <div class="footer-text">
          Copyright © 2023 Tlancer. All rights reserved.
        </div>
        <img class="logo-icon" alt="" src="/logo.svg" />
      </div>
      <img class="mdiinstagram-icon" alt="" src="/mdiinstagram.svg" />
      <img class="icbaseline-tiktok-icon" alt="" src="/icbaselinetiktok.svg" />
      <img
        class="icbaseline-discord-icon"
        alt=""
        src="/icbaselinediscord.svg"
      />
    </div>
    <img class="vector-icon" alt="" src="/vector.svg" />
    <img class="child" alt="" src="/frame-1127@2x.png" />
    <div class="div1">საბა კიაშვილი</div>
    <div class="rectangle-parent">
      <div class="group-child" />
      <div class="group-item" />
    </div>
    <b class="b">შექმენი კურსი</b>
    <div class="parent">
      <div class="div2">კურსის სილაბუსი</div>
      <div class="frame-child" />
      <div class="div3">ატვირთე ფაილი</div>
      <div class="pdf-word-excel-container">
        <span>ატვირთე მხოლოდ</span>
        <span class="pdf-word-excel"> PDF, Word, Excel, PowerPoint. . .</span>
      </div>
      <img
        class="material-symbolsupload-icon"
        alt=""
        src="/materialsymbolsupload.svg"
      />
    </div>
    <div class="parent">
      <div class="div2">კურსის სილაბუსი</div>
      <div class="frame-child" />
      <div class="div3">ატვირთე ფაილი</div>
      <div class="pdf-word-excel-container">
        <span>ატვირთე მხოლოდ</span>
        <span class="pdf-word-excel"> PDF, Word, Excel, PowerPoint. . .</span>
      </div>
      <img
        class="material-symbolsupload-icon"
        alt=""
        src="/materialsymbolsupload.svg"
      />
    </div>
    <div class="container" @click="onFrameContainer2Click">
      <b class="b1">შემდეგი</b>
      <img class="frame-inner" alt="" src="/vector-5.svg" />
    </div>
    <div class="container" @click="onFrameContainer3Click">
      <b class="b1">შემდეგი</b>
      <img class="frame-inner" alt="" src="/vector-5.svg" />
    </div>
    <div class="parent1">
      <div class="div2">ატვირთე ვიდეო ან დაამატე ერთი საცდელი გაკვეთილი</div>
      <div class="frame-child" />
      <div class="wrapper">
        <div class="div7">ატვირთე ვიდეო</div>
      </div>
      <div class="div8">ატვირთეთ ვიდეო / სურათი ახალი კურსისთვის!</div>
      <img
        class="material-symbolsupload-icon"
        alt=""
        src="/materialsymbolsupload.svg"
      />
    </div>
    <div class="parent1">
      <div class="div2">ატვირთე ვიდეო ან დაამატე ერთი საცდელი გაკვეთილი</div>
      <div class="frame-child" />
      <div class="wrapper">
        <div class="div7">ატვირთე ვიდეო</div>
      </div>
      <div class="div8">ატვირთეთ ვიდეო / სურათი ახალი კურსისთვის!</div>
      <img
        class="material-symbolsupload-icon"
        alt=""
        src="/materialsymbolsupload.svg"
      />
    </div>
    <div class="parent3">
      <div class="div2">ატვირთე სურათი</div>
      <div class="frame-child" />
      <div class="wrapper">
        <div class="div7">ატვირთე სურათი</div>
      </div>
      <div class="div8">ატვირთეთ სურათი ახალი კურსისთვის!</div>
      <img
        class="material-symbolsupload-icon"
        alt=""
        src="/materialsymbolsupload.svg"
      />
    </div>
    <div class="group-parent">
      <div class="group-container" @click="onGroupContainer1Click">
        <img class="group-inner" alt="" src="/group-302.svg" />
        <b class="b3">კურსის დეტალები</b>
        <div class="div15">დაამატე კურსის დეტალები</div>
      </div>
      <div class="group-div" @click="onGroupContainer2Click">
        <img class="group-inner" alt="" src="/group-302.svg" />
        <b class="b4">სილაბუსი</b>
        <div class="div16">დაამატე შენი სილაბუსი</div>
      </div>
      <div class="frame-parent">
        <img class="group-inner" alt="" src="/frame-1309.svg" />
        <b class="b5">კურსის ფასი</b>
        <div class="div17">დაამატე კურსის ფასი</div>
      </div>
      <div class="group-parent1">
        <img class="group-inner" alt="" src="/group-3021.svg" />
        <b class="b6">დასრულება</b>
        <div class="div17">დაამატე კურსის ვიდეო</div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent, ref } from "vue";

  export default defineComponent({
    name: "Component",
    methods: {
      onFrameContainer2Click() {
        // Please sync "კურსის შექმნა 4" to the project
      },
      onFrameContainer3Click() {
        // Please sync "კურსის შექმნა 4" to the project
      },
      onGroupContainer1Click() {
        this.$router.push("/");
      },
      onGroupContainer2Click() {
        this.$router.push("/-2");
      },
    },
  });
</script>
<style scoped>
  .box {
    position: absolute;
    top: -371.02px;
    left: 661.28px;
  }
  .footer-child {
    position: absolute;
    top: 146.22px;
    left: 195.33px;
    width: 1703.95px;
    height: 0px;
  }
  .footer-item {
    position: absolute;
    top: -470.32px;
    left: 195.33px;
    width: 1703.95px;
    height: 0px;
  }
  .social-icon {
    position: relative;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .social-icons {
    position: absolute;
    top: 4.37px;
    left: 1370.58px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 26.19px;
  }
  .footer-text {
    position: absolute;
    top: 9.82px;
    left: 628.55px;
    font-weight: 500;
    display: inline-block;
    width: 401.57px;
  }
  .logo-icon {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 127.67px;
    height: 30.55px;
  }
  .footer-copyright {
    position: absolute;
    top: 189.87px;
    left: 218.25px;
    width: 1449.15px;
    height: 30.55px;
  }
  .mdiinstagram-icon {
    position: absolute;
    top: 194.24px;
    left: 1689.22px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .icbaseline-tiktok-icon {
    position: absolute;
    top: 194.24px;
    left: 1737.24px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .icbaseline-discord-icon {
    position: absolute;
    top: 194.24px;
    left: 1785.25px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .footer {
    position: absolute;
    bottom: -4077px;
    left: -52px;
    width: 2095.16px;
    height: 311px;
    overflow: hidden;
    text-align: left;
    font-size: 17.46px;
    color: #fff;
    font-family: "Work Sans";
  }
  .vector-icon {
    position: absolute;
    height: 0.22%;
    width: 0.31%;
    top: 3.17%;
    right: 3.91%;
    bottom: 96.61%;
    left: 95.78%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .child {
    position: absolute;
    top: 61px;
    left: 214px;
    width: 1504px;
    height: 51px;
    object-fit: cover;
  }
  .div1 {
    position: absolute;
    top: 75px;
    left: 1487px;
    font-weight: 600;
    color: #333;
    text-align: left;
  }
  .group-child {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    left: 0%;
    border-radius: 14.05px;
    background-color: #fff;
  }
  .group-item {
    position: absolute;
    top: 0px;
    left: 0px;
    border-radius: 14.05px 5px 5px 14.05px;
    background-color: #f9fbfc;
    width: 535px;
    height: 1231px;
  }
  .rectangle-parent {
    position: absolute;
    height: 68.5%;
    width: 78.33%;
    top: 13.63%;
    right: 10.83%;
    bottom: 17.86%;
    left: 10.83%;
  }
  .b {
    position: absolute;
    top: 303px;
    left: 280px;
    font-size: 34.25px;
    letter-spacing: -0.01em;
    color: #333;
  }
  .div2 {
    position: absolute;
    top: 0px;
    left: 3px;
    font-size: 23px;
    letter-spacing: -0.01em;
    font-weight: 600;
    color: #333;
  }
  .frame-child {
    position: absolute;
    top: 61px;
    left: 3px;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    box-sizing: border-box;
    width: 768px;
    height: 68px;
  }
  .div3 {
    position: absolute;
    top: 83px;
    left: 37px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .pdf-word-excel {
    color: #7869e6;
  }
  .pdf-word-excel-container {
    position: absolute;
    top: 155px;
    left: 3px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .material-symbolsupload-icon {
    position: absolute;
    top: 83px;
    left: 724px;
    width: 24px;
    height: 24px;
    overflow: hidden;
  }
  .parent {
    position: absolute;
    top: 327px;
    left: 835px;
    width: 771px;
    height: 167px;
  }
  .b1 {
    position: relative;
    letter-spacing: -0.01em;
  }
  .frame-inner {
    position: relative;
    width: 19.03px;
    height: 6.52px;
  }
  .container {
    position: absolute;
    top: 1105px;
    left: 835px;
    border-radius: 6.19px;
    background-color: #8a7cee;
    display: flex;
    flex-direction: row;
    padding: 10.619468688964844px 32.74336242675781px;
    align-items: center;
    justify-content: flex-start;
    gap: 21.24px;
    cursor: pointer;
    font-size: 20.35px;
    color: #fff;
  }
  .div7 {
    position: relative;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .wrapper {
    position: absolute;
    top: 61px;
    left: 3px;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    box-sizing: border-box;
    width: 768px;
    display: flex;
    flex-direction: row;
    padding: 22px 34px;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .div8 {
    position: absolute;
    top: 149px;
    left: 0px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .parent1 {
    position: absolute;
    top: 587px;
    left: 835px;
    width: 771px;
    height: 167px;
  }
  .parent3 {
    position: absolute;
    top: 847px;
    left: 835px;
    width: 771px;
    height: 167px;
  }
  .group-inner {
    position: absolute;
    top: 12.03px;
    left: 0px;
    width: 32.35px;
    height: 32.35px;
  }
  .b3 {
    position: absolute;
    top: 0px;
    left: 73.25px;
    letter-spacing: -0.01em;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    width: 296.26px;
  }
  .div15 {
    position: absolute;
    top: 39px;
    left: 73.25px;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .group-container {
    position: relative;
    width: 369.51px;
    height: 60px;
    opacity: 0.25;
    cursor: pointer;
    color: #1d995d;
  }
  .b4 {
    position: absolute;
    top: 0px;
    left: 73.25px;
    letter-spacing: -0.01em;
  }
  .div16 {
    position: absolute;
    top: 39.48px;
    left: 73.25px;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
    color: rgba(51, 51, 51, 0.32);
  }
  .group-div {
    position: relative;
    width: 276.25px;
    height: 60.48px;
    cursor: pointer;
    color: #333;
  }
  .b5 {
    position: absolute;
    top: 0px;
    left: 73px;
    letter-spacing: -0.01em;
  }
  .div17 {
    position: absolute;
    top: 39.48px;
    left: 73px;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .frame-parent {
    position: relative;
    width: 277px;
    height: 60.48px;
    opacity: 0.25;
  }
  .b6 {
    position: absolute;
    top: 0px;
    left: 70px;
    letter-spacing: -0.01em;
  }
  .group-parent1 {
    position: relative;
    width: 270px;
    height: 60.48px;
    opacity: 0.25;
  }
  .group-parent {
    position: absolute;
    top: 426px;
    left: 286px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 146px;
    font-size: 28.92px;
    color: #110000;
  }
  .div {
    position: relative;
    background-color: #eff2fc;
    width: 100%;
    height: 1797px;
    overflow: hidden;
    text-align: center;
    font-size: 18px;
    color: #aba5a5;
    font-family: "Noto Sans Georgian";
  }
</style>
