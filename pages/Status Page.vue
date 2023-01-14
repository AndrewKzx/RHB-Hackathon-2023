<template>
  <div class="h-screen">
    <div class="flex flex-col bg-white pt-3 pl-3 pr-7 pb-[30px]">
      <div class="w-screen flex mb-[28px]">
        <img class="h-[23px]" src="../imgs/RHBPartyWhiteLogo.png" />
      </div>
      <div class="w-4/6 h-[86px] display mx-auto mb-[20px]">
        <p class="text-[#6B6B6B] text-2xl text-center font-bold">
          Total: RM 100
        </p>
        <p class="text-[#6B6B6B] text-2xl text-center font-bold">Paid: 5</p>
        <p class="text-[#6B6B6B] text-2xl text-center font-bold">Unpaid: 1</p>
      </div>
    </div>
    <div class="h-3/5 w-screen bg-[#1e6bb0] overflow-y-auto pt-[25px]">
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person1.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">James Williamson</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-green-500 pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-green-500 pl-2"> Paid </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person2.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Jesslyn Chai</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-green-500 pl-2"> 10.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-red-600 pl-2"> Unpaid </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person3.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Kamil Hazziq</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-green-500 pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-green-500 pl-2"> Paid </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person4.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Jack Teoh</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-green-500 pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-green-500 pl-2"> Paid </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person1.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Taneth Wong</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-green-500 pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-green-500 pl-2"> Paid </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person2.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Landra</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-green-500 pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-green-500 pl-2"> Paid </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
    </div>
    <nuxt-link to="Reminder">
    <div class="p-[20px] flex space-between">
      <button
        class="block m-auto rounded-xl text-white bg-[#95D0A9] p-[15px] w-3/6"
      >
        Remind
      </button>
    </div>
  </nuxt-link>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
