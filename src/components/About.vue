<template>
  <div class="flex flex-col items-center min-h-screen">
    <div class="text-center">
      <div class="mx-auto mb-4 mt-20 md:mt-32 h-48 w-48 md:h-64 md:w-64 overflow-hidden rounded-full bg-gradient-to-tr from-orange-500 to-purple-700">
        <img src="/images/me.png" alt="" class="w-full h-full object-cover" />
      </div>
      <h1 class="max-w-screen-sm text-4xl font-extrabold text-red-600 mb-8">
        Hi again,
        <span class="text-transparent bg-clip-text bg-gradient-to-tr from-orange-500 to-purple-700">I'm Markglen Tablada</span>
      </h1>
      <p class="mx-auto mb-16 text-lg font-light text-gray-400 max-w-lg">I am currently a Third year BSIT student at CPC, When I was in Highschool I've got interested in computers and programming.
        Moving up to senior high school, I took TVL specialized in ICT. <br>
      <br>Upon further learning and research, I found out that everything on a websites is made with HTML and CSS, and with that Information i gain more interest in pursuing computers and programming. <br>
      <br>As a Third year BSIT student at CPC,Im currently learning VueJS,Laravel since it is the required programming language for our third-year curriculum,if i have some free time or during
      vacations,I plan to start learning ReactJS on my own.I am really interested in exploring web development more deeply!
    </p>
      <div class="text-center">
        <button class="text-gray-800 inline-block px-8 py-4 mr-4 bg-white rounded-full font-semibold text-lg">Contact Me</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Component logic
};
</script>

<style scoped>
@media (min-width: 640px) {
  .h-24 {
    height: 6rem; /* Adjust the height for smaller screens */
  }
  .w-24 {
    width: 6rem; /* Adjust the width for smaller screens */
  }
}

</style>
