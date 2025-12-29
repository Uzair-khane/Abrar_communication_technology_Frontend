<script setup>
import { ref } from "vue";
  const isopen = ref(false)
let email = ref("info@gmail.com");
let phoneNum = ref("0301-239XXXXXX");
let time = ref("Sunday To Thursday - 8:00AM - 5:00PM");
</script>

<template>
    <div>
        <!-- header  -->
        <div v-if="!isopen" class="bg-slate-800 md:flex  hidden justify-between px-5 py-3 text-white">
            <!-- contact  -->
            <div class="flex gap-4 mx-4">
                <p class="border-r-2 border-gray-500 px-2 pr-4 flex items-center gap-2">
                    <Icon name="mdi:email-outline" class="text-amber-600 text-xl" />
                    <span>{{ email }}</span>
                </p>
                <p class="border-r-2  border-gray-500 px-2 pr-4 flex items-center gap-2">
                    <Icon name="mdi:phone-outline" class="text-amber-600 text-xl" />
                    <span>{{ phoneNum }}</span>
                </p>
                <p class="border-r-2  border-gray-500 px-2 pr-4 flex items-center gap-2">
                    <Icon name="mdi:timer-outline" class="text-amber-600 text-xl" />
                    <span>{{ time }}</span>
                </p>

            </div>
            <!-- button  -->
            <div>
                <NuxtLink to="#"> <button
                        class="py-2 mx-6 bg-sky-600 rounded-sm font-semibold cursor-pointer hover:bg-sky-500  px-3">Talk To
                        Export</button> </NuxtLink>
            </div>
        </div>
        <!-- Nav bar  -->
          <div class=" w-full">
   <nav class="flex justify-between items-center px-10  shadow-md">
    <!-- logo  -->
     <div>
   <img src="../assets/images/logo.PNG" class="w-20 h-20" alt="">
     </div>
     <!-- link  -->
      <div >
        <ul class=" hidden md:flex gap-7 px-5 text-md text-slate-700 font-semibold ">
          <NuxtLink class="  hover:text-amber-200" to="/"><li>Home</li></NuxtLink>
          <NuxtLink class=" hover:text-amber-200"  to="/"><li>About</li></NuxtLink>
          <NuxtLink class=" hover:text-amber-200"  to="/"><li>srvices</li></NuxtLink>
          <NuxtLink class=" hover:text-amber-200"  to="/"><li>Blog</li></NuxtLink>
          <NuxtLink class=" hover:text-amber-200"  to="/"><li>contact</li></NuxtLink>
         
          
        </ul>
       <button @click="isopen = !isopen" class="md:hidden">
        <Icon v-if="!isopen" name="uil:bars" />
        <Icon v-else name="uil:times" />
       </button>
      </div>
   </nav>
   
<transition
  enter-active-class="transition-all duration-300 ease-out"
  enter-from-class="opacity-0 max-h-0"
  enter-to-class="opacity-100 max-h-96"
  leave-active-class="transition-all duration-200 ease-in"
  leave-from-class="opacity-100 max-h-96"
  leave-to-class="opacity-0 max-h-0"
>
  <div
    v-show="isopen"
    class="md:hidden bg-slate-200  px-5 py-4 overflow-hidden"
  >
    <ul class="flex flex-col justify-center text-center gap-4 text-slate-700 font-semibold">
      <NuxtLink @click="isopen=false" to="/">Home</NuxtLink>
      <NuxtLink @click="isopen=false" to="/about">About</NuxtLink>
      <NuxtLink @click="isopen=false" to="/services">Services</NuxtLink>
      <NuxtLink @click="isopen=false" to="/blog">Blog</NuxtLink>
      <NuxtLink @click="isopen=false" to="/contact">Contact</NuxtLink>
    </ul>
  </div>
</transition>

  </div>
    </div>
</template>
