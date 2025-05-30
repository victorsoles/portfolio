<template>
    <nav class="bg-gray-900 sticky w-full top-0 z-50 shadow-lg">
        <div class="mx-auto max-w-6xl px-4 py-3 sm:px-6 lg:px-8">
            <div class="relative flex h-12 items-center justify-between">
                <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
                    <!-- Mobile menu button-->
                    <button type="button" class="relative inline-flex items-center justify-center rounded-md p-2 text-gray-400 hover:bg-gray-700 hover:text-white focus:ring-2 focus:ring-white focus:outline-hidden focus:ring-inset" aria-controls="mobile-menu" aria-expanded="false">
                        <span class="absolute -inset-0.5"></span>
                        <span class="sr-only">Open main menu</span>
                        <!--
                            Icon when menu is closed.

                            Menu open: "hidden", Menu closed: "block"
                        -->
                        <svg class="block size-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                        </svg>
                        <!--
                            Icon when menu is open.

                            Menu open: "block", Menu closed: "hidden"
                        -->
                        <svg class="hidden size-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18 18 6M6 6l12 12" />
                        </svg>
                    </button>
                </div>
                <!-- <div class="flex flex-1 items-center justify-center  sm:items-stretch sm:justify-start">
                </div> -->
                <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="sm:ml-8 md:ml-0">
                        <a href="hero">
                            <img class="h-12 w-auto" src="/images/logo.png" alt="Your Company">
                        </a>
                    </div>
                    <div class="hidden sm:ml-8 md:ml-25 lg:ml-60 sm:block">
                        <div class="flex space-x-4">
                            <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
                            <a href="#about" class="group rounded-md px-3 py-2 text-md font-medium text-verde transition duration-300" aria-current="page">
                                Sobre
                                <span class="block max-w-0 group-hover:max-w-full transition-all duration-500 h-0.5 bg-gray-300"></span>
                            </a>
                            <a href="#projects" class="group rounded-md px-3 py-2 text-md font-medium text-gray-300 transition duration-300">
                                Projetos
                                <span class="block max-w-0 group-hover:max-w-full transition-all duration-500 h-0.5 background-green"></span>
                            </a>
                            <a href="#features" class="group rounded-md px-3 py-2 text-md font-medium text-gray-300 transition duration-300">
                                Soluções
                                <span class="block max-w-0 group-hover:max-w-full transition-all duration-500 h-0.5 background-green"></span>
                            </a>
                            <a href="#contact" class="group rounded-md px-3 py-2 text-md font-medium text-gray-300 transition duration-300">
                                Contatos
                                <span class="block max-w-0 group-hover:max-w-full transition-all duration-500 h-0.5 background-green"></span>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="relative ml-3">
                    <img class="h-7 rounded-md w-auto opacity-90" src="/images/brazil.png" alt="Your Company">
                </div>
            </div>
        </div>
    </nav>
</template>

<script setup>

</script>
  