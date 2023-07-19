<template>
  <div class="div19">
    <footer class="footer1">
      <div class="box1" />
      <img class="footer-inner" alt="" src="/vector-36.svg" />
      <img class="footer-child1" alt="" src="/vector-37.svg" />
      <div class="footer-copyright1">
        <img class="logo-icon1" alt="" src="/logo.svg" />
        <div class="frame1">
          <div class="footer-text1">
            Copyright © 2023 Tlancer. All rights reserved.
          </div>
          <div class="social-icons1">
            <img class="social-icon2" alt="" src="/social-icon.svg" />
            <img class="social-icon2" alt="" src="/social-icon2.svg" />
          </div>
        </div>
      </div>
      <img class="mdiinstagram-icon1" alt="" src="/mdiinstagram.svg" />
      <img class="icbaseline-tiktok-icon1" alt="" src="/icbaselinetiktok.svg" />
      <img
        class="icbaseline-discord-icon1"
        alt=""
        src="/icbaselinediscord.svg"
      />
    </footer>
    <div class="inner">
      <div class="frame-group">
        <div class="rectangle-wrapper">
          <div class="frame-child4" />
        </div>
        <div class="frame2">
          <div class="button-frame-1251-parent">
            <button class="button-frame-1251" @click="onBUTTONFrame1251Click">
              <b class="b7">შემდეგი</b>
              <img
                class="button-frame-1251-child"
                alt=""
                src="/vector-51.svg"
              />
            </button>
            <div class="frame3">
              <div class="parent4">
                <b class="b8">შექმენი კურსი</b>
                <div class="frame-container">
                  <div class="group-parent2">
                    <img class="frame-child5" alt="" src="/group-3022.svg" />
                    <div class="frame4">
                      <b class="b9">კურსის დეტალები</b>
                      <div class="div20">დაამატე კურსის დეტალები</div>
                    </div>
                  </div>
                  <div class="group-parent3">
                    <img class="frame-child5" alt="" src="/group-3023.svg" />
                    <div class="frame5">
                      <b class="b8">სილაბუსი</b>
                      <div class="div21">დაამატე შენი სილაბუსი</div>
                    </div>
                  </div>
                  <div class="group-parent4">
                    <img class="frame-child5" alt="" src="/group-3024.svg" />
                    <div class="frame6">
                      <b class="b8">კურსის ფასი</b>
                      <div class="div21">დაამატე კურსის ფასი</div>
                    </div>
                  </div>
                  <div class="group-parent5">
                    <img class="frame-child5" alt="" src="/group-3025.svg" />
                    <div class="frame7">
                      <b class="b8">დასრულება</b>
                      <div class="div21">დაამატე კურსის ვიდეო</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="frame8">
                <div class="frame-parent1">
                  <form class="frame-form">
                    <div class="frame9">
                      <div class="div24">კურსის კატეგორიები</div>
                      <div class="div24">მონიშნე კურსი</div>
                    </div>
                    <div class="frame10">
                      <div class="frame11">
                        <button class="frame-button">
                          <div class="div26">კურსის კატეგორია</div>
                        </button>
                        <img class="vector-icon1" alt="" src="/vector1.svg" />
                      </div>
                      <div class="frame12">
                        <div class="div27">მონიშნეთ კურსი</div>
                        <img class="vector-icon2" alt="" src="/vector2.svg" />
                      </div>
                    </div>
                  </form>
                  <div class="frame-parent2">
                    <div class="frame13">
                      <div class="div28">აირჩიეთ კურსის ტიპი</div>
                      <div class="div28">სტუდენტების რაოდენობა</div>
                    </div>
                    <div class="frame10">
                      <button class="frame15">
                        <div class="wrapper2">
                          <input
                            class="input"
                            type="text"
                            maxlength
                            minlength
                            required
                          />
                        </div>
                        <div class="wrapper3">
                          <div class="div26">აირჩიეთ კურსის ტიპი</div>
                        </div>
                      </button>
                      <input
                        class="frame16"
                        type="text"
                        maxlength
                        minlength
                        required
                      />
                    </div>
                  </div>
                  <input
                    class="frame-input"
                    type="text"
                    maxlength
                    minlength
                    required
                  />
                  <div class="parent5">
                    <div class="div31">კლასის ტიპი</div>
                    <input class="frame17" type="text" maxlength minlength />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="frame18">
      <div class="frame19">
        <img class="frame-child9" alt="" src="/frame-1127@2x.png" />
        <div class="div32">საბა კიაშვილი</div>
      </div>
      <img class="vector-icon3" alt="" src="/vector3.svg" />
    </div>
  </div>
