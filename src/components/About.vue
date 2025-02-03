<template>
    <section class="bg-gray-950">
        <div class="text-white py-20 px-8 mx-auto max-w-6xl">
            <div class="flex flex-col md:flex-row max-w-6xl mx-auto items-center">
                <!-- Imagem -->
                <div class="md:w-1/2 flex justify-center md:justify-start mb-8 md:mb-0">
                    <img
                        src="/images/imgAbout.jpg"
                        alt="Victor Soles"
                        class="rounded-xl shadow-lg object-cover w-full max-w-sm"
                    />
                </div>

                <!-- Conteúdo -->
                <div class="md:w-1/2 md:pl-12">
                    <h3 class="text-verde text-xl font-semibold mb-5">Quem sou eu?</h3>
                    <h2 class="text-3xl font-bold mb-6">
                        Eu sou Victor Soles, um Desenvolvedor de Sistemas Web <br />
                    </h2>
                    <p class="text-gray-400 text-sm mb-7 leading-relaxed">
                        Sou um desenvolvedor de sistemas web apaixonado por criar soluções eficientes e escaláveis.  
                        Trabalho principalmente com Laravel, Vue 3, Inertia.js e Tailwind CSS. Sempre busco escrever código limpo,  
                        bem estruturado e de fácil manutenção. <span class="text-verde cursor-pointer">Saiba mais</span>
                    </p>

                    <!-- Menu de Skills -->
                    <div class="mb-6">
                        <div class="flex border-b-2 border-gray-600">
                            <button 
                                @click="activeTab = 'hard'"
                                :class="{'bg-gray-800 text-verde': activeTab === 'hard'}"
                                class="px-4 py-2 font-bold text-gray-400 hover:bg-gray-700 hover:text-gray-300 transition rounded-t-lg"
                            >
                                HardSkills
                            </button>
                            <button 
                                @click="activeTab = 'soft'"
                                :class="{'bg-gray-800 text-verde': activeTab === 'soft'}"
                                class="px-4 py-2 font-bold text-gray-400 hover:bg-gray-700 hover:text-gray-300 transition rounded-t-lg"
                            >
                                SoftSkills
                            </button>
                        </div>

                        <div class="bg-gray-700 p-6 rounded-b-lg">
                            <div v-show="activeTab === 'soft'" class="grid grid-cols-3 gap-4">
                                <div class="p-2 bg-gray-800 text-white text-center rounded-lg shadow-md">Comunicação</div>
                                <div class="p-2 bg-gray-800 text-white text-center rounded-lg shadow-md">Trabalho em Equipe</div>
                                <div class="p-2 bg-gray-800 text-white text-center rounded-lg shadow-md">Resolução de Problemas</div>
                            </div>

                            <div v-show="activeTab === 'hard'" class="grid grid-cols-3 gap-4">
                                <div class="p-2 bg-gray-800 text-blue-600 text-center rounded-lg shadow-md">PHP</div>
                                <div class="p-2 bg-gray-800 text-green-500 text-center rounded-lg shadow-md">Vue</div>
                                <div class="p-2 bg-gray-800 text-orange-600 text-center rounded-lg shadow-md">Git</div>
                                <div class="p-2 bg-gray-800 text-orange-600 text-center rounded-lg shadow-md">Laravel</div>
                                <div class="p-2 bg-gray-800 text-yellow-500 text-center rounded-lg shadow-md">JavaScript</div>
                                <div class="p-2 bg-gray-800 text-indigo-500 text-center rounded-lg shadow-md">Tailwind CSS</div>
                            </div>
                        </div>
                    </div>

                    <!-- Botão -->
                    <button class="background-green text-white px-6 py-3 rounded-xl shadow-md hover:bg-green-400 transition">
                        Baixar Currículo
                    </button>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
    import { ref } from "vue";

    const activeTab = ref("hard"); 
</script>

<style  scoped>
    .background-green {
        background-color: #00bd95;
    }

    .background-green:hover {
        background-color: #009b7a;
    }

    .texto-green-hover:hover {
        color: #009b7a; 
        background-color: #364153;
    }
</style>
