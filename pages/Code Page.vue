<template>
  <div class="h-screen bg-[#f3f3f3]">
    <div class="w-screen flex flex-col pt-3 pl-3 pr-7 pb-[15px]">
      <div class="flex mb-[28px]">
        <img class="h-[23px]" src="../imgs/RHBPartyWhiteLogo.png" />
      </div>
    </div>
    <div class="w-5/6 mx-auto mb-[30px]">
      <p class="text-3xl text-center text-[#6B6B6B] font-bold">
        Enter Verification Code
      </p>
    </div>
    <input
      class="rounded-xl w-5/6 h-[70px] block mx-auto pl-[5px]"
      placeholder="Enter Code"
      type="text"
    />
    <div class="w-5/6 mx-auto mb-[50px]">
      <p class="text-sm text-center text-[#6B6B6B]">Resend Code?</p>
    </div>
    <button
      class="block m-auto rounded-xl text-white bg-[#95D0A9] p-[15px] w-2/6 mb-[30px]"
    >
      Accept
    </button>

    <button
      class="block m-auto rounded-xl text-white bg-[#E58585] p-[15px] w-2/6 mb-[30px]"
    >
      Reject
    </button>
  </div>
</template>

<script>
export default {
  name: "CodePage",
};
</script>
