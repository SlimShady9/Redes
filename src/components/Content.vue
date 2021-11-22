<template>
  <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
      <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
        <span class="relative inline-block">
          <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
            <defs>
              <pattern id="db164e35-2a0e-4c0f-ab05-f14edc6d4d30" x="0" y="0" width=".135" height=".30">
                <circle cx="1" cy="1" r=".7"></circle>
              </pattern>
            </defs>
            <rect fill="url(#db164e35-2a0e-4c0f-ab05-f14edc6d4d30)" width="52" height="24"></rect>
          </svg>
          <span class="relative">Proyectos</span>
        </span>
        que he realizado
      </h2>
      <p class="text-base text-gray-700 md:text-xl font-bold">
        En esta sección encontrarás una lista de proyectos que he realizado en el ámbito de la programación.
      </p>
    </div>
    <div class="grid max-w-sm gap-5 mb-8 lg:grid-cols-3 sm:mx-auto lg:max-w-full">
      <div class="grid px-10 py-20 text-center border rounded lg:px-5 lg:py-10 xl:py-20">
        
        <a href="https://juegazo.gq" target="_blank" class="inline-block max-w-xs mx-auto mb-3 text-2xl font-extrabold leading-7 transition-colors duration-200 hover:text-deep-purple-accent-400" aria-label="Read article" title="Nori grape silver beet broccoli kombu beet">
          Pequeño videojuego con HTML5 manipulando el DOM
        </a>
        <img class="border-2 p-2 border-gray-200 border-dotted" src="/juegazo.jpg" alt="" srcset="">
      </div>
      <div class="grid px-10 py-20 text-center border rounded lg:px-5 lg:py-10 xl:py-20">
        
        <a
          href="https://chat-room-eight.vercel.app/"
          target="_blank"
          class="inline-block max-w-xs mx-auto mb-3 text-2xl font-extrabold leading-7 transition-colors duration-200 hover:text-deep-purple-accent-400"
          aria-label="Read article"
          title="Well, the way they make shows is, they make one"
        >
          Aplicación para chatear en salas
        </a>
        <p class="max-w-xs mx-auto mb-2 text-gray-700">
          Una pagina web donde puedes hablar con personas que estén en tu sala de chat.
        </p>
        <img src="/Chatazo.jpg" class="border-2 p-2 border-gray-200 border-dotted place-self-end" alt="">
      </div>
      <div class="grid px-10 py-20 text-center border rounded lg:px-5 lg:py-10 xl:py-20">
        <a
          href="http://chibcha-web.vercel.app/"
          target="_blank"
          class="inline-block max-w-xs mx-auto mb-3 text-2xl font-extrabold leading-7 transition-colors duration-200 hover:text-deep-purple-accent-400"
          aria-label="Read article"
          title="Pommy ipsum smeg head whizz morris himer due"
        >
          ChibchaWeb
        </a>
        <p class="max-w-xs mx-auto mb-2 text-gray-700">
          Usuarios pueden registrarse y gestionar sus dominios web y perfil (ejercicio academico).
        </p>
        <img src="/ChibchaWeb.jpg" class="border-2 p-2 border-gray-200 border-dotted place-self-end" alt="" srcset="">
      </div>
    </div>
  </div>
</template>