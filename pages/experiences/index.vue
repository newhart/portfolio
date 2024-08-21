<template>
    <div class="grid grid-cols-5 grid-rows-5 gap-4 min-h-screen bg-cover bg-center bg-[url('~/assets/image/experiances.jpg')]">
     <div class="row-span-5">
         <SideBarMenu />
     </div>
     <div class="col-span-2 row-span-5">
         <h1 class="text-8xl text-white leading-normal">Expériences</h1>
         <div class="max-w-4xl mx-auto p-6">
            <!-- Expérience 1 -->
            <div class="flex flex-col md:flex-row md:items-center mb-8">
                <!-- Année -->
                <div class="w-full md:w-1/4 mb-4 md:mb-0">
                <span class="block text-lg font-light text-[#6c305e]">2023-2024</span>
                </div>
                <!-- Contenu -->
                <div class="w-full md:w-3/4">
                <h3 class="text-xl font-semibold text-[#6c305e]">BIGDEV Company</h3>
                <p class="mt-2 text-white">
                    <span class="font-bold">DEVELOPPEUR FULL STACK SENIOR</span> <br>
                    Développeur application lourde. <br>
                    Développeur application mobile. <br>
                    Lead développeur
                </p>
                </div>
            </div>

            <!-- Expérience 2 -->
            <div class="flex flex-col md:flex-row md:items-center mb-8">
                <!-- Année -->
                <div class="w-full md:w-1/4 mb-4 md:mb-0">
                <span class="block text-lg font-light text-[#6c305e]">2022-2023</span>
                </div>
                <!-- Contenu -->
                <div class="w-full md:w-3/4">
                <h3 class="text-xl font-semibold text-[#6c305e]">CREA Agency</h3>
                <p class="mt-2 text-white">
                    <span class="font-bold">DEVELOPPEUR FULL STACK</span> <br>
                    Développeur web <br>
                    Développeur application mobile. <br>
                    Lead développeur
                </p>
                </div>
            </div>

            <!-- Expérience 3 -->
            <div class="flex flex-col md:flex-row md:items-center mb-8">
                <!-- Année -->
                <div class="w-full md:w-1/4 mb-4 md:mb-0">
                <span class="block text-lg font-light text-[#6c305e]">2021-2022</span>
                </div>
                <!-- Contenu -->
                <div class="w-full md:w-3/4">
                <h3 class="text-xl font-semibold text-[#6c305e]">MKWEBLINKS</h3>
                <p class="mt-2 text-white">
                    <span class="font-bold">DEVELOPPEUR FULL STACK</span> <br>
                        Développeur backend sous laravel.  <br>
                        Développeur frontend sous nuxt js <br>
                        Lead développeur conseil technique.  <br>
                        Développeur application mobile sous ionic angular.
                </p>
                </div>
            </div>
        </div>
    </div>
     <div class="col-span-2 row-span-5 col-start-4 py-28">
         <img src="~/assets/image/code1.jpg" width="400" height="200" alt="">
         <div class="flex">
            <img src="~/assets/image/code2.jpg" class="mt-9 ml-24" width="400" height="200" alt="">
        </div>
     </div>
   </div>
 </template>
 
 <script setup>
 </script>