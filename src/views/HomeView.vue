<script setup>
import components from '../components/component.vue'
</script>

<template>
  <!-- le composant navbar -->
  <components />
  <!-- le composant navbar -->

  <!-- ////////////////////////// section hero ////////////////////// -->

    <section class="flex-col-reverse flex justify-between sm:flex sm:flex-col-reverse    md:flex-row lg:flex-row xl:flex-row  py-10 px-20">
        <div class="pt-20 text-center w-full sm:text-center md:text-left lg:text-left xl:text-left  ">
          <p class="font-bold">Welcome to my Portfolio</p>
          <h1 class="text-5xl font-bold py-5">
              Hi I’m <br>
              <span class="text-blue-600">Robert Junior</span> <br>
              Product Designer
          </h1>
          <p>
              Collaborating with highly skilled individuals, <br>
              our agency delivers top-quality services
          </p>

          <div class="flex gap-5 py-5 flex-col  sm:justify-center md:justify-start  sm:flex-col md:flex-row ">
            <button class=" h-12 bg-blue-600 text-white font-bold w-full sm:w-full  md:flex-row  rounded-full md:w-32">
                Let’s chat
            </button>
            <button class=" h-12 border-2 border-blue-600 text-bleu-600 w-full sm:w-full font-bold  rounded-full md:w-32">
                Download CV
            </button>
              <!-- <font-awesome-icon icon="fa-solid fa-user-secret" /> -->
          </div>
        </div>
        <div  >
            <img src="../assets/image/pexels-wictor-cardoso-18269632-removebg 1.png" alt="">
        </div>
    </section>
  <!-- ////////////////////////// section hero ////////////////////// -->
  
</template>
