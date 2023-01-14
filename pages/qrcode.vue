<template>
<div>
    <div>
        <img class="w-1/3 mt-8 ml-4" src="../imgs/RHBPartyWhiteLogo.png" />
    </div>

    <div class="text-center pl-10 pt-10 pr-10 font-bold text-gray-500" style="font-size:28px">
        <p>Show your QR Code</p>
    </div>

    <div class="mt-12 min-w-screen h-90 bg-[#1e6bb0] flex justify-center items-center">
        <nuxt-link to="transactioncomp">
        <div class="">
            <img class="p-8" src="../imgs/qrcode.png" />
        </div>
        </nuxt-link>
    </div>

    <div class="pt-10 pl-8 pb-10 font-bold text-gray-500" style="font-size: 14px">
        <p>Total amount : RM100</p>
        <p>You receive : RM70</p>
        <p>RHB Points : 1000</p>
    </div>

    <nuxt-link to="transactioncomp">
    <div class="p-[20px] ">
        <button
          class="block m-auto rounded-xl text-white bg-[#E79C9C] p-[15px] w-3/6"
        >
          Cancel
        </button>
      </div>
    </nuxt-link>
</div>
      
    
</template>