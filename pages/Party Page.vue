<template>
  <div class="h-screen bg-[#f3f3f3]">
    <div class="w-screen flex flex-col pt-3 pl-3 pr-7 pb-[15px]">
      <div class="flex mb-[28px]">
        <img class="h-[23px]" src="../imgs/RHBPartyGreyLogo.png" />
      </div>
      <input
        class="rounded-md w-5/6 h-[30px] block mx-auto pl-[5px]"
        placeholder="Search name..."
        type="text"
      />
    </div>
    <div class="h-3/4 w-screen overflow-y-auto pt-[25px]">
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-9/12 p-[30px]">
          <p class="text-2xl text-[#6B6B6B] font-bold">Create a Party</p>
        </div>
        <button class="py-2 px-4 rounded inline-flex items-center">
          <img class="" src="../icons/plus.png" />
        </button>
      </div>
      
      <nuxt-link to="Party Amount">
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        
        <div class="w-10/12 pl-[20px]">
          <p class="text-xl text-[#6B6B6B] font-semibold">25/10 Birthday</p>
          <p class="text-sm text-[#6B6B6B] font-semibold">Date Created:</p>
          <p class="text-sm text-[#6B6B6B] font-semibold mb-[5px]">
            16/10/2023
          </p>
          <p class="text-sm text-red-700 font-semibold">unpaid</p>
        </div>
  
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>
      </nuxt-link>

      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-10/12 pl-[20px]">
          <p class="text-xl text-[#6B6B6B] font-semibold">Dinner party</p>
          <p class="text-sm text-[#6B6B6B] font-semibold">Date Created:</p>
          <p class="text-sm text-[#6B6B6B] font-semibold mb-[5px]">
            16/10/2023
          </p>
          <p class="text-sm text-green-400 font-semibold">paid</p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>

      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-10/12 pl-[20px]">
          <p class="text-xl text-[#6B6B6B] font-semibold">Funding for house</p>
          <p class="text-sm text-[#6B6B6B] font-semibold">Date Created:</p>
          <p class="text-sm text-[#6B6B6B] font-semibold mb-[5px]">
            16/10/2023
          </p>
          <p class="text-sm text-green-400 font-semibold">paid</p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>
    </div>

    <nuxt-link to="homepage">
    <div class="pt-[25px]">
      <button
        class="block m-auto rounded-xl text-white bg-[#95D0A9] p-[15px] w-3/6"
      >
        Back
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
