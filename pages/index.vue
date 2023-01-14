<template>
  <div class="h-screen">
    <div class="flex flex-col bg-[#1e6bb0] pt-3 pl-7 pr-7 pb-[15px]">
      <div class="p-[10px] h-23 bg-white rounded-3xl mb-[28px]">
        <p class="text-center mb-[12px]">
          Total amount:
          <span class="text-[#6B6B6B] underline pl-4"> RM 100 </span>
        </p>
        <div class="flex justify-around">
          <button class="rounded-xl text-white bg-[#95D0A9] p-[5px] w-2/6">
            Split Evenly
          </button>
          <button class="rounded-xl text-white bg-[#E58585] p-[5px] w-2/6">
            Reset
          </button>
        </div>
      </div>

      <div class="flex justify-around">
        <button
          class="bg-white border-2 border-black rounded-xl text-black p-[5px] w-[150px]"
        >
          Add from Contacts
        </button>
        <button
          class="bg-white border-2 border-black rounded-xl text-black p-[5px] w-[150px]"
        >
          Invite to Party
        </button>
      </div>
    </div>
    <div class="h-4/6 w-screen bg-[#f3f3f3] pt-[5px] overflow-y-auto">
      <div class="w-screen flex mb-[14px]">
        <img class="h-[25px]" src="../imgs/RHBPartyGreyLogo.png" />
      </div>
      <input
        class="rounded-md w-5/6 h-[30px] block mx-auto pl-[5px] mb-[20px]"
        placeholder="Search name..."
        type="text"
      />
      <div></div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person1.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B]">James Williamson</p>
          <p class="text-[#6B6B6B] mb-[10px]">+601234567891</p>
          <p class="text-[#6B6B6B]">
            Total amount:
            <span class="text-[#6B6B6B] underline pl-4"> RM 20.00 </span>
          </p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>

      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person2.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B]">James Williamson</p>
          <p class="text-[#6B6B6B] mb-[10px]">+601234567891</p>
          <p class="text-[#6B6B6B]">
            Total amount:
            <span class="text-[#6B6B6B] underline pl-4"> RM 20.00 </span>
          </p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>

      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person3.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B]">James Williamson</p>
          <p class="text-[#6B6B6B] mb-[10px]">+601234567891</p>
          <p class="text-[#6B6B6B]">
            Total amount:
            <span class="text-[#6B6B6B] underline pl-4"> RM 20.00 </span>
          </p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>

      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person4.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B]">James Williamson</p>
          <p class="text-[#6B6B6B] mb-[10px]">+601234567891</p>
          <p class="text-[#6B6B6B]">
            Total amount:
            <span class="text-[#6B6B6B] underline pl-4"> RM 20.00 </span>
          </p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>

      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person1.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B]">James Williamson</p>
          <p class="text-[#6B6B6B] mb-[10px]">+601234567891</p>
          <p class="text-[#6B6B6B]">
            Total amount:
            <span class="text-[#6B6B6B] underline pl-4"> RM 20.00 </span>
          </p>
        </div>
        <div class="w-1/12">
          <img class="block mx-auto my-auto" src="../icons/cross.png" />
        </div>
      </div>
    </div>
    <div class="p-[20px]">
      <button
        class="block m-auto rounded-xl text-white bg-[#95D0A9] p-[15px] w-3/6"
      >
        Send Request
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
