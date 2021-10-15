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
          to="https://app.swi.systems"
          target="_blank"
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
              Solana Web IDE
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
                    SWI deploys distinct file system for each user session. User
                    can edit files and interact with
                  </p>
                </div>

                <div class="mt-[58px] md:mt-[50px] xl:mt-0 xl:ml-[155px]">
                  <p class="leading-[32px]">
                    SWI is a browser-based integrated development environment
                    for the Solana blockchain that allows the development and
                    deployment of smart contracts.
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
                      Immutability
                    </span>
                    <span class="block text-sm leading-[19px]">
                      A filesystem with immutable structure.
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
                      Validation
                    </span>
                    <span class="block text-sm leading-[19px]">
                      Error highlighting.
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
                      Template
                    </span>
                    <span class="block text-sm leading-[19px]">
                      Initial template based on solana-helloworld.
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
                      Dependencies
                    </span>
                    <span class="block text-sm leading-[19px]">
                      Lets you include dependencies from crates.io
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
                      Testing facility Go/Rust inside
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
                      Anchor integration
                    </li>
                    <li class="flex items-center py-[13px] leading-[39px]">
                      <img
                        src="~/assets/img/icons/arrow.svg"
                        alt=""
                        class="flex-shrink-0 mr-[23px]"
                      />
                      Optimized user session handling
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
              <h2 class="mb-[50px] text-lg font-semibold">Challenges we've run into</h2>

              <div class="flex flex-col xl:flex-row">
                <div class="xl:max-w-[519px]">
                  <p class="leading-[32px]">
                    Solana blockchain capabilities can fulfill the aims of any
                    dApp. But the main obstacle on the way for any new
                    developer, joining the Solana ecosystem, is the complexity
                    of development and deployment.
                    <br />
                    <br />
                    That was the first problem we faced, which incentivized us
                    to create SWI. At this moment, there are no existing IDEs
                    for Solana, so SWI is a pioneer in this space.
                  </p>
                </div>

                <div class="mt-[29px] xl:mt-0 xl:ml-[179px]">
                  <p class="leading-[32px]">
                    Our personal development experience shows how important it
                    is to have handy tools for deploying solutions fast in order
                    to remain competitive in the crypto market.
                    <br />
                    <br />
                    We believe that Solana, arguably the best technological
                    solution in the space, should also lead in adopting the best
                    practices of development.
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
                  Stay tuned
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
                    <a href="#" class="text-sm leading-[19px] underline">
                      Home
                    </a>
                  </li>
                  <!-- <li class="mx-[10px] md:mx-[14px]">
                    <nuxt-link to="#" class="text-sm leading-[19px] underline">
                      Docs
                    </nuxt-link>
                  </li> -->
                  <li class="mx-[10px] md:mx-[14px]">
                    <a
                      href="https://github.com/S-W-I"
                      target="_blank"
                      class="text-sm leading-[19px] underline"
                    >
                      Source Code
                    </a>
                  </li>
                  <li class="mx-[10px] md:mx-[14px]">
                    <a
                      href="https://www.dropbox.com/s/i7pd4voamislyup/Solana%20Web%20IDE_2%402x.png"
                      target="_blank"
                      class="text-sm leading-[19px] underline"
                    >
                      Roadmap
                    </a>
                  </li>
                  <li class="mx-[10px] md:mx-[14px]">
                    <a
                      href="https://app.swi.systems"
                      target="_blank"
                      class="text-sm leading-[19px] underline"
                    >
                      App
                    </a>
                  </li>
                </ul>
              </nav>

              <ul class="flex mt-[29px] mx-[-4px] md:mt-0">
                <li class="mx-[4px]">
                  <a
                    target="_blank"
                    href="https://twitter.com/SolanaWebIDE"
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
                  </a>
                </li>
                <li class="mx-[4px]">
                  <a
                    href="https://t.me/solanaide"
                    target="_blank"
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
                  </a>
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
