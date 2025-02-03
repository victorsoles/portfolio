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
                        <p class="text-gray-400 text-sm">600</p>
                        <span class="text-verde">
                            <i class="fas fa-heart"></i>
                        </span>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-105">
                    <div class="flex justify-center items-center h-60 mb-4">
                        <img src="/images/logoMoneyMap.png" alt="MoneyMap" class="rounded-lg max-h-full max-w-full object-contain" />
                    </div>
                    <p class="text-verde text-sm uppercase mb-2">Portal Educativo</p>
                    <h3 class="text-xl font-semibold mb-4">
                        Plataforma de Suporte ao Desenvolvimento Acadêmico
                    </h3>
                    <div class="flex justify-between items-center">
                        <p class="text-gray-400 text-sm">750</p>
                        <span class="text-verde">
                            <i class="fas fa-heart"></i>
                        </span>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-105">
                    <div class="flex justify-center items-center h-60 mb-4">
                        <img src="/images/logoMoneyMap.png" alt="MoneyMap" class="rounded-lg max-h-full max-w-full object-contain" />
                    </div>
                    <p class="text-verde text-sm uppercase mb-2">REST API</p>
                    <h3 class="text-xl font-semibold mb-4">
                        Desenvolvimento de API REST para integração de sistemas
                    </h3>
                    <div class="flex justify-between items-center">
                        <p class="text-gray-400 text-sm">630</p>
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
