<template>
    <section class="py-16 px-6 lg:px-20 bg-slate-50">
        <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">

            <div class="relative group">
                <div
                    class="absolute -bottom-6 -left-6 w-full h-full border-2 border-yellow-500 rounded-lg -z-10 hidden md:block">
                </div>

                <img src="/images/about.jpg" alt="About our team"
                    class="rounded-lg shadow-xl object-cover w-full h-[400px] md:h-[500px]">


            </div>

            <div class="space-y-6">
                <div class="flex items-center gap-4 ">

                    <h2 class="text-yellow-600 uppercase tracking-widest font-bold text-2xl">
                        About Us
                    </h2>
                    <span class="h-[3px] w-18 bg-yellow-500"></span>
                </div>

                <h1 class="text-3xl md:text-4xl font-extrabold text-slate-800 leading-tight">
                    Our Hard Work Makes Your <span class="text-yellow-500">Dream Project</span> True Again
                </h1>

                <p class="text-slate-600 text-lg leading-relaxed">
                    Since 1993, Abrar Communications Co. (ACC) has been delivering certified, end-to-end solutions in
                    cybersecurity, air navigation & surveillance, radio communications, security systems, drone &
                    anti-drone technologies, and civil works — supporting critical infrastructure, defense, and
                    enterprise sectors across Saudi Arabia and beyond.

                    With over 30 years of proven expertise, Abrar combines global partnerships with local knowledge to
                    provide mission-critical communications and security solutions. Headquartered in Riyadh, with
                    branches in Jeddah, Dammam, Madinah, and Yanbu, we ensure nationwide project delivery in full
                    compliance with GAMI, HCIS, ISO, and national authority standards.
                </p>



            </div>

        </div>
        <div class="max-w-7xl mx-auto px-5 mt-28">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">

                <!-- Experience Card -->
                <div
                    class="bg-white shadow-lg rounded-lg p-8 flex flex-col items-center text-center transform transition hover:-translate-y-2 hover:shadow-xl">
                    <Icon name="mdi:target-arrow" class="text-8xl text-amber-500 mb-5" />
                    <NuxtLink to="">
                        <h2 class="text-2xl md:text-3xl font-semibold text-slate-800 hover:text-blue-700 transition hover:cursor-pointer">
                            Experience</h2>
                    </NuxtLink>
                    <p class="mt-3 text-slate-700 text-sm md:text-base">Over 30 years delivering mission-critical
                        communications and security solutions.</p>
                </div>

                <!-- Presence Card -->
                <div
                    class="bg-white shadow-lg rounded-lg p-8 flex flex-col items-center text-center transform transition hover:-translate-y-2 hover:shadow-xl">
                    <Icon name="mdi:account-check-outline" class="text-8xl text-amber-500 mb-5" />
                    <NuxtLink to="">
                        <h2 class="text-2xl hover:cursor-pointer md:text-3xl font-semibold text-slate-800 hover:text-blue-700 transition">
                            Presence</h2>
                    </NuxtLink>
                    <p class="mt-3 text-slate-700 text-sm md:text-base">Headquartered in Riyadh with branches in Jeddah,
                        Dammam, Madinah, and Yanbu.</p>
                </div>

                <!-- Partnerships Card -->
                <div
                    class="bg-white shadow-lg rounded-lg p-8 flex flex-col items-center text-center transform transition hover:-translate-y-2 hover:shadow-xl">
                    <Icon name="mdi:handshake" class="text-8xl text-amber-500 mb-5" />
                    <NuxtLink to="">
                        <h2 class="text-2xl hover:cursor-pointer md:text-3xl font-semibold text-slate-800 hover:text-blue-700 transition">
                            Partnerships</h2>
                    </NuxtLink>
                    <p class="mt-3 text-slate-700 text-sm md:text-base">Working with leading international technology
                        providers to integrate best-in-class solutions locally.</p>
                </div>

                <!-- Compliance Card -->
                <div
                    class="bg-white shadow-lg rounded-lg p-8 flex flex-col items-center text-center transform transition hover:-translate-y-2 hover:shadow-xl">
                    <Icon name="mdi:shield-check" class="text-8xl text-amber-500 mb-5" />
                    <NuxtLink to="">
                        <h2 class="text-2xl hover:cursor-pointer md:text-3xl font-semibold text-slate-800 hover:text-blue-700 transition">
                            Compliance</h2>
                    </NuxtLink>
                    <p class="mt-3 text-slate-700 text-sm md:text-base px-2 md:px-0">Delivering projects that meet GAMI,
                        HCIS, ISO, and national authority standards without compromise.</p>
                </div>

            </div>
        </div>
    </section>
</template>

<script setup>

</script>