<template>
    <div class="min-h-screen bg-black flex">
        <!-- Sidebar Menu -->
        <SideBarMenu />
        <!-- Main Content -->
        <div class="w-3/4 container mx-auto py-6 ml-1/4">
            <h1 class="text-6xl text-white leading-normal mt-4 text-center">Mes Réalisations</h1>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-8">
                <!-- Sorbonne Université -->
                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Sorbonne Université</h2>
                    <p class="mb-4 text-white">Université pluridisciplinaire, de recherche intensive et de rang mondial, située à Paris.</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Intégration page, accueil</li>
                        <li>Affichage dynamique de la page d'accueil</li>
                    </ul>
                    <p class="mb-4 text-white">Wordpress, Bootstrap, Jquery, MySQL</p>
                    <img src="~/assets/image/sary/sorbonne.jpg" alt="Sorbonne Université" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>
                <!-- Le magazine 'Sortez' -->
                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Le magazine 'Sortez'</h2>
                    <p class="mb-4 text-white">Magazine mensuel gratuit diffusé sur les Alpes-Maritimes.</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Intégration page, accueil, magazine, newsletter, agenda</li>
                        <li>Affichage dynamique de la page d'accueil, de l'agenda</li>
                        <li>Fonctionnalité du newsletter</li>
                        <li>CRUD articles</li>
                    </ul>
                    <p class="mb-4 text-white">Bootstrap, CodeIgniter, MySQL</p>
                    <img src="~/assets/image/sary/sortez.jpg" alt="Le magazine 'Sortez'"  class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>
                <!-- Noah Voyages -->
                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Noah Voyages</h2>
                    <p class="mb-4 text-white">Site touristique</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>FRONT Intégration et dynamisation de page (accueil, circuit, réservation), blog, détails circuits, authentification, chat, intégration PDF détails circuits</li>
                        <li>BACK Mise en place API (crud circuit, création de blog, API d'authentification, API de réservation et de paiement, API favoris circuits, API newsletter, info système utilisateur)</li>
                        <li>Mise en place websocket chat</li>
                    </ul>
                    <p class="mb-4 text-white">Laravel</p>
                    <img src="~/assets/image/sary/noah.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <!-- share my hobbies -->
                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">ShareMyHobbies</h2>
                    <p class="mb-4 text-white">Réseau social/ partage de hobbies</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Intégration et dynamisation [page profil, liste d’amis, liste ami bloqué ,page notification, suggestion d’ami, ajout et demande d’ami, appel vidéo API crud profil</li>
                        <li>API liste d’ami’ API notification, ... Mise en place de websocket, appel vidéo</li>
                        <li>Mise en place websocket chat</li>
                    </ul>
                    <p class="mb-4 text-white">Laravel , Ionic Angular , MySQL</p>
                    <img src="~/assets/image/sary/share.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <!-- albert menes -->
                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Albert Menes</h2>
                    <p class="mb-4 text-white">Magasin en ligne</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Correction de prix avec taxe, de design panier, de liste de produits, de total de prix dans un panier</li>
                        <li>Affichage PDF de commande, d’affichage de produit similaire, de doublon de produit</li>
                    </ul>
                    <p class="mb-4 text-white">Prestashop , PHP</p>
                    <img src="~/assets/image/sary/albert.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <!-- Nudacy record -->
                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Nudacy Records</h2>
                    <p class="mb-4 text-white">Plateforme de streaming et de téléchargement</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Conception de base de données, artiste, album Mise en place de création d’album Upload de fichier audio. Gestion album [création, ajout, suppression, modification]</li>
                    </ul>
                    <p class="mb-4 text-white">Laravel , Vue js</p>
                    <img src="~/assets/image/sary/nudacy.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Oxentt-business</h2>
                    <p class="mb-4 text-white">Site de business</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Mise en place de compte utilisateur, avec leur profil Mise en place du système d’authentification, déconnexion, connexion, mdp oublié,...</li>
                        <li>Intégration de page de création de projet Création, suppression, modification des détails de projet Mise en place de la fonctionnalité de participation au projet Mise en place de système de forum de discussion Intégration de page ‘news’ Création, suppression, modification des détails ‘news’ Mise en place de la fonctionnalité de chat de discussion Mise en place de paiement pour la participation au projet.</li>
                        <li>Mise en place websocket chat</li>
                    </ul>
                    <p class="mb-4 text-white">Laravel , vue js</p>
                    <img src="~/assets/image/sary/oxentt.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Your soccer-games</h2>
                    <p class="mb-4 text-white">Site e-commerce vente match video</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Conception de base de données Intégration: page d’accueil, de liste des matchs Fonctionnalité: création, modification, ajout des détails des matchs Mise en place de recherche de système des matchs en utilisant une API de football database Ajout au panier, commande, paiement des matchs Fonctionnalité partenaire</li>
                    </ul>
                    <p class="mb-4 text-white">Laravel</p>
                    <img src="~/assets/image/sary/soccer.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Footbal database</h2>
                    <p class="mb-4 text-white">Plateforme statistique footbal</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Refactorisation de code API de la liste des joueurs Mise en place d’API quiz, score quiz, challenge Mise en place d’API d’information de joueurs, recherche joueurs</li>
                    </ul>
                    <p class="mb-4 text-white">PHP , react</p>
                    <img src="~/assets/image/sary/database.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Sfeira</h2>
                    <p class="mb-4 text-white">Application mobile de football reseaux sociaux</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Correction bug sur la partie quizz Génération question quizz à partir d’API, openAI, chatGPT Intégration quizz conforme a la maquette</li>
                    </ul>
                    <p class="mb-4 text-white">Express js , React js , MongoDb</p>
                    <img src="~/assets/image/sary/sfeira.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Sita news</h2>
                    <p class="mb-4 text-white">Média d'actualité culturelle et artistique axé sur l'Afrique et sa diaspora.
                    </p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Conception de A à Z Intégration de A à Z Développement de A à Z</li>
                    </ul>
                    <p class="mb-4 text-white">Laravel , Bootstrap</p>
                    <img src="~/assets/image/sary/final.jpeg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>

                <div class="p-4 rounded-lg shadow-lg border border-white bg-black relative ">
                    <h2 class="text-2xl font-semibold mb-4 text-[#6c305e]">Lavash travel</h2>
                    <p class="mb-4 text-white">Site web touristique</p>
                    <ul class="list-disc list-inside mb-4 text-white">
                        <li>Intégration page : accueil, circuit Fonctionnalités : création, suppression, ajout et modification de circuit Mise en place de réservation de circuit, paiement</li>
                    </ul>
                    <p class="mb-4 text-white">PHP . Bootstrap , Mysql</p>
                    <img src="~/assets/image/sary/lavash.jpg" alt="Noah Voyages" class="w-32 mx-auto absolute bottom-[-20px] left-[25%]">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import SideBarMenu from '~/components/SideBarMenu.vue';

export default {
    components: {
        SideBarMenu
    }
};
</script>