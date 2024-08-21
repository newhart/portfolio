<template>
    <div class="sidebar-menu flex flex-col items-center justify-center bg-black p-5 rounded-r-full">
            <div v-for="navigation in navigations" :key="navigation.index"
                :class="['flex items-center justify-center rounded-full bg-white text-black mb-2', navigation.path === route.path ? 'w-14 h-14' : 'w-10 h-10']">
                <NuxtLink :to="navigation.path" :class="navigation.path === route.path ? 'bg-[#6c305e] text-white' : ''"
                    class="flex items-center justify-center w-full h-full rounded-full">
                    {{ navigation.index }}
                </NuxtLink>
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
                    path : '/competences'
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
.sidebar-menu {
    position: fixed;
    left: 0;
    top: 0;
    bottom: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: #000;
    padding: 20px;
    border-radius: 0 50px 50px 0;
}

.sidebar-menu::after {
    content: '';
    position: absolute;
    right: -10px;
    top: 0;
    bottom: 0;
    width: 2px;
    background: linear-gradient(to bottom, transparent, rgba(255, 255, 255, 0.5), transparent);
    clip-path: ellipse(50% 100% at 100% 50%); /* Courbe en utilisant ellipse */
    border-radius: 50%;
}
</style>