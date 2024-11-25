<template>
  <div
    class="flex flex-col items-center gap-8 lg:gap-10 pb-[64px] lg:pb-[96px] w-full text-center"
  >
    <div
      class="flex flex-col gap-4 lg:gap-6 transition-all duration-300 hover:transform hover:scale-102"
    >
      <div class="flex flex-col gap-3">
        <p
          class="text-[#7F56D9] font-semibold hover:text-[#6941C6] transition-colors duration-200"
        >
          Nigerian Politics Today
        </p>
        <h1
          class="text-[36px] leading-[44px] lg:text-[48px] font-semibold text-[#101828] hover:text-[#000] transition-colors duration-200"
        >
          Latest Political Updates
        </h1>
      </div>
      <p
        class="text-[#667085] text-[18px] lg:text-xl w-full lg:w-[768px] text-center transition-colors duration-200 hover:text-[#4B5563]"
      >
        Subscribe to get the latest updates on Nigerian politics, government
        policies, and electoral news.
      </p>
    </div>
    <div
      class="flex flex-col w-full lg:flex-row items-start gap-4 justify-center"
    >
      <div class="text-start w-full lg:w-[360px] flex flex-col gap-2">
        <input
          class="border w-full border-[#D0D5DD] py-3 pl-4 pr-[14px] rounded-lg transition-all duration-200 focus:ring-2 focus:ring-[#7F56D9] focus:border-transparent hover:border-[#7F56D9]"
          type="text"
          @input="emailInputValue"
          v-model="email"
          placeholder="Enter your email"
        />
        <p
          class="text-sm text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
        >
          We care about your data in our
          <a
            class="underline leading-5 hover:text-[#7F56D9] transition-colors duration-200"
            href="/"
            >privacy policy</a
          >
        </p>
      </div>
      <button
        class="py-3 px-5 lg:w-[118px] bg-[#7F56D9] rounded-lg border border-[#7F56D9] btn-shadow w-full transition-all duration-200 hover:bg-[#6941C6] active:transform active:scale-95"
      >
        Subscribe
      </button>
    </div>
  </div>

  <!-- Featured Posts Section -->
  <div class="pb-[64px] lg:pb-[96px]">
    <div class="flex flex-col gap-8 xl:px-[32px]">
      <h2
        class="font-semibold text-[24px] text-[#101828] transition-colors duration-200 hover:text-[#000]"
      >
        Featured Stories
      </h2>
      <div class="flex flex-col xl:flex-row gap-12 justify-between">
        <!-- Main Featured Post -->
        <div
          class="flex flex-col gap-8 xl:w-[48%] transition-all duration-300 hover:transform hover:scale-102"
        >
          <img
            class="w-full h-[200px] md:h-[228px] object-cover rounded-lg transition-transform duration-300 hover:transform hover:scale-105"
            src="../assets/presentation.png"
            alt="Presidential Address"
          />
          <div class="flex flex-col gap-6">
            <div class="flex flex-col gap-3">
              <small class="font-semibold text-[#6941C6]"
                >Oluwaseun Adeleke • 20 Jan 2024</small
              >
              <div class="flex justify-between items-center">
                <h2
                  class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                >
                  President's Economic Reform Package
                </h2>
                <img
                  class="transition-transform duration-200 hover:rotate-180"
                  src="../assets/wrap.png"
                  alt="wrap-img"
                />
              </div>
              <p
                class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
              >
                Analysis of the new economic policies and their potential impact
                on Nigerian markets
              </p>
            </div>
            <div class="flex items-center gap-2">
              <button
                class="bg-[#F9F5FF] text-[#6941C6] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#7F56D9] hover:text-white"
              >
                Economy
              </button>
              <button
                class="bg-[#EEF4FF] text-[#3538CD] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#3538CD] hover:text-white"
              >
                Policy
              </button>
              <button
                class="bg-[#FDF2FA] text-[#C11574] rounded-2xl text-[14px] font-medium py-[2px] px-[10px] transition-all duration-200 hover:bg-[#C11574] hover:text-white"
              >
                Reform
              </button>
            </div>
          </div>
        </div>

        <div
          class="flex flex-col gap-12 md:flex-row xl:flex-col xl:gap-8 xl:w-[48%]"
        >
          <div
            class="flex flex-col xl:flex-row gap-6 transition-all duration-300 hover:transform hover:scale-102"
          >
            <img
              class="xl:w-[48%] h-[200px] object-cover rounded-lg transition-transform duration-300 hover:transform hover:scale-105"
              src="../assets/linear.png"
              alt="Electoral Reform"
            />
            <div class="flex flex-col gap-6">
              <div class="flex flex-col gap-3">
                <small class="font-semibold text-[#6941C6]"
                  >Chioma Okonkwo • 19 Jan 2024</small
                >
                <div class="flex items-center justify-between">
                  <h2
                    class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                  >
                    Electoral Reform Bill Progress
                  </h2>
                  <img
                    class="md:hidden transition-transform duration-200 hover:rotate-180"
                    src="../assets/wrap.png"
                    alt="wrap image"
                  />
                </div>
                <p
                  class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
                >
                  Latest developments in the proposed electoral reform bill and
                  its implications...
                </p>
              </div>
              <div class="flex items-center gap-2">
                <button
                  class="bg-[#F9F5FF] text-[#6941C6] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#7F56D9] hover:text-white"
                >
                  Electoral
                </button>
                <button
                  class="bg-[#FDF2FA] text-[#C11574] rounded-2xl text-[14px] font-medium py-[2px] px-[10px] transition-all duration-200 hover:bg-[#C11574] hover:text-white"
                >
                  Reform
                </button>
              </div>
            </div>
          </div>

          <!-- Second Secondary Post -->
          <div
            class="flex flex-col xl:flex-row gap-6 transition-all duration-300 hover:transform hover:scale-102"
          >
            <img
              class="xl:w-[48%] h-[200px] object-cover rounded-lg transition-transform duration-300 hover:transform hover:scale-105"
              src="../assets/asset-3.png"
              alt="State Elections"
            />
            <div class="flex flex-col gap-6">
              <div class="flex flex-col gap-3">
                <small class="font-semibold text-[#6941C6]"
                  >Babajide Sanwo • 18 Jan 2024</small
                >
                <div class="flex items-center justify-between">
                  <h2
                    class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                  >
                    State Elections Update
                  </h2>
                  <img
                    class="md:hidden transition-transform duration-200 hover:rotate-180"
                    src="../assets/wrap.png"
                    alt="wrap image"
                  />
                </div>
                <p
                  class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
                >
                  Analysis of recent state elections and their impact on
                  national politics...
                </p>
              </div>
              <div class="flex items-center gap-2">
                <button
                  class="bg-[#ECFDF3] text-[#027A48] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#027A48] hover:text-white"
                >
                  Elections
                </button>
                <button
                  class="bg-[#FDF2FA] text-[#C11574] rounded-2xl text-[14px] font-medium py-[2px] px-[10px] transition-all duration-200 hover:bg-[#C11574] hover:text-white"
                >
                  Analysis
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- All Posts Section -->
  <div class="flex gap-8 xl:gap-[64px] flex-col xl:px-[32px]">
    <div class="flex flex-col gap-8">
      <h2
        class="font-semibold text-[24px] text-[#101828] transition-colors duration-200 hover:text-[#000]"
      >
        All Political Updates
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-12 w-full">
        <div
          v-for="(post, index) in allBlogs"
          :key="index"
          class="flex flex-col gap-8 transition-all duration-300 hover:transform hover:scale-102"
        >
          <img
            class="w-full h-[200px] md:h-[240px] object-cover rounded-lg transition-transform duration-300 hover:transform hover:scale-105"
            :src="post.image"
            :alt="post.title"
          />
          <div class="flex flex-col gap-6">
            <div class="flex flex-col gap-3">
              <small class="font-semibold text-[#6941C6]">{{
                post.subtitle
              }}</small>
              <div class="flex justify-between items-center">
                <h2
                  class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                >
                  {{ post.title }}
                </h2>
                <img
                  class="transition-transform duration-200 hover:rotate-180"
                  src="../assets/wrap.png"
                  alt="wrap image"
                />
              </div>
              <p
                class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
              >
                {{ post.news }}
              </p>
            </div>
            <div class="flex items-center gap-2 flex-wrap">
              <button
                v-for="(tag, tagIndex) in post.tags"
                :key="tagIndex"
                :class="[
                  'text-[14px]',
                  'font-medium',
                  'rounded-2xl',
                  'py-[2px]',
                  'px-[10px]',
                  'transition-all',
                  'duration-200',
                  getTagClasses(tag),
                ]"
              >
                {{ tag }}
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Pagination -->
    <div
      class="border-[#EAECF0] border-t-[1px] py-3 px-4 md:px-0 md:py-0 md:pt-5 flex justify-between items-center"
    >
      <div
        @click="previousPage"
        class="flex gap-2 text-[#667085] text-[14px] items-center font-medium cursor-pointer transition-all duration-200 hover:text-[#7F56D9]"
      >
        <img
          class="transition-transform duration-200 group-hover:translate-x-[-2px]"
          src="../assets/left.png"
          alt="back"
        />
        <small class="hidden md:block">Previous</small>
      </div>
      <div class="hidden md:flex gap-[2px]">
        <template v-for="n in 10" :key="n">
          <div
            v-if="n <= 3 || n >= 8 || n === count"
            :class="[
              'rounded-[8px]',
              'w-10',
              'h-10',
              'flex',
              'justify-center',
              'items-center',
              'text-sm',
              'text-[#7F56D9]',
              'cursor-pointer',
              'transition-all',
              'duration-200',
              'hover:bg-[#F9F5FF]',
              { 'bg-[#F9F5FF]': count === n },
            ]"
            @click="count = n"
          >
            {{ n }}
          </div>
          <div
            v-else-if="n === 4"
            class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9]"
          >
            ...
          </div>
        </template>
      </div>
      <div class="font-medium md:hidden text-sm text-[#344054]">
        Page {{ count }} of 10
      </div>
      <div
        @click="nextPage"
        class="flex gap-2 text-[#667085] text-[14px] font-medium items-center cursor-pointer transition-all duration-200 hover:text-[#7F56D9]"
      >
        <small class="hidden md:block">Next</small>
        <img
          class="transition-transform duration-200 group-hover:translate-x-[2px]"
          src="../assets/right.png"
          alt="nextPage"
        />
      </div>
    </div>
  </div>
