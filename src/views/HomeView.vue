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
    class="flex flex-col gap-5 sm:flex sm:flex-col sm:justify-between md:flex md:flex-col lg:flex lg:flex-row xl:flex lx:flex-row py-10 px-20"
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
            <div
              class="bg-gray-200 w-[500px] sm:w-full md:w-full lg:w-full xl:w-full h-4 rounded-full"
            >
              <div
                class="bg-blue-600 w-[430px] sm:w-[550px] md:w-[500px] lg:w-[500px] xl:w-[500px] h-4 rounded-full text-white font-bold flex gap-5"
              ></div>
            </div>
          </div>
          <div>
            <h1 class="font-bold py-2">
              Web & User Interface Design - Development
            </h1>
            <div
              class="bg-gray-200 w-[500px] h-4 sm:w-full md:w-full lg:w-full xl:w-full rounded-full"
            >
              <div
                class="bg-blue-600 w-[470px] h-4 sm:w-[450px] md:w-[450px] lg:w-[450px] xl:w-[450px] rounded-full text-white font-bold flex gap-5"
              ></div>
            </div>
          </div>
          <div>
            <h1 class="font-bold py-2">Interaction Design - Animation</h1>
            <div
              class="bg-gray-200 w-[500px] h-4 sm:w-full md:w-full lg:w-full xl:w-full rounded-full"
            >
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

  <!-- ///////////////////////// section skills ///////////////////// -->
  <section class="py-16">
    <div class="text-center sm:text-center">
      <h4 class="font-bold text-2xl text-blue-600">Services</h4>
      <h1 class="text-4xl font-bold py-5">
        Exploring My Design <span class="text-blue-600">Skills</span>
      </h1>
      <p>
        We transform your ideas into a distinctive web project that both
        inspires
        <br />
        you and captivates your customers
      </p>
    </div>

    <!-- les buton du slider -->
    <div
      class="flex justify-end items-center sm:flex sm:justify-center md:flex md:justify-center md:items-center lg:flex lg:justify-end gap-3 py-10 px-20"
    >
      <div class="h-7 w-7 rounded-full bg-blue-600"></div>
      <div class="h-7 w-7 rounded-full bg-blue-600"></div>
    </div>
    <!-- les cards -->
    <div
      class="flex flex-col gap-3 justify-center items-center sm:flex sm:flex-col sm:justify-center sm:items-center md:flex md:flex-row lg:flex lg:flex-row md:justify-around py-10 px-20"
    >
      <div
        class="w-full md:w-80 lg:w-80 xl:w-80 2xl:w-80 bg-blue-600 text-white p-5 rounded"
      >
        <img src="../assets/image/icon.png" alt="" />
        <h1 class="text-2xl font-bold">
          Website / App Design <br />
          UX / UI Design
        </h1>
        <p class="py-4">
          Creating Engaging Digital Experiences <br />
          for Websites and Apps through UX/UI <br />
          Design
        </p>
        <span>Learn more</span>
      </div>
      <div class="w-full md:w-80 lg:w-80 text-blue-600 border p-5 rounded">
        <img src="../assets/image/icon.png" alt="" />
        <h1 class="text-2xl font-bold">
          Website / App Design <br />
          UX / UI Design
        </h1>
        <p class="py-4">
          Creating Engaging Digital Experiences <br />
          for Websites and Apps through UX/UI <br />
          Design
        </p>
        <span>Learn more</span>
      </div>
      <div class="w-full md:w-80 lg:w-80 text-blue-600 border p-5 rounded">
        <img src="../assets/image/icon.png" alt="" />
        <h1 class="text-2xl font-bold">
          Website / App Design <br />
          UX / UI Design
        </h1>
        <p class="py-4">
          Creating Engaging Digital Experiences <br />
          for Websites and Apps through UX/UI <br />
          Design
        </p>
        <span>Learn more</span>
      </div>
    </div>
  </section>
  <!-- ///////////////////////// section skills ///////////////////// -->

  <!-- //////////////////////// Section Milestones ////////////////// -->
  <section class="bg-blue-600 text-center py-10">
    <div>
      <h4 class="font-bold text-2xl text-white">Our Milestones</h4>
      <h1 class="text-4xl text-white font-bold py-5">
        What sets our studio apart <br />
        for your projects?
      </h1>
    </div>
    <div
      class="flex-col gap-4 flex justify-around sm:flex sm:flex-col md:flex md:flex-row lg:flex lg:flex-row xl:flex xl:flex-row py-10 px-20"
    >
      <div class="bg-white p-5 rounded">
        <h1 class="font-bold text-3xl">8000+</h1>
        <p>
          Figma ipsum component <br />
          variant main layer. Hand.
        </p>
      </div>
      <div class="bg-white p-5 rounded">
        <h1 class="font-bold text-3xl">100%</h1>
        <p>
          Figma ipsum component <br />
          variant main layer. Hand.
        </p>
      </div>
      <div class="bg-white p-5 rounded">
        <h1 class="font-bold text-3xl">3.5K</h1>
        <p>
          Figma ipsum component <br />
          variant main layer. Hand.
        </p>
      </div>
      <div class="bg-white p-5 rounded">
        <h1 class="font-bold text-3xl">240+</h1>
        <p>
          Figma ipsum component <br />
          variant main layer. Hand.
        </p>
      </div>
    </div>
  </section>
  <!-- //////////////////////// Section Milestones ////////////////// -->

  <!-- //////////////////////// Section portfolio ////////////////// -->
  <section>
    <div class="text-center py-5">
      <h4 class="font-bold text-2xl text-blue-600">Our projects</h4>
      <h1 class="text-4xl font-bold py-5">
        Presenting My Design <br />
        Portfolio and Case Studies
      </h1>
    </div>
    <div
      class="flex-col gap-3 flex md:flex-row md:justify-center lg:flex-row lg:justify-center xl:flex-row xl:justify-center items-center justify-center"
    >
      <div class="flex gap-2">
        <button class="h-10 bg-blue-600 text-white font-bold rounded-full w-32">
          All
        </button>
        <button
          class="h-10 border-2 border-blue-600 text-bleu-600 font-bold rounded-full w-32"
        >
          UI/UX Design
        </button>
      </div>
      <div class="flex gap-2">
        <button
          class="h-10 border-2 border-blue-600 text-bleu-600 font-bold rounded-full w-44"
        >
          Branding Design
        </button>
        <button
          class="h-10 border-2 border-blue-600 text-bleu-600 font-bold rounded-full w-32"
        >
          Wordpress
        </button>
      </div>
    </div>

    <div class="">
      <div
        class="flex-col gap-4 flex justify-around sm:flex sm:flex-col md:flex md:flex-row lg:flex lg:flex-row xl:flex xl:flex-row py-10 px-20"
      >
        <img
          src="../assets/image/preview2.png"
          alt=""
          style="height: 396px; height: 356px"
        />
        <img
          src="../assets/image/preview1.png"
          alt=""
          style="height: 396px; height: 356px"
        />
        <img
          src="../assets/image/preview3.png"
          alt=""
          style="height: 396px; height: 356px"
        />
      </div>
      <div
        class="flex-col gap-4 flex justify-around sm:flex sm:flex-col md:flex md:flex-row lg:flex lg:flex-row xl:flex xl:flex-row py-10 px-20"
      >
        <img
          src="../assets/image/preview4.png"
          style="height: 396px; height: 356px"
        />
        <img
          src="../assets/image/preview5.png"
          style="height: 396px; height: 356px"
        />
        <img
          src="../assets/image/preview6.png"
          style="height: 396px; height: 356px"
        />
      </div>
    </div>
  </section>
  <!-- //////////////////////// Section portfolio ////////////////// -->

  <!-- //////////////////////// Section temoignage ////////////////// -->
  <section class="py-10 px-20">
    <div>
      <div class="text-center">
        <h4 class="font-bold text-2xl text-blue-600">Testimonials</h4>
        <h1 class="text-4xl font-bold py-5">The Trust From Clients</h1>
      </div>
    </div>
    <div class="flex justify-center gap-5 py-7">
      <div class="h-7 w-7 rounded-full bg-blue-600"></div>
      <div class="h-7 w-7 rounded-full bg-blue-600"></div>
    </div>
    <div class="">
      <div
        class="flex-col w- gap-5 flex justify-between md:flex-row lg:flex-row xl:flex-row 2xl:flex-row"
      >
        <div class="border border-gray-200 p-7 rounded">
          <div class="flex justify-center items-center">
            <img class="" src="../assets/image/Ellipse 3.png" alt="" />
          </div>
          <div class="flex justify-center items-center text-yellow-400 pt-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <p class="py-3">
            Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet
            tellus eget egestas. Enim ultrices dictumst tortor in eget neque
            vestibulum potenti tempus
          </p>
          <div class="text-center">
            <h4 class="font-bold">Savannah Nguyen</h4>
            <p>President of Sales</p>
          </div>
        </div>
        <div class="border border-gray-200 p-7 rounded">
          <div class="flex justify-center items-center">
            <img class="" src="../assets/image/Ellipse 3.png" alt="" />
          </div>
          <div class="flex justify-center items-center text-yellow-400 pt-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <p class="py-3">
            Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet
            tellus eget egestas. Enim ultrices dictumst tortor in eget neque
            vestibulum potenti tempus
          </p>
          <div class="text-center">
            <h4 class="font-bold">Savannah Nguyen</h4>
            <p>President of Sales</p>
          </div>
        </div>
        <div class="border border-gray-200 p-7 rounded">
          <div class="flex justify-center items-center">
            <img class="" src="../assets/image/Ellipse 3.png" alt="" />
          </div>
          <div class="flex justify-center items-center text-yellow-400 pt-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <p class="py-3">
            Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet
            tellus eget egestas. Enim ultrices dictumst tortor in eget neque
            vestibulum potenti tempus
          </p>
          <div class="text-center">
            <h4 class="font-bold">Savannah Nguyen</h4>
            <p>President of Sales</p>
          </div>
        </div>
        <div class="border border-gray-200 p-7 rounded">
          <div class="flex justify-center items-center">
            <img class="" src="../assets/image/Ellipse 3.png" alt="" />
          </div>
          <div class="flex justify-center items-center text-yellow-400 pt-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-6 h-6"
            >
              <path
                fill-rule="evenodd"
                d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <p class="py-3">
            Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet
            tellus eget egestas. Enim ultrices dictumst tortor in eget neque
            vestibulum potenti tempus
          </p>
          <div class="text-center">
            <h4 class="font-bold">Savannah Nguyen</h4>
            <p>President of Sales</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- //////////////////////// Section temoigne ////////////////// -->

  <!-- //////////////////////// Section contact ////////////////// -->
  <section class="bg-blue-600 py-10 px-20">
    <div class="text-center">
      <h4 class="text-2xl text-white pb-2">contact me</h4>
      <h1 class="text-4xl text-white font-bold">Request Free Consultancy</h1>
    </div>
    <div
      class="flex-col flex justify-center items-center gap-7 py-10 md:flex-row lg:flex-row xl:flex-row 2xl:flex-row"
    >
      <div class="bg-white md:w-1/3 rounded p-4">
        <div class="pb-7">
          <p class="font-bold">Hotline 24/7</p>
          <p class="text-xl font-bold">(+23) 5535 68 68</p>
        </div>
        <div>
          <p>
            <span class="font-bold">Address:</span>2972 Westheimer Rd. Santa
            Ana, Illinois 85486
          </p>
          <p><span class="font-bold">Email:</span>nevaeh.simmons@example.com</p>
          <p><span class="font-bold">Fax:</span>(702) 555-0122</p>
          <p>
            <span class="font-bold">Work Hour:</span>Mon - Sat: 9:00 - 18:00
          </p>
        </div>
      </div>
      <div class="pt-10">
        <div class="">
          <div class="flex gap-3">
            <input
              type="text"
              class="w-full h-10"
              name=""
              id=""
              placeholder="Name*"
            />
            <input
              type="text"
              class="w-full h-10"
              name=""
              id=""
              placeholder="Email Address*"
            />
          </div>
          <div class="py-2">
            <input
              type="text"
              class="w-full h-10"
              name=""
              id=""
              placeholder="How can we help you?"
            />
          </div>
          <div class="flex">
            <input
              type="text"
              class="w-full h-20"
              name=""
              id=""
              placeholder="How can we help you?"
            />
          </div>
        </div>
        <div>
          <div class="flex gap-6 text-xs p-2">
            <input
              type="checkbox"
              class="form-checkbox h-5 w-5 text-indigo-600"
            />
            <p>By submitting, i’m agreed to the Terms & Conditons</p>
          </div>
          <div>
            <button
              class="h-10 border-white text-white bg-blue-900 font-bold rounded-full w-44"
            >
              Request Now
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- //////////////////////// Section contact ////////////////// -->
</template>
