<template>
  <div class="pt-10" style="background-color :#b4e4f2">

    <div class = "h-1/2" >
    <div> 
      <div class = "flex justify-evenly h-12">
        <div class="h-5 w-5" ><img src="../imgs/overview.png" alt=""></div>
        <div class="h-20 w-20 mx-24"><img src="../imgs/rhbnew.png" alt=""></div>
        <div class="h-8 w-8"><img src="../imgs/logoutnew.png" alt=""></div>
      </div>

      <div class="text-white text-xs flex justify-center pb-2">
      <p>SAVINGS V</p>
      </div>

      <div class ="px-5 border rounded-3xl h-60 mx-5 pt-2 " style = "background-color: white"> <!-- part 2 whitebox -->

        <div class="flex flex-col items-center mb-2">
          <div class="text-sm"><p>RHB Smart Account-i</p></div>
          <div class="font-bold text-3xl"><p>MYR 16,000.00</p></div>
          <div class="text-sm"><p>2-68356-00063-0</p></div>
        </div>

        <div class ="flex flex-col text-sm">
          <div class = "flex mb-4 pl-2">
             <div class="pr-24"><p>KK Supermarket</p></div>
             <div class="ml-4 text-red-600"><p>-MYR 50.00</p></div>
            </div>
            <div class = "flex mb-4 pl-2">
             <div class="pr-24"><p>Laura's Boutique</p></div>
             <div class="ml-3 text-red-600"><p>-MYR 50.00</p></div>
            </div>
            <div class = "flex">
             <div class="pr-32 pl-2"><p>Natalie Vong</p></div>
             <div class="text-green-400"><p>MYR 200.00</p></div>
            </div>
        </div>

        <div class="flex justify-end pt-4">
          <div><button class="border rounded-full pt-1 pb-1 px-6 bg-[#0365B8] text-white" >Pay</button></div>
          <div class="h-5 w-5 ml-2 pt-1"><img src="../imgs/detail.png" alt=""></div>
        </div>

      </div>

      <div class="h-28 mt-14 pt-3 mx-4" style = "background-color : white">

        <div><img src="../imgs/addnew.jpg" alt=""></div>
        
      </div>

    <NuxtLink to="Party Page">
      <div class="h-28 p-5 ">
        
        <button class="flex h-16 mt-1" >
          <div><img class = " w-full border rounded-3xl " src="../imgs/rhbparty.jpg" alt=""></div>
        </button>
      
      </div>
    </NuxtLink>

    </div>

    <div class="bg-white pt-4 h-3/4">
      <div class="text-xs mb-2 pl-10 " style="color: #9D9D9D"><p>OFFERS & PROMOTIONS</p></div>
      <div class="h-32 w-72 ml-12"><img src="../imgs/mountain.png" alt=""></div>
    </div>

  </div>



  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>



    </div>
