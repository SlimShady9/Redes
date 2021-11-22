<template>
  <div class="relative mt-16 bg-amber-200">
    <svg class="absolute top-0 w-full h-6 -mt-5 sm:-mt-10 sm:h-16 text-amber-200" preserveAspectRatio="none" viewBox="0 0 1440 54">
      <path fill="currentColor" d="M0 22L120 16.7C240 11 480 1.00001 720 0.700012C960 1.00001 1200 11 1320 16.7L1440 22V54H1320C1200 54 960 54 720 54C480 54 240 54 120 54H0V22Z"></path>
    </svg>
    <div class="px-4 pt-12 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
      <div class="grid lg:place-items-center gap-16 row-gap-10 mb-8 lg:grid-cols-6">
        <div class="md:max-w-md lg:col-span-2">
          <a href=""></a>
            
            <span class="ml-2 text-2xl font-bold tracking-wide text-gray-800 uppercase">¿Quieres saber más de mí?</span>
          
          <div class="mt-4 lg:max-w-sm">
            <p class="text-sm text-gray-800 font-bold">
              Contactame.
            </p>
            <p class="mt-4 text-sm text-gray-800 font-bold">
              Enviame un correo y respondere en breve.
            </p>
          </div>
        </div>
        <Form class="lg:col-span-4"/>
      </div>
      <div class="flex flex-col justify-between pt-5 pb-10 border-t border-deep-purple-accent-200 sm:flex-row">
        <p class=" text-xs text-gray-800 font-bold">
          © Copyright 2021 Juan David Alberto Quintero Gaona. Todos los derechos reservados.
        </p>
        
      </div>
    </div>
  </div>
</template>

<script>
import Form from './Form.vue'

export default {

    components: {
        Form
    },
    
}
</script>