<template>
    <div class="min-w-screen min-h-screen bg-[#eeeeee]">
        <div class="min-w-screen h-20 bg-[#ffffff]">
            <div>
                <img class="w-1/2 pt-5 pb-5 ml-4" src="../imgs/RHBPartyWhiteLogo.png" />
            </div>
        </div>

        <div class="mt-2 min-w-screen h-14 bg-[#ffffff]">
            <p class="pt-4 pl-4 font-bold" style="font-size:16px">Accounts</p>
        </div>

        <div class="box-border ml-6 mr-6 mt-12 h-60 rounded-xl bg-[#ffffff]">
            <p class="pl-4 pt-8 font-bold" style="font-size:14px">Account Number</p>

            <div class="box-border bg-[#ffffff] shadow-md mt-2 ml-4 mr-4 h-10">
                <p class="pt-2 pl-2 text-gray-400">1234-1234-123</p>
            </div>

            <div>
                <p class="pl-4 pt-4 font-bold" style="font-size:14px">Bank</p>
            </div>

            <div class="relative w-70 ml-4 mr-4 mt-4 shadow-md">
                <button
                  class="flex items-center justify-between px-3 py-2 shadow-md bg-white w-full border rounded-lg"
                  @click="isOptionsExpanded = !isOptionsExpanded"
                  @blur="isOptionsExpanded = false"
                >
                  <span>{{ selectedOption }}</span>
                  <svg
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    class="h-4 w-4 transform transition-transform duration-200 ease-in-out"
                    :class="isOptionsExpanded ? 'rotate-180' : 'rotate-0'"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M19 9l-7 7-7-7"
                    />
                  </svg>
                </button>
                <transition
                  enter-active-class="transform transition duration-500 ease-custom"
                  enter-class="-translate-y-1/2 scale-y-0 opacity-0"
                  enter-to-class="translate-y-0 scale-y-100 opacity-100"
                  leave-active-class="transform transition duration-300 ease-custom"
                  leave-class="translate-y-0 scale-y-100 opacity-100"
                  leave-to-class="-translate-y-1/2 scale-y-0 opacity-0"
                >
                  <ul
                    v-show="isOptionsExpanded"
                    class="absolute left-0 right-0 mb-4 bg-white divide-y rounded-lg shadow-lg overflow-hidden"
                  >
                    <li
                      v-for="(option, index) in options"
                      :key="index"
                      class="px-3 py-2 transition-colors duration-300 hover:bg-gray-200"
                      @mousedown.prevent="setOption(option)"
                    >
                      {{ option }}
                    </li>
                  </ul>
                </transition>
              </div>
        </div>

        <div class="box-border ml-6 mr-6 mt-8 h-28 rounded-xl bg-[#ffffff] pt-6 pl-6" style="font-size: 14px">
            <p><b>Name:</b> Sandra Tan</p>
            <p><b>Account Number:</b> 1234-1234-123</p>
            <p><b>Bank Selected:</b> RHB Bank</p>
        </div>

        <div class="pt-40 flex space-between">
            <button
              class="block m-auto rounded-xl text-white bg-[#95D0A9] p-[15px] w-3/6"
            >
              Invite
            </button>
            <button
              class="block m-auto rounded-xl text-white bg-[#95D0A9] p-[15px] w-2/6"
            >
              Back
            </button>
          </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      isOptionsExpanded: false,
      selectedOption: "RHB",
      options: ["CIMB", "Hong Leong Bank", "Maybank"]
    };
  },
  methods: {
    setOption(option) {
      this.selectedOption = option;
      this.isOptionsExpanded = false;
    }
  }
};
</script>

<style>
.ease-custom {
  transition-timing-function: cubic-bezier(.61,-0.53,.43,1.43);
}
</style>