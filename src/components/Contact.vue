<template>
    <section class="bg-gray-900 text-white py-16 px-8">
        <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Texto de Contato -->
            <div class="flex flex-col justify-center">
                <h3 class="text-4xl font-bold mb-4">Contato</h3>
                <p class="text-gray-300 mb-4">
                    Sinta-se à vontade para entrar em contato comigo.
                </p>
                <p class="text-gray-300">
                    Estou sempre aberto a discutir novos projetos, ideias criativas ou oportunidades.
                </p>
                <div class="flex justify-center md:justify-start space-x-6 mt-8">
                    <a
                        href="https://w.app/victorsoles"
                        target="_blank"
                        class="background-green-hover p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img
                            class="h-6 w-auto opacity-90"
                            src="/images/icons/whatsapp.png"
                            alt="Link WhatsApp"
                        />
                    </a>

                    <a
                        href="https://www.instagram.com/victorsolles/"
                        target="_blank"
                        class="bg-gray-800 p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img
                            class="h-6 w-auto opacity-90"
                            src="/images/icons/o-email.png"
                            alt="Copiar Email"
                        />
                    </a>

                    <a
                        href="https://www.linkedin.com/in/victor-soles/"
                        target="_blank"
                        class="bg-gray-800 p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img
                            class="h-6 w-auto opacity-90"
                            src="/images/icons/linkedin.png"
                            alt="Link Linkedin"
                        />
                    </a>

                    <a
                        href="https://www.instagram.com/victorsolles/"
                        target="_blank"
                        class="bg-gray-800 p-4 rounded-full shadow-md hover:bg-gray-700 transition flex items-center justify-center"
                    >
                        <img
                            class="h-6 w-auto opacity-90"
                            src="/images/icons/instagram.png"
                            alt="link Instagram"
                        />
                    </a>
                </div>
            </div>

            <!-- Formulário -->
            <form
                @submit.prevent="submitForm"
                class="bg-gray-800 rounded-xl shadow-lg p-6 flex flex-col gap-4"
            >
                <!-- Nome -->
                <input
                    type="text"
                    placeholder="Seu nome"
                    v-model="form.name"
                    class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
                />

                <!-- Email -->
                <input
                    type="email"
                    placeholder="Seu Email"
                    v-model="form.email"
                    class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
                />

                <!-- Mensagem -->
                <textarea
                    placeholder="Sua Mensagem"
                    v-model="form.message"
                    rows="4"
                    class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
                ></textarea>

                <!-- Botão de envio -->
                <button
                    type="submit"
                    class="background-green2-hover cursor-pointer text-white font-semibold rounded-lg px-6 py-2 transition"
                >
                    Enviar Mensagem
                </button>
            </form>
        </div>
    </section>
</template>

<script setup>
import { reactive } from 'vue';

const form = reactive({
    name: '',
    email: '',
    subject: '',
    message: '',
});

const submitForm = () => {
    // Aqui você pode adicionar lógica para enviar o formulário
    console.log('Form data:', form);
    alert('Message sent!');
};
</script>

<style scoped>
.background-green-hover {
    background-color: #009b7a;
}

.background-green-hover:hover {
    background-color: #00bd95; /* Cor mais escura para o hover */
}

.background-green2-hover {
    background-color: #00bd95;
}

.background-green2-hover:hover {
    background-color: #009b7a; /* Cor mais escura para o hover */
}
</style>
