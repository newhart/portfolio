<template>
    <div
        class="relative min-h-screen w-full h-full flex items-center justify-center bg-cover bg-[url('~/assets/image/about.jpg')]">
        <SideBarMenu />
        <div class="content flex flex-col items-start justify-center p-10  bg-opacity-75 rounded-l-full">
            <div class="text-section text-left">
                <h1 class="text-8xl text-white">Bonjour</h1>
                <h2 class="text-3xl text-[#6c305e] font-bold">Je suis Haritiana RANDRIA</h2>
                <h3 class="text-2xl text-white">Développeur Full-Stack</h3>
                <p class="text-lg text-white mt-4">Je suis un développeur full-stack résidant à Madagascar, <br>
                    toujours
                    prêt à me former aux dernières technologies. Mon <br> objectif est de développer <NuxtLink to="/competences"
                        class="highlight text-[#6c305e] underline">mes compétences</NuxtLink> pour <br> pouvoir participer
                    à des
                    projets
                    ambitieux et à la pointe de l'innovation.</p>
            </div>
        </div>
    </div>
</template>

<script setup>
const   navigations  = [
                {
                    index : 1 , 
                    path : '/about'
                },
                {
                    index : 2, 
                    path : '/diplomes'
                }, 
                {
                    index : 3 , 
                    path : '/experiences'
                }, 
                {
                    index : 4 , 
                    path : '/participations'
                }, 
                {
                    index : 5 , 
                    path : '/competances'
                }, 
                {
                    index : 6 , 
                    path : '/realisations'
                }, 
                {
                    index : 7 , 
                    path : '/contact'
                }, 
            ]
const route = useRoute()
</script>

<style scoped>
.content {
    margin-left: 220px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: 20px;
    border-radius: 50px 0 0 50px;
}

.relative {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
}

.text-section {
    flex: 1;
    padding: 20px;
    text-align: left;
}
</style>