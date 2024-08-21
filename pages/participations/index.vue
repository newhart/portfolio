<template>
    <div class="grid grid-cols-5 grid-rows-5 gap-4 min-h-screen bg-cover bg-center bg-[url('~/assets/image/participation.jpg')]">
     <div class="row-span-5">
         <SideBarMenu />
     </div>
     <div class="col-span-2 row-span-5">
         <h1 class="text-6xl text-white leading-normal">PARTICIPATIONS</h1>
         <img src="~/assets/image/tech/maxresdefault.jpg" alt="" class="my-4" width="400" height="400" >
                 <h2 class="text-3xl text-[#6c305e] font-bold">DEVFEST</h2>
                 <p class="text-sm text-white">
                    Antananarivo 2019 <br>
                    Evènement organisé par GDG Madagascar <br>
                    sur le développement informatique <br>
                    à Madagascar
                 </p>
     </div>
     <div class="col-span-2 row-span-5 col-start-4 py-28">
        <div class="ml-28 mt-4">
          <div>
            <h2 class="text-3xl text-[#6c305e] font-bold">CREATHON</h2>
                 <p class="text-sm text-white">
                    Antananarivo 2019  <br>
                    Concours mondial sur la technologie <br>
                    sur le thème, “aides aux handicapés dans l’éducation”
                 </p>
          </div>
                 <img src="~/assets/image/tech/2.jpg" alt="" width="200" height="200" >
        </div>
     </div>

     <div class="col-span-5 flex justify-center space-x-16 relative mt[-20%]" >
        <h1 class="text-xl text-white stages relative">STAGES</h1>
        <div class="ml-5">
            <h2 class="text-3xl text-[#6c305e] font-bold">STAGIAIRE/DEVELOPPEUR WEB</h2>
                 <p class="text-sm text-white">   
                    RANDEV TEAM, Antananarivo 2019-2020 <br>
                    ·Développeur backend sous laravel . <br>
                    ·CMS wordpress , prestashop <br>
                    ·Développeur frontend React js
                 </p>
        </div>
     </div>
   </div>
 </template>
 
 <script setup>
 </script>

 <style scoped>
 .stages::after {
    content: '';
    height: 110px;
    width: 15px;
    background-color: #6c305e;
    position: absolute;
    right: -45px;
 }
</style>
 