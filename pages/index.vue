<template>
  <div class="bg-black text-white text-base font-sans overflow-hidden">
    <header
      class="
        relative
        md:absolute md:left-0 md:right-0
        z-[2]
        py-[14px]
        md:py-[43px] md:pb
        xl:py-[31px]
        bg-black
        md:bg-transparent
      "
    >
      <div class="container flex items-center md:items-start xl:items-center">
        <nuxt-link to="#" class="flex text-[22px] font-bold">
          <img
            src="~/assets/img/logo.svg"
            alt="SWI"
            class="mr-[15px] w-[93px] h-[65px] md:w-[118px] md:h-[83px]"
            width="93"
            height="65"
          />
        </nuxt-link>

        <nuxt-link
          to="#"
          class="
            ml-auto
            py-[11px]
            px-[24px]
            md:py-[12px] md:px-[27px]
            rounded-[260px]
            font-bold
            text-sm
            leading-[20px]
            capitalize
            bg-btn-landing
          "
        >
          enter the app
        </nuxt-link>
      </div>
    </header>

    <main>
      <section
        class="
          relative
          z-[1]
          pt-[60px]
          pb-[225px]
          md:pt-[269px] md:pb-[174px]
          xl:pt-[251px] xl:pb-[192px]
        "
      >
        <div class="container relative">
          <img
            src="~/assets/img/light.svg"
            alt=""
            draggable="false"
            class="
              hidden
              md:block
              absolute
              top-0
              left-[-390px]
              xl:left-[-1050px]
              select-none
            "
          />

          <div class="relative z-[1] max-w-[567px]">
            <h1
              class="
                text-[24px]
                md:text-[44px]
                font-normal
                leading-[29px]
                md:leading-[53px]
              "
            >
              Smart Web IDE
              <span
                class="
                  block
                  mt-[13px]
                  md:mt-[9px]
                  text-[32px]
                  md:text-xl
                  leading-[39px]
                  md:leading-[75px]
                "
              >
                for smart contract development
              </span>
            </h1>
          </div>

          <img
            src="~/assets/img/hero-bg.svg"
            alt=""
            class="
              absolute
              top-[-140px]
              right-[-118px]
              md:top-[-605px] md:right-[-159px]
              xl:top-[-580px] xl:right-[-151px]
              w-[493px]
              h-[493px]
              max-w-none
              md:w-[1063px] md:h-[1061px]
            "
          />
        </div>
      </section>

      <section class="bg-section">
        <div class="container relative z-[1]">
          <img
            src="~/assets/img/light.svg"
            alt=""
            draggable="false"
            class="
              hidden
              xl:block
              absolute
              bottom-[-660px]
              right-[-970px]
              select-none
            "
          />

          <div class="relative">
            <div
              class="
                pt-[32px]
                pb-[72px]
                md:pt-[55px] md:pb-[98px]
                xl:pt-[94px] xl:pb-[102px]
                border-t-[1px] border-b-[1px] border-[#333333]
              "
            >
              <h2 class="mb-[50px] text-lg font-semibold">How it works?</h2>

              <div class="flex flex-col xl:flex-row">
                <div class="xl:max-w-[543px] w-[100%] flex-shrink-0">
                  <p class="mb-[58px] md:mb-[47px] xl:mb-[39px] leading-[32px]">
                    Lorem Ipsum is simply dummy text of the printing and
                    typesetting industry. Lorem Ipsum has been the industry's
                    standard dummy tandard dummy has bee
                  </p>

                  <ul class="flex m-[-8px]">
                    <li class="p-[8px]">
                      <span class="block mb-[8px] font-semibold leading-[22px]">
                        Lorem ipsum
                      </span>
                      <span class="block text-[14px] leading-[17px]">
                        <strong class="font-medium">SWI</strong>
                        lets you build complex programs on Rust.
                      </span>
                    </li>
                    <li class="p-[8px]">
                      <span class="block mb-[8px] font-semibold leading-[22px]">
                        Lorem ipsum dei
                      </span>
                      <span class="block text-[14px] leading-[17px]">
                        It compiles it and allows to download built prpgrams.
                      </span>
                    </li>
                  </ul>
                </div>

                <div class="mt-[58px] md:mt-[50px] xl:mt-0 xl:ml-[155px]">
                  <p class="leading-[32px]">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    Duis aute irure dolor in reprehenderit in voluptate vel esse
                    cillum dolore eu fugiat nulla pariatur. Excepteur sint
                    occaecat cupidatat non proident, sunt in culpa qui officia
                    deserunt mollit anim id est laborum.
                  </p>
                </div>
              </div>
            </div>

            <div
              class="
                flex flex-col
                xl:flex-row xl:items-center
                pt-[47px]
                pb-[64px]
                md:pt-[66px] md:pb-[119px]
                xl:pt-[88px] xl:pb-[125px]
              "
            >
              <div class="flex-shrink-0 max-w-[543px] w-[100%]">
                <img src="~/assets/img/work-img.svg" alt="" />
              </div>

              <div class="mt-[62px] md:mt-[84px] xl:mt-0 xl:ml-[155px]">
                <ul
                  class="
                    md:flex
                    md:flex-wrap
                    md:mx-[-65px]
                    md:my-[-41px]
                    md:max-w-[713px]
                  "
                >
                  <li class="md:px-[65px] md:py-[41px] md:w-[50%]">
                    <span
                      class="
                        block
                        mb-[5px]
                        text-[24px]
                        font-semibold
                        leading-[29px]
                      "
                    >
                      30
                    </span>
                    <span class="block text-sm leading-[19px]">
                      SWI lets you build complex programs on Rust.
                    </span>
                  </li>
                  <li
                    class="
                      mt-[34px]
                      md:mt-0 md:px-[65px] md:py-[41px] md:w-[50%]
                    "
                  >
                    <span
                      class="
                        block
                        mb-[5px]
                        text-[24px]
                        font-semibold
                        leading-[29px]
                      "
                    >
                      54.543
                    </span>
                    <span class="block text-sm leading-[19px]">
                      It compiles it and allows to download built prpgrams
                    </span>
                  </li>
                  <li
                    class="
                      mt-[34px]
                      md:mt-0 md:px-[65px] md:py-[41px] md:w-[50%]
                    "
                  >
                    <span
                      class="
                        block
                        mb-[5px]
                        text-[24px]
                        font-semibold
                        leading-[29px]
                      "
                    >
                      30
                    </span>
                    <span class="block text-sm leading-[19px]">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </span>
                  </li>
                  <li
                    class="
                      mt-[34px]
                      md:mt-0 md:px-[65px] md:py-[41px] md:w-[50%]
                    "
                  >
                    <span
                      class="
                        block
                        mb-[5px]
                        text-[24px]
                        font-semibold
                        leading-[29px]
                      "
                    >
                      54.543
                    </span>
                    <span class="block text-sm leading-[19px]">
                      Duis aute irure
                    </span>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section>
        <div class="container">
          <div
            class="
              relative
              pt-[28px]
              pb-[69px]
              md:pt-[79px] md:pb-[92px]
              xl:pt-[150px] xl:pb-[90px]
              border-t-[1px] border-b-[1px] border-[#333333]
            "
          >
            <div class="relative z-[1] max-w-[677px]">
              <h2 class="mb-[45px] text-lg font-semibold leading-[39px]">
                There’s more to come soon
              </h2>

              <div class="flex flex-col md:flex-row">
                <div>
                  <ul class="my-[-13px]">
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      Testing facility Go/Tust inside
                    </li>
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      One-click contract deployment
                    </li>
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      Multiple program version handling
                    </li>
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      Full filesystem management
                    </li>
                  </ul>
                </div>

                <div class="mt-[26px] md:mt-0 md:ml-[103px]">
                  <ul class="my-[-13px]">
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      Testing facility Go
                    </li>
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      One-click contract
                    </li>
                  </ul>
                </div>
              </div>
            </div>

            <img
              src="~/assets/img/spiral.svg"
              alt=""
              class="
                absolute
                right-[-115px]
                bottom-[-225px]
                md:right-[-238px] md:bottom-[-247px]
                xl:right-[-287px] xl:bottom-[-147px]
                w-[382px]
                h-[463px]
                md:w-[765px] md:h-[928px]
                max-w-none
              "
            />
          </div>
        </div>
      </section>

      <div class="relative">
        <div
          class="
            absolute
            left-0
            top-[40%]
            xl:top-[280px]
            right-0
            bottom-0
            bg-footer
          "
        ></div>
        <div
          class="
            absolute
            left-0
            right-0
            top-0
            bottom-0
            mx-auto
            w-[100%]
            2xl:max-w-[1920px]
          "
        >
          <img
            src="~/assets/img/footer-bg.svg"
            alt=""
            class="
              absolute
              bottom-[-693px]
              left-[-528px]
              md:left-[-1116px] md:bottom-[-1493px]
              xl:left-[-661px] xl:bottom-[-1326px]
              w-[1883px]
              h-[1442px]
              md:w-[3410px] md:h-[2612px]
              max-w-none
            "
          />
          <img
            src="~/assets/img/light.svg"
            alt=""
            draggable="false"
            class="hidden xl:block absolute top-[-74px] left-[-48%] select-none"
          />
        </div>

        <div class="relative">
          <section
            class="
              pt-[55px]
              pb-[55px]
              md:pt-[25px] md:pb-[90px]
              xl:pt-[101px] xl:pb-[120px]
            "
          >
            <div class="container">
              <h2 class="mb-[50px] text-lg font-semibold">Lorem Ipsum</h2>

              <div class="flex flex-col xl:flex-row">
                <div class="xl:max-w-[519px]">
                  <p class="leading-[32px]">
                    Lorem Ipsum is simply dummy text of the printing and
                    typesetting industry. Lorem Ipsum has been the industry's
                    standard dummy. Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit, sed do eiusmod tempor incididunt ut labore
                    et dolore magna aliqua. Ut enim ad minim veniam, quis
                    nostrud exercitation ullamco laboris nisi ut aliquip
                  </p>
                </div>

                <div class="mt-[29px] xl:mt-0 xl:ml-[179px]">
                  <p class="leading-[32px]">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    Duis aute irure dolor in reprehen non proident, sunt in
                    culpa qui officia deserunt mollit anim id est laborum.
                  </p>
                </div>
              </div>
            </div>
          </section>

          <section
            class="
              pt-[55px]
              pb-[80px]
              md:pt-[90px] md:pb-[110px]
              xl:pt-[120px] xl:pb-[145px]
            "
          >
            <div class="container">
              <div class="mx-auto md:max-w-[666px] xl:max-w-[618px]">
                <p
                  class="
                    mb-[16px]
                    text-center text-[#B014CA] text-[23px]
                    leading-[39px]
                    uppercase
                  "
                >
                  Lorem ipsummore
                </p>
                <h2
                  class="text-center text-[32px] font-semibold leading-[39px]"
                >
                  There’s more to come soon for smart contract development
                </h2>
              </div>
            </div>
          </section>

          <footer
            class="
              pt-[80px]
              pb-[47px]
              md:pt-[110px] md:pb-[52px]
              xl:pt-[145px] xl:pb-[93px]
            "
          >
            <div
              class="
                container
                flex flex-col
                items-center
                md:flex-row md:justify-between
              "
            >
              <nav>
                <ul class="flex flex-wrap mx-[-10px] md:mx-[-14px]">
                  <li class="mx-[10px] md:mx-[14px]">
                    <nuxt-link to="#" class="text-sm leading-[19px] underline">
                      Home
                    </nuxt-link>
                  </li>
                  <li class="mx-[10px] md:mx-[14px]">
                    <nuxt-link to="#" class="text-sm leading-[19px] underline">
                      Docs
                    </nuxt-link>
                  </li>
                  <li class="mx-[10px] md:mx-[14px]">
                    <nuxt-link to="#" class="text-sm leading-[19px] underline">
                      App
                    </nuxt-link>
                  </li>
                </ul>
              </nav>

              <ul class="flex mt-[29px] mx-[-4px] md:mt-0">
                <li class="mx-[4px]">
                  <nuxt-link
                    to="#"
                    class="
                      flex
                      justify-center
                      items-center
                      w-[32px]
                      h-[32px]
                      rounded-[50%]
                      bg-[#191919]
                    "
                  >
                    <icon
                      name="twitter"
                      class="fill-[#B014CA] w-[16px] h-[16px]"
                      custom-size
                    />
                  </nuxt-link>
                </li>
                <li class="mx-[4px]">
                  <nuxt-link
                    to="#"
                    class="
                      flex
                      justify-center
                      items-center
                      w-[32px]
                      h-[32px]
                      rounded-[50%]
                      bg-[#191919]
                    "
                  >
                    <icon
                      name="telegram"
                      class="fill-[#B014CA] w-[16px] h-[16px]"
                      custom-size
                    />
                  </nuxt-link>
                </li>
              </ul>
            </div>
          </footer>
        </div>
      </div>
    </main>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
