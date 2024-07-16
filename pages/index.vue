<template>
  <div class="block w-full">
    <!-- INDEX PAGE HEADER SEARCH BAR -->
    <div class="w-full h-[300px] md:h-[400px] flex flex-col items-center justify-center rounded-md mt-3 bg-hero-pattern bg-repeat">
      <div class="w-full h-full flex flex-col items-center m-auto justify-center bg-black/60">
        <h2 class="text-3xl md:text-5xl text-white font-bold drop-shadow-xl"> Watch movies online </h2>
        <p class="text-white font-medium text-center mt-3"> Latest Movies & Series Online </p>
        <input type="text" class="w-10/12 md:w-5/12 px-3 h-12 rounded-md mt-3 bg-white/90 focus:outline-red-500 font-medium" placeholder="Search for movies and series" value="" />
        <button class="w-10/12 md:w-5/12 px-3 h-12 rounded-md shadow-lg shadow-red-500/50 mt-3 bg-red-600 text-white font-bold hover:bg-red-500 disabled:opacity-90"> Search Movies </button>
      </div>
    </div>
    <!-- Bolckquote -->
    <blockquote class="text-lg my-6 font-semibold italic text-center text-white mt-6">
      <span>Latest</span>
      <span class="relative inline-block mx-3">
        <span class="before:block before:absolute before:-inset-1 before:-skew-y-3 before:bg-primary"></span>
        <h1 class="relative text-white">Movies online</h1>
      </span>
      <span>today</span>
    </blockquote>
    <p class="text-gray-300 text-center text-sm"> Watch the latest <strong>movies online</strong> in HD quality and Bulgarian audio. At Filmi9 you will also find movies with BG subtitles. </p>
    <!-- Latest Update -->
    <div class="flex flex-col items-center w-full pb-10 mt-3">
      <div class="grid grid-cols-2 lg:grid-cols-4 2xl:grid-cols-6 gap-2 mt-3 w-full">
        <div class="block">
          <div class="w-full flex flex-col items-center rounded-md shadow relative hover:opacity-90 cursor-pointer z-10">
            <div class="w-full h-[280px] md:h-[300px] lg:h-[400px] 2xl:h-[500px] relative bg-gray-600 rounded-md">
              <a target="_blank" href="/movie">
                <div class="w-full h-full relative" name="movie_image">
                  <img alt="The Light Between Oceans (2016) Movie Online" src="https://filmi9.com/_next/image?url=https%3A%2F%2Fcdn.filmi9.com%2Fimages%2F1721025158297-c9S6VKZPllNgdxBUuI3GYJiqcKO.jpg.webp&w=384&q=80" class="rounded-xl" style="
                        position: absolute;
                        height: 100%;
                        width: 100%;
                        inset: 0px;
                        object-fit: cover;
                        color: transparent;
                      " />
                </div>
              </a>
              <div class="absolute top-2 left-1 flex flex-col space-y-1">
                <h4 class="text-white font-semibold text-xs py-1 px-2 bg-black rounded"> Movie online </h4>
                <span class="text-white font-semibold text-xs py-1 px-2 bg-black rounded text-center">
                  <a href="/#">BG SUBS</a>
                </span>
              </div>
              <div class="absolute bottom-1 right-1 flex flex-col items-center space-y-1">
                <div class="flex items-center text-white font-semibold text-xs py-1 px-2 bg-black/90 rounded space-x-1.5">
                  <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512" class="text-yellow-400" height="21" width="21" xmlns="http://www.w3.org/2000/svg">
                    <path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM21.3 229.2H21c.1-.1.2-.3.3-.4zM97 319.8H64V192h33zm113.2 0h-28.7v-86.4l-11.6 86.4h-20.6l-12.2-84.5v84.5h-29V192h42.8c3.3 19.8 6 39.9 8.7 59.9l7.6-59.9h43zm11.4 0V192h24.6c17.6 0 44.7-1.6 49 20.9 1.7 7.6 1.4 16.3 1.4 24.4 0 88.5 11.1 82.6-75 82.5zm160.9-29.2c0 15.7-2.4 30.9-22.2 30.9-9 0-15.2-3-20.9-9.8l-1.9 8.1h-29.8V192h31.7v41.7c6-6.5 12-9.2 20.9-9.2 21.4 0 22.2 12.8 22.2 30.1zM265 229.9c0-9.7 1.6-16-10.3-16v83.7c12.2.3 10.3-8.7 10.3-18.4zm85.5 26.1c0-5.4 1.1-12.7-6.2-12.7-6 0-4.9 8.9-4.9 12.7 0 .6-1.1 39.6 1.1 44.7.8 1.6 2.2 2.4 3.8 2.4 7.8 0 6.2-9 6.2-14.4z"></path>
                  </svg>
                  <p class="text-white font-semibold text-xs md:text-sm"> IMDB rating <strong class="text-yellow-400">7.3</strong>/10 </p>
                </div>
              </div>
              <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
                <button class="bg-black/90 hover:scale-105 rounded-lg p-3 inline-flex items-center text-white space-x-2">
                  <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" class="inline-block text-sm" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg">
                    <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"></path>
                    <path d="M6.271 5.055a.5.5 0 0 1 .52.038l3.5 2.5a.5.5 0 0 1 0 .814l-3.5 2.5A.5.5 0 0 1 6 10.5v-5a.5.5 0 0 1 .271-.445z"></path>
                  </svg>
                  <span class="text-sm">Trailer</span>
                </button>
              </div>
            </div>
          </div>
          <div v-if="0" class="w-screen h-screen fixed top-0 left-0 flex justify-center items-center z-50">
            <div class="w-full h-full">
              <div id="modal-bg" class="w-full h-full top-0 absolute backdrop-blur-sm bg-black/50">

              </div>
              <div class="w-[99vw] md:w-[40vw] min-w-[50vw] min-h-[50vh] flex items-center flex-col gap-3 -translate-y-1/2 p-4 bg-black shadow rounded-lg top-1/2 left-1/2 -translate-x-1/2 absolute">
                <h1 class="text-gray-200 font-black text-2xl font-roboto">The Light Between Oceans (2016)</h1>
                <div class="w-full h-[100px] px-4 rounded-lg bg-gray-900 text-gray-200 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent text-center">
                  <p class="m-auto"> Advertisement..</p>
                </div>
                <div class="rounded-lg w-full h-full" style="width: 640px; height: 360px;">

                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-col py-1 backdrop-blur-sm bg-black/80 w-full px-2 rounded-b">
            <div class="flex items-center justify-between py-1">
              <span class="text-white font-medium text-xs rounded" _msttexthash="10942776" _msthash="90">📅 2016</span>
              <span class="text-white font-medium text-xs rounded" _msttexthash="913692" _msthash="91">⏰ 132 min.</span>
              <span class="text-white font-medium text-xs rounded" _msttexthash="10980190" _msthash="92">😍 2.3K</span>
            </div>
            <div class="flex items-center space-x-1.5 w-full flex-wrap text-center justify-center">
              <a class="text-gray-400 font-roboto font-medium text-sm hover:text-red-500" href="/genre/drama">Drama</a>
              <a class="text-gray-400 font-roboto font-medium text-sm hover:text-red-500" href="/genre/romans">Romance</a>
            </div>
            <a class="md:text-lg text-center font-semibold text-white hover:text-gray-200 w-full truncate" href="/film/the-light-between-oceans-svetlina-mezhdu-dva-okeana-2016"> Light Between Two Oceans (2016)</a>
            <a target="_blank" class="bg-red-600 hover:bg-red-500 rounded-md my-1.5 md:my-2 p-1.5 md:px-2 md:py-2 inline-flex items-center justify-center text-white space-x-2" href="/film/the-light-between-oceans-svetlina-mezhdu-dva-okeana-2016">
              <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" class="inline-block text-md md:text-xl" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg">
                <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"></path>
                <path d="M6.271 5.055a.5.5 0 0 1 .52.038l3.5 2.5a.5.5 0 0 1 0 .814l-3.5 2.5A.5.5 0 0 1 6 10.5v-5a.5.5 0 0 1 .271-.445z"></path>
              </svg>
              <span class="font-medium font-roboto text-sm">Watch online</span>
            </a>
          </div>
        </div>
      </div>
      <a class="bg-white p-3 mb-10 mt-3 rounded w-10/12 md:w-6/12 font-semibold text-black text-center font-roboto leading-7" href="/filmi/1">See all movies online</a>
    </div>
    <p class="text-gray-300 text-center text-sm">All movies and series are available to watch for free and without registration.</p>
    <p class="text-gray-300 text-center text-sm">Movies published on the site for watching <strong>movies online</strong> are not hosted on our server. The site uses materials from other sites and is not responsible for the content of the published <strong>films and series</strong>. </p>
  </div>
</template>
