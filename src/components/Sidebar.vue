<template>
  <aside class="w-64" aria-label="Sidebar">
    <div class="flex flex-col overflow-y-auto h-screen py-4 px-3 bg-[#00000017] rounded-lg ">



      <div>
        <a href="#"
          class="flex flex-col gap-2 justify-center items-center p-2 text-base font-normal rounded-lg text-[#8990AD]  hover:bg-[#FFFFFF] hover:text-[#495172] ">
          <img src="../assets/metrics.svg" />
          <span class="ml-3">Dashboard</span>
        </a>
      </div>
      <div>
        <a href="#"
          class="flex flex-col gap-2 justify-center items-center p-2 text-base font-normal rounded-lg dark:text-[#8990AD]  hover:bg-[#FFFFFF] hover:text-[#495172]">
          <img src="../assets/analytics.svg" />
          <span class="ml-3">Analytics</span>
        </a>
      </div>
      <div>
        <a href="#"
          class="flex flex-col gap-2 justify-center items-center p-2 text-base font-normal  rounded-lg dark:text-[#8990AD]  hover:bg-[#FFFFFF] hover:text-[#495172]">
          <img src="../assets/currency-exchange-2.svg" />
          <span class="ml-3">Trading</span>
        </a>
      </div>
      <div>
        <a href="#"
          class="flex flex-col gap-2 justify-center items-center p-2 text-base font-normal rounded-lg dark:text-[#8990AD]  hover:bg-[#FFFFFF] hover:text-[#495172]">
          <img src="../assets/sound-wave.svg" />
          <span class="ml-3">Notifications</span>
        </a>
      </div>
      
      <div class="mt-auto">
        <a href="#"
          class="flex  flex-col items-center p-2 text-base font-normal text-gray-900 rounded-lg  dark:text-[#8990AD]  hover:bg-[#FFFFFF] hover:text-[#495172]">
          <img src="../assets/logout.svg" />
          <span class="ml-3">Logout</span>
        </a>
      </div>
    </div>
  </aside>
</template>
  
<script>
export default {
  name: 'Sidebar'
}
</script>
  
<style scoped>/* You can add more styles here if necessary */</style>