</template>

<script>
import { ref } from "vue";

export default {
  name: "HomePage",
  setup() {
    const email = ref("");
    const allBlogs = ref([
      {
        image: require("@/assets/asset-4.png"),
        subtitle: "Adebayo Johnson • 17 Jan 2024",
        title: "National Assembly Budget Debate",
        news: "Inside look at the heated debates surrounding the new national budget proposals",
        tags: ["Budget", "Legislature"],
      },
      {
        image: require("@/assets/asset-5.png"),
        subtitle: "Folake Adeleke • 16 Jan 2024",
        title: "State Governors Forum",
        news: "Key decisions from the latest governors' forum meeting on security and economy",
        tags: ["Governance", "Security", "Economy"],
      },
      {
        image: require("@/assets/asset-6.png"),
        subtitle: "Ibrahim Musa • 15 Jan 2024",
        title: "Anti-Corruption Campaign",
        news: "New measures implemented by EFCC to combat corruption in public offices",
        tags: ["Anti-corruption", "Policy"],
      },
      {
        image: require("@/assets/asset-7.png"),
        subtitle: "Ngozi Okafor • 14 Jan 2024",
        title: "Political Party Alignments",
        news: "Recent political party mergers and their implications for future elections",
        tags: ["Politics", "Parties"],
      },
      {
        image: require("@/assets/asset-8.png"),
        subtitle: "Yusuf Ahmed • 13 Jan 2024",
        title: "Local Government Reforms",
        news: "Proposed reforms to strengthen local government administration",
        tags: ["Local Government", "Reform"],
      },
      {
        image: require("@/assets/asset-9.png"),
        subtitle: "Aisha Bukar • 12 Jan 2024",
        title: "Youth in Politics Initiative",
        news: "New programs to encourage youth participation in Nigerian politics",
        tags: ["Youth", "Politics"],
      },
    ]);
    let count = ref(1);

    const emailInputValue = () => {
      console.log(email.value);
    };

    const previousPage = () => {
      if (count.value > 1) {
        count.value--;
      }
    };

    const nextPage = () => {
      if (count.value < 10) {
        count.value++;
      }
    };

    const getTagClasses = (tag) => {
      const baseClasses = "hover:text-white";
      const tagMap = {
        Budget: "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]",
        Legislature: "bg-[#EEF4FF] text-[#3538CD] hover:bg-[#3538CD]",
        Governance: "bg-[#ECFDF3] text-[#027A48] hover:bg-[#027A48]",
        Security: "bg-[#FDF2FA] text-[#C11574] hover:bg-[#C11574]",
        Economy: "bg-[#FFF6ED] text-[#C4320A] hover:bg-[#C4320A]",
        "Anti-corruption": "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]",
        Policy: "bg-[#EEF4FF] text-[#3538CD] hover:bg-[#3538CD]",
        Politics: "bg-[#ECFDF3] text-[#027A48] hover:bg-[#027A48]",
        Parties: "bg-[#FDF2FA] text-[#C11574] hover:bg-[#C11574]",
        "Local Government": "bg-[#F8F9FC] text-[#363F72] hover:bg-[#363F72]",
        Reform: "bg-[#FFF6ED] text-[#C4320A] hover:bg-[#C4320A]",
        Youth: "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]",
      };
      return `${
        tagMap[tag] || "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]"
      } ${baseClasses}`;
    };

    return {
      email,
      previousPage,
      emailInputValue,
      allBlogs,
      count,
      nextPage,
      getTagClasses,
    };
  },
};
</script>

<style>
.scale-102 {
  transform: scale(1.02);
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.fade-in {
  animation: fadeIn 0.3s ease-out forwards;
}

.btn-shadow {
  color: #fff;
  box-shadow: 0px 2px 3px 0px #1018280d;
  font-weight: 500;
}
</style>
