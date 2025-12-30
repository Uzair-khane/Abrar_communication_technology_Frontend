<template>
    <div class="relative h-[560px] w-full bg-[url('/images/hero.jpg')] bg-cover bg-center">

        <!-- Overlay -->
        <div class="absolute inset-0 bg-black/50"></div>

        <!-- Content -->
        <div class="relative z-10 text-white flex flex-col px-10 md:px-28 py-20 ">
            <h1 class="text-3xl text-center sm:text-left sm:text-5xl md:text-5xl font-bold leading-normal">Technology
                That Works. <br>
                <span class="text-yellow-600"> When It Matters.</span>
            </h1>
            <h2 class="text-2xl font-semibold  text-center sm:text-left">Innovation Lives Here</h2>
            <p class="text-xl mt-5 text-center sm:text-left ">
                Delivering mission-critical communications, cybersecurity <br> and security systems across Saudi Arabia
                for
                over 30 years.
            </p>
        <div class="mt-10 flex flex-col gap-3 md:flex-row md:gap-4">
  
  <NuxtLink to="">
    <button
      class="w-full md:w-auto py-3 px-6 bg-amber-500 hover:bg-amber-600 transition cursor-pointer text-white rounded-sm"
    >
      Our Solutions
    </button>
  </NuxtLink>

  <NuxtLink to="">
    <button
      class="w-full md:w-auto py-3 px-6 border border-white hover:bg-sky-600 hover:border-sky-600 transition cursor-pointer text-white rounded-sm"
    >
      Learn More
    </button>
  </NuxtLink>

</div>

        </div>

    </div>
</template>
