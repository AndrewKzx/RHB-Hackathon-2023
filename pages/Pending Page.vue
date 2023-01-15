<template>
  <div class="h-screen">
    <div class="flex flex-col bg-white pt-3 pl-3 pr-7 pb-[30px]">
      <div class="w-screen flex mb-[28px]">
        <img class="h-[23px]" src="../imgs/RHBPartyWhiteLogo.png" />
      </div>
      <div class="w-4/6 h-[86px] display mx-auto mb-[20px]">
        <p class="text-[#6B6B6B] text-3xl text-center font-bold">
          Waiting for 0/6 to accept
        </p>
      </div>
      <button
        class="block shadow-md m-auto rounded-xl text-white bg-[#E58585] p-[5px] w-2/6"
      >
        Cancel
      </button>
    </div>
    <nuxt-link to="Accept Prompt">
    <div class="h-3/5 w-screen bg-[#6acde7] overflow-y-auto pt-[25px]">
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12">
          <img class="block mx-auto my-auto" src="../imgs/person1.png" />
        </div>
        <div class="w-7/12 shadow-md">
          <p class="text-[#6B6B6B] font-semibold">James Williamson</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-[#D1D384] pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-[#D1D384] pl-2"> Pending </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12 shadow-md">
          <img class="block  mx-auto my-auto" src="../imgs/person2.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Jesslyn Chai</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-[#D1D384] pl-2"> 10.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-[#D1D384] pl-2"> Pending </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12 shadow-md">
          <img class="block mx-auto my-auto" src="../imgs/person3.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Kamil Hazziq</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-[#D1D384] pl-2"> 10.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-[#D1D384] pl-2"> Pending </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12 shadow-md">
          <img class="block mx-auto my-auto" src="../imgs/person4.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Jack Teoh</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-[#D1D384] pl-2"> 10.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-[#D1D384] pl-2"> Pending </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
      <div
        class="rounded-xl w-5/6 h-3/12 bg-white mx-auto mb-[25px] flex items-stretch justify-around"
      >
        <div class="w-3/12 shadow-md">
          <img class="block mx-auto my-auto" src="../imgs/person1.png" />
        </div>
        <div class="w-7/12">
          <p class="text-[#6B6B6B] font-semibold">Taneth Wong</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-[#D1D384] pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-[#D1D384] pl-2"> Pending </span>
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
        <div class="w-7/12 shadow-md">
          <p class="text-[#6B6B6B] font-semibold">Landra</p>
          <p class="text-[#6B6B6B] font-semibold">+601234567891</p>
          <p class="text-[#6B6B6B] font-semibold">
            RM:
            <span class="text-[#D1D384] pl-2"> 20.00 </span>
          </p>
          <p class="text-[#6B6B6B] font-semibold">
            Status:
            <span class="text-[#D1D384] pl-2"> Pending </span>
          </p>
        </div>
        <div class="w-1/12"></div>
      </div>
    </div>
  </nuxt-link>
   
    <div class="pt-4 pl-6 flex space-between">
      <nuxt-link to="qrcode">
        <div class="box-border shadow-md p-10 h-4 rounded-xl flex justify-center items-center" style="background-color: #0365B8"> 
            
            <h1 class="text-white text-center">
                Pay With QR
            </h1>
        </div>
        </nuxt-link>
        
        <nuxt-link to="Party Amount">
          <div class="box-border shadow-md ml-14 p-10 h-4 rounded-xl flex justify-center items-center" style="background-color: #a4a4a4"> 
              
              <h1 class="text-white text-center">
                  Back 
              </h1>
          </div>
          </nuxt-link>
    </div>
  
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
