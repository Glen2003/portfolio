<!-- Projects.vue -->
<template>
  <section class="py-8 px-4" id="project">
    <h2 class="text-2xl md:text-4xl font-extrabold leading-tight tracking-tight mb-4 text-center text-red-700">Some of my Recent Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8">
      <!-- Card component repeated six times -->
      <div v-for="(project, index) in projects" :key="index" class="overflow-hidden bg-black rounded-lg shadow-lg mx-auto">
        <img :src="project.image" :alt="project.title" class="w-full h-40 md:h-48 object-cover object-center">
        <div class="p-4 md:p-6 bg-black ">
          <h3 class="font-semibold text-lg md:text-xl mb-2 text-yellow-400 cursor-pointer">{{ project.title }}</h3>
          <p class="text-gray-100 text-sm md:text-base cursor-pointer">{{ project.description }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          title: "Student Monitoring",
          description: "A student monitoring system is to monitor the student and to notify the parents when their children is arrived at school",
          image: "/images/monitoring.png",
        },
        {
          title: "Account Manager",
          description: "Account manager is a system that manage the users account like updating users password and assigning roles.",
          image: "/images/account.png",
        },
        {
          title: "Anime Website",
          description: "Anime website using React js",
          image: "/images/anime.png",
        },
        {
          title: "Music Player - SPOTIFY API",
          description: "A music player using spotify api and fetch api in Nodejs and basic css and html.",
          image: "/images/spotify.jpg",
        },
        {
          title: "Milktea Ordering System",
          description: "A Milktea Ordering System created with PHP,HTML,CSS,JAVASCRIPT, JQUERY. ",
          image: "/images/milktea.png",
        },
        {
          title: "Portfolio - Vue",
          description: "My personal portfolio using vue js framework and tailwind css",
          image: "/images/port.png",
        },
      ],
    };
  },
};
</script>

<style scoped>
#project{
  background-color: #141818;
}
/* Add your custom styles here */
</style>
