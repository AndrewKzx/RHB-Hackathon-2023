<template>
    <div>
        <div>
            <img class="w-1/3 mt-8 ml-4" src="../imgs/RHBPartyWhiteLogo.png" />
        </div>

        <div class="text-center pl-10 pt-10 pr-10">
            <p class="font-bold" style="font-size:20px">Transaction Completed</p>
            <div class="pt-6">
                <p>Thank you for using RHB Party,</p>
                <p>your transaction will be sent to</p>
                <p>your transaction history</p>
            </div>
            
        </div>

        <div>
            <img class="pl-10 pr-10" src="../imgs/transactioncomp.png" />
        </div>

        <nuxt-link to="transactioncomp">
            <div class="p-[20px] ">
                <button
                  class="block m-auto rounded-xl text-white bg-[#0365B8] p-[15px] w-3/6 font-bold">
                  Back to Home
                </button>
              </div>
            </nuxt-link>
    </div>
</template>