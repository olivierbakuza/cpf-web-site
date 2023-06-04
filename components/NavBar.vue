<template>
    <!-- Main navigation container -->
    <nav class="flex-no-wrap relative z-40 flex w-full items-center justify-between py-2 shadow-md shadow-black/5 dark:bg-neutral-600 dark:shadow-black/10 lg:flex-wrap lg:justify-start lg:py-4" data-te-navbar-ref>
        <div class="flex w-full flex-wrap items-center justify-between md:px-20 px-2">
            <!-- Logo -->
            <a class="mb-4 mt-3 md:ml-5 ml-2 flex items-center text-neutral-900 hover:text-neutral-900 focus:text-neutral-900 dark:text-neutral-200 dark:hover:text-neutral-400 dark:focus:text-neutral-400 lg:mb-0 lg:mt-0" href="#">
                <img src="../assets/images/logo-vpf.png" style="height: 55px" alt="" loading="lazy" />
            </a>

            <!-- Collapsible navigation container -->
            <div class="!visible hidden text-right flex-grow basis-[100%] items-center lg:!flex lg:basis-auto" id="navbarSupportedContent1" data-te-collapse-item>
            
                <!-- Left navigation links -->
                <ul class="list-style-none ml-auto flex flex-col pl-0 lg:flex-row" data-te-navbar-nav-ref>
                    <li class="mb-4 lg:mb-0 lg:pr-4" data-te-nav-item-ref>
                        <!-- Home link -->
                        <a class="text-white hover:text-green-500 focus:text-green-500 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 lg:px-2 [&.active]:text-black/90 dark:[&.active]:text-zinc-400" href="#" data-te-nav-link-ref>
                            Accueil
                        </a>
                    </li>
                    <!-- Services link -->
                    <li class="mb-4 lg:mb-0 lg:pr-4" data-te-nav-item-ref>
                        <a class="text-white hover:text-green-500 focus:text-green-500 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 lg:px-2 [&.active]:text-black/90 dark:[&.active]:text-neutral-400" href="#" data-te-nav-link-ref>
                            Services
                        </a>
                    </li>
                    <!-- Projects link -->
                    <li class="mb-4 lg:mb-0 lg:pr-4" data-te-nav-item-ref>
                        <a class="text-white hover:text-green-500 focus:text-green-500 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 lg:px-2 [&.active]:text-black/90 dark:[&.active]:text-neutral-400" href="#" data-te-nav-link-ref>
                            Projects
                        </a>
                    </li>
                    <!-- About link -->
                    <li class="mb-4 lg:mb-0 lg:pr-4" data-te-nav-item-ref>
                        <a class="text-white hover:text-green-500 focus:text-green-500 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 lg:px-2 [&.active]:text-black/90 dark:[&.active]:text-neutral-400" href="#" data-te-nav-link-ref>
                            À Propos
                        </a>
                    </li>
                </ul>

            </div>

            <!-- Hamburger button for mobile view -->
            <button class="block text-right border-0 bg-transparent px-2 text-neutral-500 hover:no-underline hover:shadow-none focus:no-underline focus:shadow-none focus:outline-none focus:ring-0 dark:text-neutral-200 lg:hidden"
            type="button"
            data-te-collapse-init
            data-te-target="#navbarSupportedContent1"
            aria-controls="navbarSupportedContent1"
            aria-expanded="false"
            aria-label="Toggle navigation">
            <!-- Hamburger icon -->
            <span class="[&>svg]:w-12">
                <svg viewBox="0 0 32 32" class="fill-white hover:fill-green-700" xmlns="http://www.w3.org/2000/svg"><defs></defs><title/><g id="List"><path class="cls-1" d="M9.2285,16a1.5,1.5,0,1,1-1.5-1.5A1.5,1.5,0,0,1,9.2285,16Zm-1.5,4.5a1.5,1.5,0,1,0,1.5,1.5A1.4985,1.4985,0,0,0,7.7285,20.5Zm0-12a1.5,1.5,0,1,0,1.5,1.5A1.5,1.5,0,0,0,7.7285,8.5ZM25.7715,15H11.7285a1,1,0,0,0,0,2h14.043a1,1,0,1,0,0-2Zm-.043,6H11.6855a1,1,0,1,0,0,2h14.043a1,1,0,0,0,0-2ZM11.6855,11h14.043a1,1,0,0,0,0-2H11.6855a1,1,0,1,0,0,2Z"/></g></svg>
            </span>
            </button>
        </div>
    </nav>
</template>
