<template>
    <section class="bg-gray-950 text-white py-20 px-8">
        <div class="max-w-6xl mx-auto">
            <!-- Título -->
            <h3 class="text-verde text-center font-medium mb-5">
                Algumas funcionalidades já desenvolvidas em projetos privados
            </h3>
            <h2 class="text-4xl font-bold text-center mb-12">Soluções Desenvolvidas</h2>

            <!-- Cards -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="relative bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-104">
                    <h3 class="text-xl font-semibold mb-4">Relatórios de movimentações Financeiras</h3>
                    <p class="text-gray-400 text-sm">
                        Geração de relatórios analíticos de receitas e despesas com filtros por período, 
                        categoria e conta, gráficos interativos e exportação em PDF ou Excel para apoiar decisões financeiras.
                    </p>
                    <div class="absolute bottom-0 right-0 background-green-hover p-2 rounded-br-lg flex items-center justify-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-white" viewBox="0 0 24 24" fill="currentColor">
                            <path fill-rule="evenodd" d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 7h2v2h-2V7zm0 4h2v6h-2v-6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="relative bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-104">
                    <h3 class="text-xl font-semibold mb-4">Conciliação bancária manual</h3>
                    <p class="text-gray-400 text-sm">
                        	Ferramenta que cruza lançamentos internos com extratos bancários, 
                            aponta divergências e permite marcar itens conciliados, mantendo histórico e assegurando a 
                            integridade dos saldos.
                    </p>
                    <div class="absolute bottom-0 right-0 background-green-hover p-2 rounded-br-lg flex items-center justify-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-white" viewBox="0 0 24 24" fill="currentColor">
                            <path fill-rule="evenodd" d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 7h2v2h-2V7zm0 4h2v6h-2v-6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="relative bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-104">
                    <h3 class="text-xl font-semibold mb-4">Automação de Registro Rural</h3>
                    <p class="text-gray-400 text-sm">
                        O sistema gerencia o envio, validação e aprovação de documentos rurais,
                        integrando com órgãos governamentais para garantir conformidade legal,
                        reduzindo burocracia e acelerando o processo de regularização
                    </p>
                    <div class="absolute bottom-0 right-0 background-green-hover p-2 rounded-br-lg flex items-center justify-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-white" viewBox="0 0 24 24" fill="currentColor">
                            <path fill-rule="evenodd" d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 7h2v2h-2V7zm0 4h2v6h-2v-6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                </div>

                <!-- Card 4 -->
                <div class="relative bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-104">
                    <h3 class="text-xl font-semibold mb-4">Dashboard de Formulários Customizados</h3>
                    <p class="text-gray-400 text-sm">
                        Plataforma para criar formulários e dashboards de respostas de forma dinâmica,
                        definir regras de validação e acompanhar respostas em tempo real por meio de indicadores personalizados.
                    </p>
                    <div class="absolute bottom-0 right-0 background-green-hover p-2 rounded-br-lg flex items-center justify-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-white" viewBox="0 0 24 24" fill="currentColor">
                            <path fill-rule="evenodd" d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 7h2v2h-2V7zm0 4h2v6h-2v-6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                </div>

                <!-- Card 5 -->
                <div class="relative bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-104">
                    <h3 class="text-xl font-semibold mb-4">Envio de E-mails e Notificações Agendadas</h3>
                    <p class="text-gray-400 text-sm">
                        Cada tarefa concluída dispara notificações instantâneas e e-mails automáticos em filas, 
                        garantindo entrega confiável, escalável e sem impacto na performance da aplicação.
                    </p>
                    <div class="absolute bottom-0 right-0 background-green-hover p-2 rounded-br-lg flex items-center justify-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-white" viewBox="0 0 24 24" fill="currentColor">
                            <path fill-rule="evenodd" d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 7h2v2h-2V7zm0 4h2v6h-2v-6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                </div>

                <!-- Card 6 -->
                <div class="relative bg-gray-800 rounded-xl shadow-lg p-6 transition hover:scale-104">
                    <h3 class="text-xl font-semibold mb-4">Importação, Validação e Exportação de Dados</h3>
                    <p class="text-gray-400 text-sm">
                        Processos robustos para importar CSV com pré-validação e aprovação administrativa, 
                        além de exportar registros para Excel e PDF, facilitando integrações e auditorias.
                    </p>
                    <div class="absolute bottom-0 right-0 background-green-hover p-2 rounded-br-lg flex items-center justify-center cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-white" viewBox="0 0 24 24" fill="currentColor">
                            <path fill-rule="evenodd" d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 7h2v2h-2V7zm0 4h2v6h-2v-6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>

</script>

<style>
.background-green-hover {
    background-color: #009b7a;
}

.background-green-hover:hover {
    background-color: #00bd95;
}
</style>
