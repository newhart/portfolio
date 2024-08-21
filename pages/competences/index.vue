<template>
    <div class="min-h-screen bg-black flex">
        <SideBarMenu />
        <div class="w-3/4 container mx-auto py-6 ml-1/4">
            <h1 class="text-6xl text-white leading-normal mt-4 animate-fade-in">COMPÉTENCES</h1>
            <p class="text-white animate-fade-in">Je suis un développeur proactif, toujours à l'affût des dernières tendances en matière de développement, que ce soit pour les applications web, mobiles ou autres.</p>
            <div class="grid grid-cols-5 gap-4 mt-4">
                <a href="#" class="flex flex-col items-center cursor-pointer hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/4.jpg" alt="Vue.js" width="150" height="150">
                    <span class="mt-2 text-white">Github</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/6.jpg" alt="Visual" width="150" height="150">
                    <span class="mt-2 text-white">Visual Studio Code</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/8.jpg" alt="PostgressSql" width="150" height="150">
                    <span class="mt-2 text-white">PostgressSQL</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/9.jpg" alt="Mysql" width="150" height="150">
                    <span class="mt-2 text-white">MySQL</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/21.jpg" alt="=Laravel" width="150" height="150">
                    <span class="mt-2 text-white">Laravel</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/32.jpg" alt="Vue" width="150" height="150">
                    <span class="mt-2 text-white">Vue js</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/17.jpg" alt="Nuxt js" width="150" height="150">
                    <span class="mt-2 text-white">Nuxt js</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/18.jpg" alt="Adonis" width="150" height="150">
                    <span class="mt-2 text-white">Adonis js</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/19.jpg" alt="Adonis" width="150" height="150">
                    <span class="mt-2 text-white">Symfony</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/23.jpg" alt="Adonis" width="150" height="150">
                    <span class="mt-2 text-white">Python</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/29.jpg" alt="React" width="150" height="150">
                    <span class="mt-2 text-white">React js</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/12.jpg" alt="Angular" width="150" height="150">
                    <span class="mt-2 text-white">Angular</span>
                </a>
                <a href="#" class="flex flex-col items-center hover:scale-105 transition-transform duration-300">
                    <img src="~/assets/image/tech/10.jpg" alt="codeIgniter" width="150" height="150">
                    <span class="mt-2 text-white">CodeIgniter</span>
                </a>
            </div>
        </div>
    </div>
</template>

<style scoped>
@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}

.animate-fade-in {
    animation: fadeIn 3s ease-in-out;
}
</style>