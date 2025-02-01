<template>
    <section class="bg-gray-900 text-white py-16 px-8">
      <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Texto de Contato -->
        <div class="flex flex-col justify-center">
          <h3 class="text-4xl font-bold mb-4">Contact</h3>
          <p class="text-gray-300 mb-4">
            Feel free to reach out to me with any questions or feedback.
          </p>
          <p class="text-gray-300">
            I'm always open to discussing new projects, creative ideas, or
            opportunities.
          </p>
        </div>
  
        <!-- Formulário -->
        <form
          @submit.prevent="submitForm"
          class="bg-gray-800 rounded-xl shadow-lg p-6 flex flex-col gap-4"
        >
          <!-- Nome -->
          <input
            type="text"
            placeholder="Your Name"
            v-model="form.name"
            class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
          />
  
          <!-- Email -->
          <input
            type="email"
            placeholder="Your Email"
            v-model="form.email"
            class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
          />
  
          <!-- Assunto -->
          <input
            type="text"
            placeholder="Subject"
            v-model="form.subject"
            class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
          />
  
          <!-- Mensagem -->
          <textarea
            placeholder="Your Message"
            v-model="form.message"
            rows="4"
            class="bg-gray-700 text-white rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-300"
          ></textarea>
  
          <!-- Botão de envio -->
          <button
            type="submit"
            class="background-green hover:bg-green-300 cursor-pointer text-white font-semibold rounded-lg px-6 py-2 transition"
          >
            Send Message
          </button>
        </form>
      </div>
    </section>
  </template>
  
  <script setup>
  import { reactive } from "vue";
  
  const form = reactive({
    name: "",
    email: "",
    subject: "",
    message: "",
  });
  
  const submitForm = () => {
    // Aqui você pode adicionar lógica para enviar o formulário
    console.log("Form data:", form);
    alert("Message sent!");
  };
  </script>
  
  <style scoped>
  /* Estilo adicional (se necessário) */
  </style>
  