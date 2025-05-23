<template>
  <div class="relative h-screen w-full overflow-hidden">
    <video
      autoplay
      loop
      muted
      playsinline
      class="absolute top-0 left-0 w-full h-full object-cover z-0"
    >
      <source
        src="https://act-webstatic.hoyoverse.com/puzzle/hk4e/pz_DvjBejelna/resource/puzzle/2024/09/03/61284ab577e9db9d34d2caab99558ae3_8193488065075813152.mp4"
        type="video/mp4"
      />
    </video>

    <div
      class="relative z-10 flex items-center justify-center h-full text-center text-white"
    >
      <div>
        <img
          src="https://fastcdn.hoyoverse.com/mi18n/resource-trans/upload/event/2022/09/22/9e92bf0749633a5afec41c619a485886_5908227672008322975.png?x-oss-process=image/format,webp/quality,Q_90"
          alt=""
          className=" z-20 w-[389px]"
        />
        <p class="text-xl mb-6 drop-shadow-md">Explore o Mundo de Aventura</p>
        <button
          class="bg-yellow-500 hover:bg-yellow-600 text-white text-[20px] font-bold px-30 py-3 rounded shadow-lg cursor-pointer"
        >
          Baixar
        </button>
      </div>

      
    </div>

    <div class="absolute top-0 left-0 w-full h-full bg-black/40 z-5"></div>
  </div>

  <footer className="bg-gray-900 text-gray-300 py-8">
    <div
      className="container mx-auto px-4 flex flex-col items-center justify-center space-y-6"
    >
      <div>
        <img
          src="https://fastcdn.hoyoverse.com/mi18n/resource-trans/upload/event/2023/07/10/5adaf3c356e577f0659899a8f5a2a06a_863358723360619202.png"
          alt="Genshin Impact"
          className="w-[130px]"
        />
      </div>

      <nav className="flex flex-wrap justify-center gap-8 text-sm">
        <a
          href="#"

          className="hover:text-white transition"
        >
          Política de Privacidade
        </a>
        <a
          href="#"

          className="hover:text-white transition"
        >
          Termos de Serviço
        </a>
        <a
          href="#"
          className="hover:text-white transition"
        >
          Sobre Nós
        </a>
        <a
          href="#"
          className="hover:text-white transition"
        >
          Contate-nos
        </a>
        <a
          href="#"
          className="hover:text-white transition"
        >
          Centro de assistência
        </a>
      </nav>

      <div className="text-center text-xs text-gray-500 max-w-4xl px-4">
        <p>
          "PlayStation Family Mark," "PS5 logo" and "PS4 logo" are registered
          trademarks or trademarks of Sony Interactive Entertainment Inc.
        </p>
        <p>
          Epic, Epic Games, Epic Games Store, the Epic Games Store logo, and
          Epic Online Services are trademarks and/or registered trademarks of
          Epic Games. All other trademarks are the property of their respective
          owners.
        </p>
      </div>

      <div>
        <a
          href="#"
        >
          <img
            src="https://fastcdn.hoyoverse.com/mi18n/resource-trans/upload/event/2021/12/29/eaa64d81ae6a7318a6afb91cbffd83a4_118924438105936743.png"
            alt="HoYoverse Logo"
            className="w-[300px]"
          />
        </a>
      </div>

      <div className="text-center text-white text-sm mt-1">
        Copyright © COGNOSPHERE. All Rights Reserved.
      </div>
    </div>
  </footer>
</template>
