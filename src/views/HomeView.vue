<script setup>
import components from "../components/component.vue";
</script>

<template>
  <!-- le composant navbar -->
  <components />
  <!-- le composant navbar -->

  <!-- ////////////////////////// section hero ////////////////////// -->

  <section
    class="flex-col-reverse flex justify-between sm:flex sm:flex-col-reverse md:flex-row lg:flex-row xl:flex-row py-10 px-20"
  >
    <div
      class="pt-20 text-center w-full sm:text-center md:text-left lg:text-left xl:text-left"
    >
      <p class="font-bold">Welcome to my Portfolio</p>
      <h1 class="text-5xl font-bold py-5">
        Hi I’m <br />
        <span class="text-blue-600">Robert Junior</span> <br />
        Product Designer
      </h1>
      <p>
        Collaborating with highly skilled individuals, <br />
        our agency delivers top-quality services
      </p>

      <div
        class="flex gap-5 py-5 flex-col sm:justify-center md:justify-start sm:flex-col md:flex-row"
      >
        <button
          class="h-12 bg-blue-600 text-white font-bold w-full sm:w-full rounded-full md:w-32"
        >
          Let’s chat
        </button>
        <button
          class="h-12 border-2 border-blue-600 text-bleu-600 w-full sm:w-full font-bold rounded-full md:w-32"
        >
          Download CV
        </button>
        <!-- <font-awesome-icon icon="fa-solid fa-user-secret" /> -->
      </div>
    </div>
    <div>
      <img
        src="../assets/image/pexels-wictor-cardoso-18269632-removebg 1.png"
        alt=""
      />
    </div>
  </section>
  <!-- ////////////////////////// section hero ////////////////////// -->

  <!-- ========================= section sponsort==================== -->
  <section
    class="flex flex-col gap-5 sm:flex sm:flex-col sm:justify-between md:flex md:justify-between md:flex-col lg:flex lg:justify-between lg:flex-row xl:flex xl:justify-between lx:flex-row py-10 px-20"
  >
    <img src="../assets/image/logo-1.png" alt="" />
    <img src="../assets/image/logo-2.png" alt="" />
    <img src="../assets/image/logo-3.png" alt="" />
    <img src="../assets/image/logo-5.png" alt="" />
  </section>
  <!-- ========================= section sponsort==================== -->

  <!-- ///////////////////////// section experience////////////////// -->
  <div
    class="flex-col-reverse gap-8 flex justify-between sm:flex sm:justify-center sm:items-center sm:flex-col md:flex md:justify-center md:items-center md:flex-row lg:flex lg:justify-center lg:items-center lg:flex-row xl:flex xl:justify-center xl:items-center xl:flex-row py-10 px-20"
  >
    <div class="w-1/2">
      <img src="../assets/image/pexel2.png" alt="" class="" />
    </div>

    <div class="w-full sm:w-full md:w-1/2">
      <div class="">
        <div class="text-center md:text-left lg:text-left xl:text-left">
          <span class="text-blue-600 font-bold">About Me</span>
          <h1 class="text-4xl font-bold py-5">
            <span class="text-blue-600 font-bold text-4xl"
              >20 Year’s Experience</span
            >
            <br />
            on Product Design
          </h1>
          <p class="py-5">
            Hello there! I'm Robert Junior. I specialize in web design and
            <br />
            development, and I'm deeply passionate and committed to my craft.
            <br />
            With 20 years of experience as a professional graphic designe
          </p>
        </div>

        <div
          class="py-8 flex flex-col gap-2 justify-between sm:flex-col md:flex-row lg:flex-row xl:flex-row"
        >
          <button
            class="h-10 bg-blue-600 text-white font-bold rounded-full md:w-40 w-full"
          >
            Main Skills
          </button>
          <button
            class="h-10 border-2 border-blue-600 text-bleu-600 font-bold rounded-full md:w-40 w-full"
          >
            Awards
          </button>
          <button
            class="h-10 border-2 border-blue-600 text-bleu-600 font-bold rounded-full md:w-40 w-full"
          >
            Education
          </button>
        </div>
        <div>
          <div>
            <h1 class="font-bold py-2">User Experience Design - UI/UX</h1>
            <div class="bg-gray-200 w-[500px] sm:w-full  md:w-full lg:w-full xl:w-full h-4 rounded-full">
              <div
                class="bg-blue-600 w-[430px]  sm:w-[550px] md:w-[500px] lg:w-[500px] xl:w-[500px] h-4 rounded-full text-white font-bold flex gap-5"
              ></div>
            </div>
          </div>
          <div>
            <h1 class="font-bold py-2">
              Web & User Interface Design - Development
            </h1>
            <div class="bg-gray-200 w-[500px] h-4 sm:w-full md:w-full lg:w-full xl:w-full rounded-full">
              <div
                class="bg-blue-600 w-[470px] h-4 sm:w-[450px] md:w-[450px] lg:w-[450px] xl:w-[450px] rounded-full text-white font-bold flex gap-5"
              ></div>
            </div>
          </div>
          <div>
            <h1 class="font-bold py-2">Interaction Design - Animation</h1>
            <div class="bg-gray-200 w-[500px] h-4 sm:w-full md:w-full lg:w-full xl:w-full rounded-full">
              <div
                class="bg-blue-600 w-[470px] h-4 sm:w-[400px] md:w-[400px] lg:w-[400px] xl:w-[400px] rounded-full text-white font-bold flex gap-5"
              ></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- ///////////////////////// section experience////////////////// -->
</template>
