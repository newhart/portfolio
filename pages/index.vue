<template>
    <div class="bg-[url('~/assets/image/main.jpg')] bg-cover bg-center relative min-h-screen w-full h-full flex justify-center items-center">
        <div class="flex flex-col items-center justify-center h-full text-white absolute left-1/2 transform -translate-x-1/2 leading-tight">
            <h1 class="font-bold font-oswald leading-tight letter text-4xl sm:text-5xl md:text-6xl">
                PORTFOLIO
            </h1>
            <h2 class="text-4xl sm:text-5xl md:text-6xl font-oswald leading-tight letter">
                Haritiana
            </h2>
            <h2 class="text-4xl sm:text-5xl md:text-6xl font-oswald leading-tight letter randria relative">
                RANDRIA
            </h2>
            <p class="text-lg sm:text-xl mt-4 text-[#6c305e] italic">Développeur Full-Stack</p>
        </div>
        <div class="absolute bottom-10 right-10 sm:right-20 md:right-28">
            <NuxtLink to="/about" class="flex items-center justify-center gap-4">
                <img src="~/assets/image/white.svg" class="w-10 h-10 text-white fill-current" alt="Description de l'image">
                <div class="text-lg sm:text-xl font-bold text-white text-wrapper">
                    <span class="typewriter">Apprendre plus <br> à mon sujet ?</span>
                </div>
            </NuxtLink>
        </div>
    </div>
</template>

<script setup>
const { $anime } = useNuxtApp();

onMounted(() => {
    $anime.timeline()
    .add({
      targets: '.letter',
      translateY: [-100, 0],
      opacity: [0, 1],
      scale: [0.5, 1],
      easing: "easeOutBounce",
      duration: 1200,
      delay: (el, i) => 100 * i
    });

    $anime.timeline({loop: true})
            .add({
                targets: '.letter-detail',
                opacity: [0, 1],
                easing: "easeInOutQuad",
                duration: 200,
                delay: (el, i) => 100 * i
            }).add({
                targets: '.text-wrapper',
                opacity: [1, 0],
                duration: 1000,
                easing: "easeOutExpo",
                delay: 1000
            });
    
    $anime.timeline({loop: false}) 
    .add({
        targets: '.typewriter .letter',
        opacity: [0, 1], 
        easing: "easeInOutQuad",
        duration: 150,
        delay: (el, i) => 150 * (i + 1)
    });
});
</script>

<style scoped>
.randria::after {
   content: '';
   background-color: #6c305e;
   width: 50%;
   height: 10%;
   position: absolute;
   top: 0;
   right: 0;
   transform: rotate(5deg);
}
</style>