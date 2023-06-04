<template>
    <main>

        <!-- Hero section -->
        <div class="relative">
            
            <NavBar/>
        
            <img src="../assets/images/cpf-hero.jpg" class="absolute inset-0 object-cover w-full h-full" alt="" />
        
            <div class="absolute top-0 w-full h-full bg-black bg-opacity-50"></div>
        
            <div class="relative bg-opacity-75 bg-deep-purple-accent-700">
                <svg class="absolute inset-x-0 md:-bottom-2 -bottom-1 text-white" viewBox="0 0 1160 163">
                <path fill="currentColor" d="M-164 13L-104 39.7C-44 66 76 120 196 141C316 162 436 152 556 119.7C676 88 796 34 916 13C1036 -8 1156 2 1216 7.7L1276 13V162.5H1216C1156 162.5 1036 162.5 916 162.5C796 162.5 676 162.5 556 162.5C436 162.5 316 162.5 196 162.5C76 162.5 -44 162.5 -104 162.5H-164V13Z"></path>
                </svg>
                <div class="relative px-4 py-16 mx-auto overflow-hidden sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
                <div class="flex lg:ml-6 md:ml-0 flex-col items-center justify-between xl:flex-row">
                    <div class="w-full h-[350px] lg:max-w-xl mb-12 xl:mb-0 xl:pr-16 xl:w-7/12">
                        <h2 class="max-w-2xl mb-14 font-sans md:text-5xl text-4xl font-bold tracking-tight text-white sm:text-4xl sm:leading-none">
                            Volontaires pour la Protection de la <span class="text-green-600">Faune et Flore</span>
                        </h2>
                        <p class="max-w-xl mb-4 text-base text-gray-200 md:text-lg">
                            Si vous êtes une personne qui soutient nos idées et qui veut apporter sa plus grande contribution, nous vous souhaitons la bienvenue !
                        </p>
                        <a href="/" aria-label="" class="inline-flex items-center font-semibold tracking-wider transition-colors duration-200 text-green-400 hover:text-teal-accent-700">
                            Faire un don
                            <svg class="inline-block w-3 ml-2" fill="currentColor" viewBox="0 0 12 12">
                            <path d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"></path>
                            </svg>
                        </a>
                    </div>
                </div>
                </div>
            </div>
        
        </div>

        <!-- Mision, Vision and Domain section -->
        <section class="md:flex relative md:ml-0 -ml-1.5 lg:space-x-28 md:space-x-3 md:space-y-0 space-y-10 justify-center md:-mt-16 -mt-32">
            <div class="w-80 h-72 px-5 bg-slate-50 rounded-lg shadow-md hover:scale-105 duration-300 hover:border border-green-500 cursor-default md:mx-0 mx-auto">
                <div class="w-20 h-20 mx-auto">
                    <img src="../assets/images/mission.png" alt="" srcset="">
                </div>
                <h3 class="text-center text-2xl pt-8 pb-5 font-semibold">Notre Mission</h3>
                <p class="text-center font-thin text-sm">
                    Nous contibuons à la protection de la flore et plus particulièrement les especes intégralement et partiellemnt protégées.
                </p>
            </div>
            <div class="w-80 h-72 px-5 bg-slate-50 rounded-lg shadow-md hover:scale-105 duration-300 hover:border border-green-500 cursor-default md:mx-0 mx-auto">
                <div class="w-28 h-28 mx-auto">
                    <img src="../assets/images/vision.png" alt="" srcset="">
                </div>
                <h3 class="text-center text-2xl pb-5 font-semibold">Notre Vision</h3>
                <p class="text-center font-thin text-sm">
                    Nous contibuons à la protection de la flore et plus particulièrement les especes intégralement et partiellemnt protégées.
                </p>
            </div>
            <div class="w-80 h-72 px-5 bg-slate-50 rounded-lg shadow-md hover:scale-105 duration-300 hover:border border-green-500 cursor-default md:mx-0 mx-auto">
                <div class="w-16 h-16 mx-auto my-4">
                    <img src="../assets/images/field.png" alt="" srcset="">
                </div>
                <h3 class="text-center text-2xl pb-3 font-semibold truncate">Domaine d'intervation</h3>
                <ul class="font-thin text-xs space-y-1">
                    <li class="flex space-x-2 items-center">
                        <span class="w-4 h-4">
                            <img class="w-4 h-4" src="../assets/images/check.png" alt="" srcset="">
                        </span>
                        <span>Protection de la Faune et Flore</span>
                    </li> 
                    <li class="flex space-x-2 items-center">
                        <span class="w-4 h-4">
                            <img class="w-4 h-4" src="../assets/images/check.png" alt="" srcset="">
                        </span>
                        <span>Environnement de la Faune et Flore</span> 
                    </li>
                    <li class="flex space-x-2">
                        <span class="w-10 h-4">
                            <img class="w-10 h-4" src="../assets/images/check.png" alt="" srcset="">
                        </span>
                        <span>Transformantion des conflits par la méthode non violente active et mode de gestion pacifique autour des protégées.</span>
                    </li>
                    <li class="flex space-x-2">
                        <span class="w-5 h-4">
                            <img class="w-5 h-4" src="../assets/images/check.png" alt="" srcset="">
                        </span>
                        <span>Gouvernance participative des aires et espèces protégées.</span>
                    </li>
                </ul>
            </div>
        </section>

        <!-- Services section -->
        <section class="pt-16 md:pb-24 pb-10 relative">
            <svg class="absolute inset-x-0 md:-bottom-2 -bottom-1 text-green-50" viewBox="0 0 1160 163">
                <path fill="currentColor" d="M-164 13L-104 39.7C-44 66 76 120 196 141C316 162 436 152 556 119.7C676 88 796 34 916 13C1036 -8 1156 2 1216 7.7L1276 13V162.5H1216C1156 162.5 1036 162.5 916 162.5C796 162.5 676 162.5 556 162.5C436 162.5 316 162.5 196 162.5C76 162.5 -44 162.5 -104 162.5H-164V13Z"></path>
                </svg>
            <div class="text-green-950">
                <h2 class="md:text-4xl text-3xl text-center">Bienvenue !</h2>
                <p class="mx-auto my-4 lg:px-80 md:px-28 px-4 md:text-base text-center text-sm">
                    Nous nous engageons à protéger la Faune et Flore et à améliorer notre environnement
                </p>
            </div>

            <div class="w-full md:flex md:space-x-6 md:space-y-0 space-y-6 md:py-12 py-8 lg:px-16 md:px-3 px-4">
                <div class="md:w-1/3 w-full lg:flex md:block flex lg:border-0 md:border border-0 lg-0 md:p-5 p-0 lg:text-left md:text-center text-left justify-center space-x-2 hover:scale-105 duration-300 cursor-default">

                    <img class="md:h-20 h-16 w-auto lg:mx-0 md:mx-auto mx-0 bg-green-500 p-2 pt-2.5 rounded-full" src="../assets/images/community.png" alt="" srcset="">
                    
                    <div>
                        <h2 class="lg:text-2xl text-base font-semibold mb-1.5 lg:my-0 md:my-5 my-0 truncate">Une Grande Communauté</h2>
                        <p class="font-thin text-xs text-justify">
                            Nous impliquons plus de personnes dans nos projets et activités pour faire connaître notre organisation. Nous défendons l'expansion de notre activité dans le monde entier pour protéger notre planète.
                        </p>
                    </div>
                </div>
                <div class="md:w-1/3 w-full lg:flex md:block flex lg:border-0 md:border border-0 lg-0 md:p-5 p-0 lg:text-left md:text-center text-left justify-center space-x-2 hover:scale-105 duration-300 cursor-default">
                    
                    <img class="md:h-20 h-16 w-auto lg:mx-0 md:mx-auto mx-0 bg-yellow-500 p-3 pt-3.5 rounded-full" src="../assets/images/project.png" alt="" srcset="">
                    
                    <div>
                        <h2 class="lg:text-2xl text-base font-semibold mb-1.5 lg:my-0 md:my-5 my-0 truncate">De Nombreux Projets</h2>
                        <p class="font-thin text-xs text-justify">Nous travaillons constamment à promouvoir nos projets et à y impliquer davantage de personnes. Nous croyons que notre force réside dans notre cohésion et nos efforts conjoints.</p>
                    </div>
                </div>
                <div class="md:w-1/3 w-full lg:flex md:block flex lg:border-0 md:border border-0 lg-0 md:p-5 p-0 lg:text-left md:text-center text-left justify-center space-x-2 hover:scale-105 duration-300 cursor-default">
                    
                    <img class="md:h-20 h-16 w-auto lg:mx-0 md:mx-auto mx-0 bg-cyan-600 p-2 rounded-full" src="../assets/images/donation.png" alt="" srcset="">
                    
                    <div>
                        <h2 class="lg:text-2xl text-base font-semibold mb-1.5 lg:my-0 md:my-5 my-0 truncate">Donation</h2>
                        <p class="font-thin text-xs text-justify">Vous pouvez soutenir n'importe laquelle de nos campagnes par votre participation personnelle ou tout don.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects section -->
        <section class="pt-16 md:pb-40 pb-10 relative bg-green-50">
            <svg class="absolute z-10 inset-x-0 md:-bottom-2 -bottom-1 text-white" viewBox="0 0 1160 163">
                <path fill="currentColor" d="M-164 13L-104 39.7C-44 66 76 120 196 141C316 162 436 152 556 119.7C676 88 796 34 916 13C1036 -8 1156 2 1216 7.7L1276 13V162.5H1216C1156 162.5 1036 162.5 916 162.5C796 162.5 676 162.5 556 162.5C436 162.5 316 162.5 196 162.5C76 162.5 -44 162.5 -104 162.5H-164V13Z"></path>
                </svg>
            <div class="text-green-950">
                <h2 class="md:text-4xl text-3xl text-center">Nos projets reçent</h2>
                <p class="mx-auto my-4 lg:px-80 md:px-28 px-4 md:text-base text-center text-sm">
                    Chaque personne peut participer à notre événement caritatif. Nous apprécions votre impact sur nos projets et apprécions votre aide.
                </p>
            </div>

            <div class="w-full z-50 md:flex md:space-x-6 md:space-y-0 space-y-6 md:py-12 py-8 lg:px-20 md:px-3 px-4">
                <div class="md:w-1/3 shadow-lg w-full lg:flex md:block flex rounded-lg bg-slate-100 hover:scale-105 hover:-translate-y-5 duration-300">

                    <img class="h-36 m-1 lg:w-52 md:w-full w-36 object-cover rounded-lg" src="../assets/images/proj.png" alt="" srcset="">

                    <div class="p-2">
                        <h2 class="text-lg font-semibold">Titre du projet</h2>
                        <p class="text-xs text-justify font-thin my-2">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur sint, a quisquam vitae ipsam quaerat?
                        </p>
                        <a class="text-xs text-green-600 cursor-pointer hover:underline" href="#">Lire plus...</a>
                    </div>

                </div>
                <div class="md:w-1/3 shadow-lg w-full lg:flex md:block flex rounded-lg bg-slate-100 hover:scale-105 hover:-translate-y-5 duration-300">

                    <img class="h-36 m-1 lg:w-52 md:w-full w-36 object-cover rounded-lg" src="../assets/images/proj.png" alt="" srcset="">

                    <div class="p-2">
                        <h2 class="text-lg font-semibold">Titre du projet</h2>
                        <p class="text-xs text-justify font-thin my-2">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur sint, a quisquam vitae ipsam quaerat?
                        </p>
                        <a class="text-xs text-green-600 cursor-pointer hover:underline" href="#">Lire plus...</a>
                    </div>

                </div>
                <div class="md:w-1/3 shadow-lg w-full lg:flex md:block flex rounded-lg bg-slate-100 hover:scale-105 hover:-translate-y-5 duration-300">

                    <img class="h-36 m-1 lg:w-52 md:w-full w-36 object-cover rounded-lg" src="../assets/images/proj.png" alt="" srcset="">

                    <div class="p-2">
                        <h2 class="text-lg font-semibold">Titre du projet</h2>
                        <p class="text-xs text-justify font-thin my-2">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur sint, a quisquam vitae ipsam quaerat?
                        </p>
                        <a class="text-xs text-green-600 cursor-pointer hover:underline" href="#">Lire plus...</a>
                    </div>

                </div>
            </div>

        </section>


        <!-- About section -->
        <section class="pt-16 md:pb-28 pb-16 relative bg-white">
            <svg class="absolute z-10 inset-x-0 md:-bottom-2 -bottom-1 text-green-50" viewBox="0 0 1160 163">
                <path fill="currentColor" d="M-164 13L-104 39.7C-44 66 76 120 196 141C316 162 436 152 556 119.7C676 88 796 34 916 13C1036 -8 1156 2 1216 7.7L1276 13V162.5H1216C1156 162.5 1036 162.5 916 162.5C796 162.5 676 162.5 556 162.5C436 162.5 316 162.5 196 162.5C76 162.5 -44 162.5 -104 162.5H-164V13Z"></path>
                </svg>
            <div class="text-green-950">
                <h2 class="md:text-4xl text-3xl text-center">Quelques mots sur nous</h2>
                <p class="mx-auto my-4 lg:px-80 md:px-28 px-4 md:text-base text-center text-sm">
                    Lisez dans petit paragraphe un bref description de qui nous sommes et pourquoi nous sommes tant motivez de faire ce que nous faisons. 
                </p>
            </div>

            <div class="w-full hover:scale-95 duration-300 z-50 md:flex items-start md:space-x-6 md:space-y-0 space-y-6 md:py-12 py-8 lg:px-20 md:px-3 px-4">
                <img class="lg:h-80 h-full lg:w-auto md:w-full w-auto" src="../assets/images/proj.png" alt="" srcset="">
                <div>
                    <h1 class="text-xl font-semibold text-green-800">À Propos</h1>
                    <p class="mt-5 mb-10 font-thin text-justify">
                        Nous impliquons plus de personnes dans nos projets et activités pour faire connaître notre organisation. Nous défendons l'expansion de notre activité dans le monde entier pour protéger notre planète.
                        Nous travaillons constamment à promouvoir nos projets et à y impliquer davantage de personnes. Nous croyons que notre force réside dans notre cohésion et nos efforts conjoints.
                        De nos jours, le monde technogénique nuit beaucoup à notre planète. Nous travaillons à minimiser son influence et espérons pouvoir sauver notre nature pendant des siècles.
                        Nous apprécions chaque personne et nous nous efforçons d'aider tous ceux qui en ont besoin. Des millions de personnes luttent contre la faim, les maladies et les actions militaires. Nous mettons des efforts pour les aider.
                    </p>
                    <a class="hover:underline py-2 px-4 rounded-md hover:bg-green-600 bg-green-800 text-white text-sm" href="#!">
                        Lire plus
                    </a>
                </div>
            </div>

            <section >
                <div class="text-green-950 py-12">
                    <h2 class="md:text-4xl text-3xl text-center">Nous contacter</h2>
                    <p class="mx-auto my-4 lg:px-80 md:px-28 px-4 md:text-base text-center text-sm">
                        N'hésitez pas à nous contacter à tout moment et à poser toutes vos questions. Nous sommes toujours ouverts à toutes suggestions et collaborations.
                    </p>
                </div>

                <form action="" class="lg:px-20 md:px-0 px-4  md:flex md:space-x-10 justify-center">
                    <div class="space-y-6">
                        <fieldset>
                            <input type="text" class="border rounded-md md:w-96 w-full h-11 px-3" placeholder="Notre nom">
                        </fieldset>
                        <fieldset>
                            <input type="text" class="border rounded-md md:w-96 w-full h-11 px-3" placeholder="Sujet">
                        </fieldset>
                        <fieldset>
                            <input type="email" class="border rounded-md md:w-96 w-full h-11 px-3" placeholder="Email">
                        </fieldset>
                    </div>
                    <div class="block space-y-6 text-left md:mt-0 mt-6">
                        <textarea name="" id="" cols="60" rows="6" class="border block rounded-md md:w-96 w-full h-28 p-3" placeholder="Message"></textarea>
                        <button class="py-2 px-6 bg-green-700 hover:bg-green-500 text-white rounded-md">Envoyer</button>
                    </div>
                </form>
            </section>

        </section>

        <!-- Footer container -->
        <footer id="footer" class="bg-green-50 text-center text-neutral-600 dark:bg-neutral-600 dark:text-neutral-200 lg:text-left">

            <!-- Main container div: holds the entire content of the footer, including four sections (Tailwind Elements, Products, Useful links, and Contact), with responsive styling and appropriate padding/margins. -->
            <div class="mx-6 pb-10 pt-3 text-left">
                <div class="md:flex space-y-8 md:space-y-0">
                    <!-- Products section -->
                    <div class="md:w1/3 w-full">
                    <h6
                        class="mb-4 flex font-semibold uppercase">
                        Navigations
                    </h6>
                    <p class="mb-4">
                        <a href="#hero" class="text-neutral-600 dark:text-neutral-200 hover:underline"
                        >Accueil</a
                        >
                    </p>
                    <p class="mb-4">
                        <a href="#activity" class="text-neutral-600 dark:text-neutral-200 hover:underline"
                        >Services</a
                        >
                    </p>
                    <p class="mb-4">
                        <a href="#about" class="text-neutral-600 dark:text-neutral-200 hover:underline"
                        >Projets</a
                        >
                    </p>
                    <p class="mb-4">
                        <a href="#contact" class="text-neutral-600 dark:text-neutral-200 hover:underline"
                        >À propos</a
                        >
                    </p>
                    </div>
                    <!-- Contact section -->
                    <div class="md:w1/3 w-full">
                        <h6 class="mb-4 flex font-semibold uppercase "> Contact </h6>
                        <p class="mb-4 flex items-center md:justify-start ">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="mr-3 h-5 w-6">
                                <path d="M11.47 3.84a.75.75 0 011.06 0l8.69 8.69a.75.75 0 101.06-1.06l-8.689-8.69a2.25 2.25 0 00-3.182 0l-8.69 8.69a.75.75 0 001.061 1.06l8.69-8.69z" />
                                <path d="M12 5.432l8.159 8.159c.03.03.06.058.091.086v6.198c0 1.035-.84 1.875-1.875 1.875H15a.75.75 0 01-.75-.75v-4.5a.75.75 0 00-.75-.75h-3a.75.75 0 00-.75.75V21a.75.75 0 01-.75.75H5.625a1.875 1.875 0 01-1.875-1.875v-6.198a2.29 2.29 0 00.091-.086L12 5.43z" />
                            </svg>
                            Bunia ville, Ituri, R.D.Congo
                        </p>
                        <p class="mb-4 flex items-center md:justify-start">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="mr-3 h-5 w-5">
                                <path d="M1.5 8.67v8.58a3 3 0 003 3h15a3 3 0 003-3V8.67l-8.928 5.493a3 3 0 01-3.144 0L1.5 8.67z" />
                                <path d="M22.5 6.908V6.75a3 3 0 00-3-3h-15a3 3 0 00-3 3v.158l9.714 5.978a1.5 1.5 0 001.572 0L22.5 6.908z" />
                            </svg>
                            contact@vpf.com
                        </p>
                        <p class="mb-4 flex items-center md:justify-start"> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="mr-3 h-5 w-5">
                            <path fill-rule="evenodd" d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z"
                                clip-rule="evenodd" />
                            </svg>
                            +243 997057917
                        </p>
                        <p class="flex items-center md:justify-start">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="mr-3 h-5 w-5">
                                <path fill-rule="evenodd" d="M7.875 1.5C6.839 1.5 6 2.34 6 3.375v2.99c-.426.053-.851.11-1.274.174-1.454.218-2.476 1.483-2.476 2.917v6.294a3 3 0 003 3h.27l-.155 1.705A1.875 1.875 0 007.232 22.5h9.536a1.875 1.875 0 001.867-2.045l-.155-1.705h.27a3 3 0 003-3V9.456c0-1.434-1.022-2.7-2.476-2.917A48.716 48.716 0 0018 6.366V3.375c0-1.036-.84-1.875-1.875-1.875h-8.25zM16.5 6.205v-2.83A.375.375 0 0016.125 3h-8.25a.375.375 0 00-.375.375v2.83a49.353 49.353 0 019 0zm-.217 8.265c.178.018.317.16.333.337l.526 5.784a.375.375 0 01-.374.409H7.232a.375.375 0 01-.374-.409l.526-5.784a.373.373 0 01.333-.337 41.741 41.741 0 018.566 0zm.967-3.97a.75.75 0 01.75-.75h.008a.75.75 0 01.75.75v.008a.75.75 0 01-.75.75H18a.75.75 0 01-.75-.75V10.5zM15 9.75a.75.75 0 00-.75.75v.008c0 .414.336.75.75.75h.008a.75.75 0 00.75-.75V10.5a.75.75 0 00-.75-.75H15z" clip-rule="evenodd" />
                            </svg>
                            +243 811572916
                        </p>
                    </div>

                    <!-- Social network icons container -->
                    <div class="md:w1/3 w-full">
                        <h6 class="mb-4 flex font-semibold uppercase "> Réseaux sociaux </h6>
                        <div class="flex">
                            <a href="#!" class="mr-6 text-neutral-600 dark:text-neutral-200">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z" />
                                </svg>
                            </a>
                            <a href="#!" class="mr-6 text-neutral-600 dark:text-neutral-200">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
                                </svg>
                            </a>
                            <a href="#!" class="mr-6 text-neutral-600 dark:text-neutral-200">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z" />
                                </svg>
                            </a>
                            <a href="#!" class="mr-6 text-neutral-600 dark:text-neutral-200">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.38 1.11-2.5 2.48-2.5s2.48 1.12 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.968v16h4.969v-8.399c0-4.67 6.029-5.052 6.029 0v8.399h4.988v-10.131c0-7.88-8.922-7.593-11.018-3.714v-2.155z" />
                                </svg>
                            </a>
                        </div>
                        <div class="flex flex-col justify-between mt-3 -pt-12 -mb-5 border-t-2">
                            <div class="w-full ">
                                <h1 class="text-2xl md:text-xl xl:text-2xl font-semibold leading-10 text-gray-800 dark:text-white mb-3 xl:text-left md:mt-0 mt-4">S'abonner</h1>
                                <p class="text-sm leading-normal text-gray-600 dark:text-gray-200 text-center xl:text-left">S'abonner à notre news letter pour être notifier à chaque fois qu'une nouvelle est au rendez-vous !</p>
                                <div class="flex mt-6">
                                    <input class="bg-gray-300 rounded-l-full h-11 rounded-r-none dark:bg-gray-800 text-base leading-none text-gray-800 dark:text-white px-5 w-4/5 border border-transparent focus:outline-none focus:border-gray-500" type="email" placeholder="Your Email" />
                                    <button class="w-32 rounded-l-none hover:bg-green-600 bg-green-700 rounded-r-full text-base font-medium leading-none text-white px-5 py-2 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-700">S'abonner</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!--Copyright section-->
            <div class="bg-green-100 p-6 text-center text-sm dark:bg-neutral-700">
                <span>© 2023 Copyright cpf - </span>
                <a class="font-semibold text-neutral-600 dark:text-neutral-400" href="#"> nkayisi Design</a>
            </div>

        </footer>

    </main>
</template>

<script setup>

</script>