</template>
<script>
  import { defineComponent, ref } from "vue";

  export default defineComponent({
    name: "Component1",
    methods: {
      onBUTTONFrame1251Click() {
        this.$router.push("/-2");
      },
    },
  });
</script>
<style scoped>
  .box1 {
    position: absolute;
    top: -371.02px;
    left: 661.28px;
  }
  .footer-inner {
    position: absolute;
    top: 146.22px;
    left: 195.33px;
    width: 1703.95px;
    height: 0px;
  }
  .footer-child1 {
    position: absolute;
    top: -470.32px;
    left: 195.33px;
    width: 1703.95px;
    height: 0px;
  }
  .logo-icon1 {
    position: relative;
    width: 127.67px;
    height: 30.55px;
  }
  .footer-text1 {
    position: relative;
    font-weight: 500;
    display: inline-block;
    width: 401.57px;
    flex-shrink: 0;
  }
  .social-icon2 {
    position: relative;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .social-icons1 {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 26.19px;
  }
  .frame1 {
    width: 820.6px;
    height: 26.19px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 340px;
  }
  .footer-copyright1 {
    position: absolute;
    top: 189.87px;
    left: 218.25px;
    width: 1449.15px;
    height: 30.55px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 500px;
  }
  .mdiinstagram-icon1 {
    position: absolute;
    top: 194.24px;
    left: 1689.22px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .icbaseline-tiktok-icon1 {
    position: absolute;
    top: 194.24px;
    left: 1737.24px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .icbaseline-discord-icon1 {
    position: absolute;
    top: 194.24px;
    left: 1785.25px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .footer1 {
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
  .frame-child4 {
    position: relative;
    border-radius: 14.05px 5px 5px 14.05px;
    background-color: #f9fbfc;
    width: 535px;
    height: 1231px;
  }
  .rectangle-wrapper {
    flex: 1;
    border-radius: 14.05px;
    background-color: #fff;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .b7 {
    position: relative;
    font-size: 20.47px;
    letter-spacing: -0.01em;
    font-family: "Noto Sans Georgian";
    color: #fff;
    text-align: center;
  }
  .button-frame-1251-child {
    position: relative;
    width: 19.14px;
    height: 6.55px;
  }
  .button-frame-1251 {
    cursor: pointer;
    border: none;
    padding: 10.680000305175781px 32.93000030517578px;
    background-color: #8a7cee;
    position: absolute;
    top: 955.82px;
    left: 555px;
    border-radius: 6.23px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 21.36px;
  }
  .button-frame-1251:hover {
    background-color: #5243c0;
  }
  .b8 {
    position: relative;
    letter-spacing: -0.01em;
  }
  .frame-child5 {
    position: relative;
    width: 32.35px;
    height: 32.35px;
  }
  .b9 {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.01em;
  }
  .div20 {
    align-self: stretch;
    position: relative;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
    color: rgba(51, 51, 51, 0.32);
  }
  .frame4 {
    width: 296.26px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-parent2 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    padding: 0px 0px 0.000102996826171875px;
    align-items: center;
    justify-content: space-between;
    color: #333;
  }
  .div21 {
    position: relative;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .frame5 {
    width: 203px;
    height: 60.48px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-parent3 {
    width: 276.25px;
    height: 60.48px;
    display: flex;
    flex-direction: row;
    padding: 0px 0px 0.000087738037109375px;
    box-sizing: border-box;
    align-items: center;
    justify-content: flex-start;
    gap: 40px;
    opacity: 0.25;
  }
  .frame6 {
    width: 204px;
    height: 60.48px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-parent4 {
    width: 277px;
    height: 60.48px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 40px;
    opacity: 0.25;
  }
  .frame7 {
    width: 200px;
    height: 60.48px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-parent5 {
    width: 270px;
    height: 60.48px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 37px;
    color: #b4b5bc;
  }
  .frame-container {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 146px;
    font-size: 28.92px;
    color: #110000;
  }
  .parent4 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 76px;
  }
  .div24 {
    flex: 1;
    position: relative;
    font-size: 22px;
    letter-spacing: -0.01em;
    font-weight: 600;
    font-family: "Noto Sans Georgian";
    color: #333;
    text-align: center;
  }
  .frame9 {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 161px;
  }
  .div26 {
    position: relative;
    font-size: 18px;
    letter-spacing: -0.01em;
    font-weight: 500;
    font-family: "Noto Sans Georgian";
    color: #aba5a5;
    text-align: center;
  }
  .frame-button {
    cursor: pointer;
    border: 1px solid #d7d7d7;
    padding: 0px 34px;
    background-color: transparent;
    flex: 1;
    border-radius: 7px;
    box-sizing: border-box;
    height: 68px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .vector-icon1 {
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    height: 8.73px;
    margin-left: -34px;
  }
  .frame11 {
    flex: 1;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
  }
  .div27 {
    flex: 1;
    position: relative;
    font-size: 18px;
    letter-spacing: -0.01em;
    font-weight: 500;
    font-family: "Noto Sans Georgian";
    color: #aba5a5;
    text-align: center;
  }
  .vector-icon2 {
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    height: 8.73px;
  }
  .frame12 {
    flex: 1;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: 22px 18.630796432495117px;
    align-items: center;
    justify-content: flex-end;
    gap: 125px;
  }
  .frame10 {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 70px;
  }
  .frame-form {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 25px;
  }
  .div28 {
    flex: 1;
    position: relative;
    letter-spacing: -0.01em;
    font-weight: 600;
  }
  .frame13 {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 150px;
  }
  .input {
    border: none;
    font-weight: 500;
    font-family: "Noto Sans Georgian";
    font-size: 18px;
    background-color: transparent;
    position: relative;
    letter-spacing: -0.01em;
    color: #aba5a5;
    text-align: center;
  }
  .wrapper2 {
    align-self: stretch;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    box-sizing: border-box;
    height: 68px;
    display: flex;
    flex-direction: column;
    padding: 0px 34px;
    align-items: flex-start;
    justify-content: center;
  }
  .wrapper3 {
    align-self: stretch;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    box-sizing: border-box;
    height: 68px;
    display: flex;
    flex-direction: column;
    padding: 0px 34px;
    align-items: flex-start;
    justify-content: center;
    margin-top: -68px;
  }
  .frame15 {
    cursor: pointer;
    border: none;
    padding: 0;
    background-color: transparent;
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
  }
  .frame16 {
    border: 1px solid #d7d7d7;
    background-color: transparent;
    flex: 1;
    border-radius: 7px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    padding: 0px 34px;
    align-items: flex-start;
    justify-content: center;
  }
  .frame-parent2 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    padding: 0px 0px 0px 3px;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 22px;
  }
  .frame-input {
    border: 1px solid #d7d7d7;
    background-color: transparent;
    align-self: stretch;
    border-radius: 7px;
    display: flex;
    flex-direction: column;
    padding: 33px 592px 33px 34px;
    align-items: flex-start;
    justify-content: flex-end;
  }
  .div31 {
    position: absolute;
    top: 0px;
    left: 6px;
    letter-spacing: -0.01em;
    font-weight: 600;
  }
  .frame17 {
    border: 1px solid #d7d7d7;
    background-color: transparent;
    position: absolute;
    top: 61px;
    left: 0px;
    border-radius: 7px;
    box-sizing: border-box;
    width: 768px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: 22px 21.630796432495117px;
    align-items: center;
    justify-content: space-between;
  }
  .parent5 {
    align-self: stretch;
    position: relative;
    height: 129px;
    font-size: 23px;
  }
  .frame-parent1 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    gap: 89px;
  }
  .frame8 {
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    font-size: 22px;
  }
  .frame3 {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 1323px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 185px;
  }
  .button-frame-1251-parent {
    align-self: stretch;
    position: relative;
    height: 1005.18px;
  }
  .frame2 {
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    margin-left: -1432px;
  }
  .frame-group {
    width: 1504px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
  }
  .inner {
    position: absolute;
    top: 245px;
    left: 208px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .frame-child9 {
    position: relative;
    width: 1503px;
    height: 51px;
    object-fit: cover;
  }
  .div32 {
    position: relative;
    font-weight: 600;
  }
  .frame19 {
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
  }
  .vector-icon3 {
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    height: 4px;
  }
  .frame18 {
    position: absolute;
    top: 57px;
    left: 214px;
    width: 1631px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: 4px 0px 0px;
    box-sizing: border-box;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 122px;
    text-align: left;
    font-size: 18px;
  }
  .div19 {
    position: relative;
    background-color: #eff2fc;
    width: 100%;
    height: 1797px;
    overflow: hidden;
    text-align: center;
    font-size: 34.25px;
    color: #333;
    font-family: "Noto Sans Georgian";
  }

  @media screen and (max-width: 1200px) {
    .button-frame-1251 {
      flex-direction: column;
    }

    .group-parent2 {
      flex-direction: column;
      gap: 40px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div24 {
      flex: unset;
      align-self: stretch;
    }

    .frame9 {
      flex-direction: column;
      gap: 161px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame11 {
      flex: unset;
      align-self: stretch;
    }

    .frame12 {
      flex: unset;
      align-self: stretch;
    }

    .frame10 {
      flex-direction: column;
      gap: 70px;
      align-items: center;
      justify-content: flex-start;
    }

    .div28 {
      flex: unset;
      align-self: stretch;
    }

    .frame13 {
      flex-direction: column;
      gap: 150px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame15 {
      flex: unset;
      align-self: stretch;
    }

    .frame16 {
      flex: unset;
      align-self: stretch;
    }

    .frame17 {
      flex-direction: column;
      gap: 579px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame19 {
      flex-direction: column;
      gap: -230px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div19 {
      width: 100%;
    }
  }
  @media screen and (max-width: 960px) {
    .button-frame-1251 {
      flex-direction: column;
    }

    .group-parent2 {
      flex-direction: row;
      gap: 40px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame9 {
      flex-direction: row;
      gap: 161px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame10 {
      flex-direction: row;
      gap: 70px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame13 {
      flex-direction: row;
      gap: 150px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame17 {
      flex-direction: row;
      gap: 579px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame19 {
      flex-direction: row;
      gap: -230px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div19 {
      width: 100%;
    }
  }
  @media screen and (max-width: 420px) {
    .button-frame-1251 {
      flex-direction: column;
    }

    .group-parent2 {
      flex-direction: column;
      gap: 40px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div24 {
      flex: unset;
      align-self: stretch;
    }

    .frame9 {
      flex-direction: column;
      gap: 161px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame11 {
      flex: unset;
      align-self: stretch;
    }

    .frame12 {
      flex: unset;
      align-self: stretch;
    }

    .frame10 {
      flex-direction: column;
      gap: 70px;
      align-items: center;
      justify-content: flex-start;
    }

    .div28 {
      flex: unset;
      align-self: stretch;
    }

    .frame13 {
      flex-direction: column;
      gap: 150px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame15 {
      flex: unset;
      align-self: stretch;
    }

    .frame16 {
      flex: unset;
      align-self: stretch;
    }

    .frame17 {
      flex-direction: column;
      gap: 579px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame19 {
      flex-direction: column;
      gap: -230px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div19 {
      width: 100%;
    }
  }
</style>
