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
          Our blog
        </p>
        <h1
          class="text-[36px] leading-[44px] lg:text-[48px] font-semibold text-[#101828] hover:text-[#000] transition-colors duration-200"
        >
        Stories and interviews
        </h1>
      </div>
      <p
        class="text-[#667085] text-[18px] lg:text-xl w-full lg:w-[768px] text-center transition-colors duration-200 hover:text-[#4B5563]"
      >
      Subscribe to learn about new product features, the latest in technology, solutions, and updates.
      </p>
    </div>
    <div
      class="flex flex-col w-full lg:flex-row items-start gap-4 justify-center"
    >
      <div class="text-start w-full lg:w-[360px] flex flex-col gap-2">
        <input
          class="border w-full border-[#D0D5DD] py-3 pl-4 pr-[14px] rounded-lg transition-all duration-200 focus:ring-2 focus:ring-[#7F56D9] focus:border-transparent hover:border-[#7F56D9]"
          type="text"
          placeholder="Enter your email"
        />
        <p
          class="text-sm text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
        >
          We care about your data in our
          <a
            class="underline leading-5 hover:text-[#7F56D9] transition-colors duration-200"
            href="../assets/asset4.png"
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
      Recent blog posts
      </h2>
      <div class="flex flex-col xl:flex-row gap-12 justify-between">
        <!-- Main Featured Post -->
        <div
          class="flex flex-col gap-8 xl:w-[48%] transition-all duration-300 hover:transform hover:scale-102"
        >
          <img
            class="w-full h-[200px] md:h-[228px] object-cover rounded-lg transition-transform duration-300 hover:transform hover:scale-105"
            src="../assets/asset1.png"
            alt="Presidential Address"
          />
          <div class="flex flex-col gap-6">
            <div class="flex flex-col gap-3">
              <small class="font-semibold text-[#6941C6]"
                >Olivia Rhye • 20 Jan 2022</small
              >
              <div class="flex justify-between items-center">
                <h2
                  class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                >
                UX review presentations
                </h2>
            
              </div>
              <p
                class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
              >
                How do you create compelling presentations that wow your colleagues and impress your managers?
              </p>
            </div>
            <div class="flex items-center gap-2">
              <button
                class="bg-[#F9F5FF] text-[#6941C6] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#7F56D9] hover:text-white"
              >
                Design
              </button>
              <button
                class="bg-[#EEF4FF] text-[#3538CD] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#3538CD] hover:text-white"
              >
                Research
              </button>
              <button
                class="bg-[#FDF2FA] text-[#C11574] rounded-2xl text-[14px] font-medium py-[2px] px-[10px] transition-all duration-200 hover:bg-[#C11574] hover:text-white"
              >
                Presentation
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
              src="../assets/asset2.png"
              alt="Migrating to Linear 101"
            />
            <div class="flex flex-col gap-6">
              <div class="flex flex-col gap-3">
                <small class="font-semibold text-[#6941C6]"
                  >Phoenix Baker • 19 Jan 2022</small
                >
                <div class="flex items-center justify-between">
                  <h2
                    class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                  >
                  Migrating to Linear 101
                  </h2>
                  <img
                    class="md:hidden transition-transform duration-200 "
                    src="../assets/asset4.png"
                    alt="wrap image"
                  />
                </div>
                <p
                  class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
                >
                Linear helps streamline software projects, sprints, tasks, and bug tracking. Here’s how to get...
                </p>
              </div>
              <div class="flex items-center gap-2">
                <button
                  class="bg-[#F9F5FF] text-[#6941C6] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#7F56D9] hover:text-white"
                >
                  Design
                </button>
                <button
                  class="bg-[#FDF2FA] text-[#C11574] rounded-2xl text-[14px] font-medium py-[2px] px-[10px] transition-all duration-200 hover:bg-[#C11574] hover:text-white"
                >
                  Research
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
              src="../assets/asset4.png"
              alt="software project"
            />
            <div class="flex flex-col gap-6">
              <div class="flex flex-col gap-3">
                <small class="font-semibold text-[#6941C6]"
                  >Lana Steiner • 18 Jan 2022</small
                >
                <div class="flex items-center justify-between">
                  <h2
                    class="text-[#101828] font-semibold text-xl xl:text-2xl transition-colors duration-200 hover:text-[#7F56D9]"
                  >
                  Building your API Stack
                  </h2>
          
                </div>
                <p
                  class="text-[#667085] transition-colors duration-200 hover:text-[#4B5563]"
                >
                The rise of RESTful APIs has been met by a rise in tools for creating, testing, and manag...
                </p>
              </div>
              <div class="flex items-center gap-2">
                <button
                  class="bg-[#ECFDF3] text-[#027A48] text-[14px] font-medium rounded-2xl py-[2px] px-[10px] transition-all duration-200 hover:bg-[#027A48] hover:text-white"
                >
                  Design
                </button>
                <button
                  class="bg-[#FDF2FA] text-[#C11574] rounded-2xl text-[14px] font-medium py-[2px] px-[10px] transition-all duration-200 hover:bg-[#C11574] hover:text-white"
                >
                  Research
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
      All blog posts
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
        <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            1
          </div>
          <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            2
          </div>
          <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            3
          </div>
          <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            ...
          </div>
          <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            8
          </div>
          <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            9
          </div>
          <div class="rounded-[8px] w-10 h-10 flex justify-center items-center text-sm text-[#7F56D9] cursor-pointer transition-all duration-200 hover:bg-[#F9F5FF]">
            10
          </div>
      </div>
      <div class="font-medium md:hidden text-sm text-[#344054]">
        Page 1 of 10
      </div>
      <div
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
    const allBlogs = ref([
      {
        image: require("@/assets/asset5.png"),
        subtitle: "Alec Whitten • 17 Jan 2022",
        title: "Bill Walsh leadership lessons",
        news: "Like to know the secrets of transforming a 2-14 team into a 3x Super Bowl winning Dynasty?",
        tags: ["Leadership", "Management"],
      },
      {
        image: require("@/assets/asset6.png"),
        subtitle: "Demi WIlkinson • 16 Jan 2022",
        title: "PM mental models",
        news: "Mental models are simple expressions of complex processes or relationships.",
        tags: ["Product", "Research", "Frameworks"],
      },
      {
        image: require("@/assets/asset7.png"),
        subtitle: "Candice Wu • 15 Jan 2022",
        title: "What is Wireframing?",
        news: "Introduction to Wireframing and its Principles. Learn from the best in the industry.",
        tags: ["Design", "Research"],
      },
      {
        image: require("@/assets/asset8.png"),
        subtitle: "Natali Craig • 14 Jan 2022",
        title: "How collaboration makes us better designers",
        news: "Collaboration can make our teams stronger, and our individual designs better.",
        tags: ["Design", "Research"],
      },
      {
        image: require("@/assets/asset9.png"),
        subtitle: "Drew Cano • 13 Jan 2022",
        title: "Our top 10 Javascript frameworks to use",
        news: "JavaScript frameworks make development easy with extensive features and functionalities",
        tags: ["Software", "Tools" , "Saas"],
      },
      {
        image: require("@/assets/asset10.png"),
        subtitle: "Orlando Diggs • 12 Jan 2022",
        title: "Podcast: Creating a better CX Community",
        news: "Starting a community doesn’t need to be complicated, but how do you get started?",
        tags: ["Podcast", "Customer sucess"],
      },
    ]);


  
    const getTagClasses = (tag) => {
      const baseClasses = "hover:text-white";
      const tagMap = {
        Leadership: "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]",
        Management: "bg-[#EEF4FF] text-[#3538CD] hover:bg-[#3538CD]",
        Product: "bg-[#ECFDF3] text-[#027A48] hover:bg-[#027A48]",
        Research: "bg-[#FDF2FA] text-[#C11574] hover:bg-[#C11574]",
        Frameworks: "bg-[#FFF6ED] text-[#C4320A] hover:bg-[#C4320A]",
        Design: "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]",
        Softwares: "bg-[#ECFDF3] text-[#027A48] hover:bg-[#027A48]",
        Tools: "bg-[#FDF2FA] text-[#C11574] hover:bg-[#C11574]",
        Saas: "bg-[#F8F9FC] text-[#363F72] hover:bg-[#363F72]",
        Podcast: "bg-[#FFF6ED] text-[#C4320A] hover:bg-[#C4320A]",
        "Customer service": "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]",
      };
      return `${
        tagMap[tag] || "bg-[#F9F5FF] text-[#6941C6] hover:bg-[#6941C6]"
      } ${baseClasses}`;
    };

    return {
      allBlogs,
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
