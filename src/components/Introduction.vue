<template>
  <!-- Introduction -->
  <section class="mb-8 py-20 text-white text-center relative">
    <div
      class="absolute inset-0 w-full h-full bg-contain introduction-bg z-30"
      style="background-image: url(assets/img/intro.jpg)"
    ></div>
    <div class="container mx-auto">
      <div class="text-white main-header-content">
        <h1 class="font-bold text-5xl mb-5">
          Découvrez une nouvelle façon originale d'écouter de la musique!
        </h1>
        <p class="w-full md:w-8/12 mx-auto tracking-wide">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus et dolor
          mollis, congue augue non, venenatis elit. Nunc justo eros, suscipit ac aliquet
          imperdiet, venenatis et sapien. Duis sed magna pulvinar, fringilla lorem eget,
          ullamcorper urna.
        </p>
        <video width="640" height="480" controls autoplay loop class="mx-auto mt-14 rounded-lg">
          <source src="assets/video/player.mp4" type=video/mp4>
        </video>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Introduction',
};
</script>

<style></style>
