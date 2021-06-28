<template>
  <div>
     <section class="relative">
      <div class="container flex flex-col-reverse lg:flex-row items-center gap-12 mt-14 lg:mt-28">
        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <Logo />
          <br>
          <h2 class="text-bookmark-blue text-3xl md:text-4 lg:text-5xl text-center lg:text-left mb-6">
            Freedom.
          </h2>
          <p class="text-bookmark-grey text-lg text-center lg:text-left mb-6">
            The Social Platform for activists, to bring voice to their cause.
          </p>
          <div class="flex justify-center flex-wrap gap-6">
            <button onclick="window.location.replace('/404');" type="button" class="btn shadow-md py-3 px-6 rounded-md transition duration-300 bg-bookmark-purple text-white hover:bg-bookmark-white hover:text-black">
              Web Version
            </button>
            <button onclick="window.location.replace('/404')" type="button" class="btn shadow-md py-3 px-6 rounded-md transition duration-300 bg-bookmark-white hover:bg-bookmark-purple hover:text-white">
              Download The App (Desktop only)
            </button>
          </div>
        </div>
        <!-- Image -->
        <div class="flex justify-center flex-1 mb-10 md:mb-16 lg:mb-0 z-10">
          <img class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full" src="https://raw.githubusercontent.com/johnkomarnicki/modern-landing-page-with-tailwinds/master/public/imgs/hero-bg.png" alt="" />
        </div>
      </div>
      <!-- Rounded Rectangle -->
      <div
        class="
          hidden
          md:block
          overflow-hidden
          bg-bookmark-purple
          rounded-l-full
          absolute
          h-80
          w-2/4
          top-32
          right-0
          lg:
          -bottom-28
          lg:-right-36
        "
      ></div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style>
@import url("https://raw.githubusercontent.com/johnkomarnicki/modern-landing-page-with-tailwinds/master/public/style.css");
</style>
