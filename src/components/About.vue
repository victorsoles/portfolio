<template>
    <section class="bg-gray-950">
        <div class="text-white py-20 px-8 mx-auto max-w-6xl">
            <div class="flex flex-col md:flex-row max-w-6xl mx-auto items-center">
                <!-- Imagem -->
                <div class="md:w-1/2 flex justify-center md:justify-start mb-8 md:mb-0">
                    <img
                        src="/images/imgAbout.jpg"
                        alt="Mary Smith"
                        class="rounded-xl shadow-lg object-cover w-full max-w-sm"
                    />
                </div>

                <!-- Conteúdo -->
                <div class="md:w-1/2 md:pl-12">
                    <h3 class="text-verde text-xl font-semibold mb-4">Quem sou eu?</h3>
                    <h2 class="text-3xl font-bold mb-6">
                        Eu sou Victor Soles, um Desenvolvedor de Sistemas Web <br />
                    </h2>
                    <p class="text-gray-400 text-sm mb-6 leading-relaxed">
                        Sou um desenvolvedor de sistemas web apaixonado por criar soluções eficientes e escaláveis.  
                        Trabalho principalmente com Laravel, Vue 3, Inertia.js e Tailwind CSS. Sempre busco escrever código limpo,  
                        bem estruturado e de fácil manutenção. <span class="text-verde">Saiba mais</span>
                    </p>

                    <!-- Informações -->
                    <div class="grid grid-cols-2 gap-4 text-sm mb-6">
                        <div>
                            <p class="text-gray-400">Name:</p>
                            <p class="font-bold text-white">Mary Smith</p>
                        </div>
                        <div>
                            <p class="text-gray-400">From:</p>
                            <p class="font-bold text-white">New York, USA</p>
                        </div>
                        <div>
                            <p class="text-gray-400">Age:</p>
                            <p class="font-bold text-white">35</p>
                        </div>
                        <div>
                            <p class="text-gray-400">Email:</p>
                            <p class="font-bold text-white">marysmith@gmail.com</p>
                        </div>
                    </div>

                    <!-- Botão -->
                    <button
                        class="background-green text-white px-6 py-3 rounded-xl shadow-md hover:bg-green-400 transition"
                    >
                        Baixar Currículo
                    </button>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<script setup></script>

<style lang="scss" scoped></style>
