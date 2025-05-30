<template>
    <section id="hero" class="bg-gray-900">
        <div
            class="text-white py-6 px-8 flex flex-col mx-auto max-w-6xl md:flex-row items-center justify-between"
        >
            <!-- Texto da seção -->
            <div class="md:w-1/2 text-center md:text-left">
                <h1 class="text-2xl font-bold mb-5">
                    Olá, <span class="text-verde">eu sou</span>
                </h1>
                <h2 class="text-5xl font-bold text-verde mb-5">Victor Soles</h2>
                <p class="text-lg mb-6 font-bold">Desenvolvedor de Sistemas Web</p>
                <p class="text-sm text-gray-400 mb-8">
                    Sou um desenvolvedor de sistemas web apaixonado por criar soluções eficientes e escaláveis.  
                    Trabalho principalmente com Laravel, Vue 3, Inertia.js e Tailwind CSS
                </p>

                <a
                    href="/portfolio/Curriculo-Victor-Soles.pdf"
                    download="Curriculo-Victor-Soles.pdf"
                    class="background-green-hover text-white px-6 py-3 my-2 mr-5 rounded-xl shadow-md inline-block"
                >
                    Currículo
                </a>

                <a
                    href="#projects"
                    class="text-gray-300 px-6 py-3 my-2 rounded-xl border-1 border-gray-400 shadow-md hover:bg-gray-700 cursor-pointer"
                >
                    Veja meu trabalho
                </a>

                <!-- Ícones sociais -->
                <div class="flex justify-center md:justify-start space-x-6 mt-8">
                    <a
                        href="https://www.linkedin.com/in/victor-soles/"
                        target="_blank"
                        class="bg-gray-800 p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img class="h-5 w-auto opacity-90" src="/images/icons/linkedin.png" alt="Link Linkedin">
                    </a>

                    <a
                        href="https://github.com/victorsoles" 
                        target="_blank"
                        class="bg-gray-800 p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img class="h-6 w-auto opacity-90" src="/images/icons/github.png" alt="Link GitHub">
                    </a>

                    <a
                        href="https://www.instagram.com/victorsolles/" 
                        target="_blank"
                        class="bg-gray-800 p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img class="h-5 w-auto opacity-90" src="/images/icons/instagram.png" alt="link Instagram">
                    </a>
                </div>
            </div>

            <!-- Imagem da seção -->
            <div class="md:w-1/2 mt-10 md:mt-0 flex justify-center">
                <div class="p-2 rounded-xl shadow-lg">
                    <img
                        src="/images/heroTeste.png"
                        alt="Tayyab Sajjad"
                        class="rounded-xl object-cover"
                    />
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<style>
.background-green-hover {
    background-color: #00bd95;
}

.background-green-hover:hover {
    background-color: #009b7a; /* Cor mais escura para o hover */
}

</style>