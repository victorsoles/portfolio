<template>
    <section class="bg-gray-900 text-white py-20 px-8">
        <div class="max-w-6xl mx-auto">
            <!-- Título -->
            <h3 class="text-verde text-center font-medium mb-4">
                Veja meu portfólio de projetos públicos
            </h3>
            <h2 class="text-4xl font-bold text-center mb-12">Projetos</h2>

            <!-- Cards -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-105">
                    <div class="flex justify-center items-center h-60 mb-4">
                        <img src="/images/logoMoneyMap.png" alt="MoneyMap" class="rounded-lg max-h-full max-w-full object-contain" />
                    </div>
                    <p class="text-verde text-sm uppercase mb-2">MoneyMap</p>
                    <h3 class="text-xl font-semibold mb-4">
                        Sistema de gerenciamento de finanças pessoais
                    </h3>
                    <div class="flex justify-between items-center">
                        <p class="text-gray-400 text-sm">Projeto em Manutenção</p>
                        <span class="text-verde">
                            <i class="fas fa-heart"></i>
                        </span>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-105">
                    <div class="flex justify-center items-center h-60 mb-4 relative">
                        <div class="absolute inset-0 flex justify-center items-center">
                            <div class="bg-custom rounded-xl size-custom"></div>
                        </div>
                        <div class="z-10">
                            <img src="/images/logoGowave.png" alt="Gowave" class="rounded-lg h-20 w-auto object-contain" />
                        </div>
                    </div>
                    <p class="text-verde text-sm uppercase mb-2">Gowave</p>
                    <h3 class="text-xl font-semibold mb-4">
                        Landing Page para contratação de serviços
                    </h3>
                    <div class="flex justify-between items-center">
                        <a href="https://gowave.com.br/" target="_blank" class="text-indigo-300 hover:scale-102 text-sm">Ver Projeto</a>
                        <span class="text-verde">
                            <i class="fas fa-heart"></i>
                        </span>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-105">
                    <div class="flex justify-center items-center h-60 mb-4">
                        <img src="/images/projetoEmManutencao.png" alt="MoneyMap" class="rounded-lg w-48 h-auto object-contain" />
                    </div>
                    <p class="text-verde text-sm uppercase mb-2">Portal Educativo</p>
                    <h3 class="text-xl font-semibold mb-4">
                        Plataforma de Suporte ao Desenvolvimento Acadêmico
                    </h3>
                    <div class="flex justify-between items-center">
                        <p class="text-gray-400 text-sm">Projeto em Desenvolvimento</p>
                        <span class="text-verde">
                            <i class="fas fa-heart"></i>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<style>
.bg-custom {
    background-color: #5d6ed6;
}

.size-custom {
    width: 90%;
    height: 80%;
}
</style>
