<template>
  <aside class="fixed min-h-screen w-60 top-0 left-0">
    <nav class="flex w-full flex-col px-4 py-3 h-screen overflow-y-auto bg-black border-t">
      <span class="inline-flex flex-col">
        <a class="text-primary tracking-tight leading-snug text-2xl font-black px-1" href="/">🍿 Filmi9.com</a><span
          class="text-gray-100 tracking-wide text-xs px-1">Watch <strong>movies online</strong></span></span>

      <ul class="flex flex-col space-y-4 py-1 mt-3">
        <li class="flex items-center space-x-2 text-white tracking-wide text-lg font-semibold font-roboto">
          <a href="/">🎥 Movies</a><span
            class="rounded-lg bg-red-600 px-2 py-0.5 text-white text-xs font-medium font-roboto">6441 online</span>
        </li>
        <a class="flex items-center space-x-2 text-white tracking-wide text-lg font-semibold font-roboto"
          href="/seriali">🎬 TV series online</a><a
          class="flex items-center space-x-2 text-white tracking-wide text-lg font-semibold font-roboto"
          href="/filmi/bg-audio">🇧🇬 Movies BG AUDIO</a><a
          class="flex items-center space-x-2 text-white tracking-wide text-lg font-semibold font-roboto"
          href="/trending">💫 Top Movies Online</a><a
          class="flex items-center space-x-2 text-white tracking-wide text-lg font-semibold font-roboto"
          href="/actors">🧑 Actors</a>
      </ul>

      <ul class="flex flex-col space-y-4 py-3 mt-3 border-t border-t-[#171717]">
        <p class="text-gray-300 text-sm">What do you want to watch today?</p>
        <li class="flex items-center space-x-3 p-0.5 hover:bg-black rounded">
          <div class="w-10 h-10 bg-[#171717] rounded-full relative">
            <img alt="Drama Movies Online"
              sizes="(max-width: 640px) 100px, (max-width: 768px) 120px, 140px"
              src="https://placehold.co/600x400"
              decoding="async" data-nimg="fill" class="rounded-full" loading="lazy"
              style="position: absolute; height: 100%; width: 100%; inset: 0px; object-fit: cover; color: transparent;"
              ></div>
          <div class="block"><a class="text-white text-lg font-semibold font-roboto" href="/genre/drama"
              _msttexthash="57434" _msthash="11">Drama</a>
            <p class="text-white text-xs" _msttexthash="139256" _msthash="12">2469 movies</p>
          </div>
        </li>
        <li class="flex items-center space-x-3 p-3 cursor-pointer hover:bg-black rounded"><a class="text-white text-lg font-semibold font-roboto" href="/genres" >All genres</a></li>
      </ul>

      <div class="w-full rounded-lg px-3 py-6 mt-9 bg-black"><p class="text-gray-400 text-xs text-center" >The films published on the site are not hosted by Filmi9.com. Filmi9 does not store physical video files.</p></div>
    </nav>
  </aside>
</template>
