<script>
  import { goto } from "@sapper/app"
</script>

<svelte:head>
  <title>Pigeon Messenger</title>
  <script src="js/panelTilt.js"></script>
</svelte:head>

<style>
*, *::before, *::after {
    box-sizing: inherit;
}
.wrapper {
    -moz-box-align: center;
    -moz-box-pack: center;
    align-items: center;
    display: flex;
    height: 100%;
    justify-content: center;
    padding: 5vh 5%;
    width: 100%;
}
.panel {
    -moz-user-select: none;
    display: flex;
    height: 466px;
    pointer-events: none;
    position: relative;
    width: 100%;
}
.panel__img-col {
    box-shadow: 0 20px 100.28px 8.72px rgba(0, 0, 0, 0.35);
    /* flex-basis: 70%; */
}
</style>

<div style="width: 100%; height: 100vh; overflow: hidden" class="bg-gray-100 relative">
  <!-- HEADER -->
  <div class="flex w-full justify-center lg:justify-between px-12 py-2 md:py-4">
    <!-- Logo -->
    <div class="flex justify-center items-center">
      <img style="width: 2rem; heigth: 2rem;" src="icons/logo/pigeon.svg" alt="Pigeon Messenger logo">
      
      <p class="hidden lg:block text-xl mx-2 font-bold">Pigeon Messenger</p>
    </div>

    <!-- Menu list -->
    <div class="hidden lg:flex text-sm items-center justify-center">
      <p class="mx-4">About</p>
      <p class="mx-4">Features</p>
      <p class="mx-4">App store</p>
      <p class="mx-4">Contact</p>

      <!-- Download and Switch to app buttons -->

      <!-- goto('/app'); -->
      <button on:click={(e) => {
        
      }} class="mx-4 px-4 py-2 bg-blue-500 rounded-full text-white">
        🧰 App is in Development
      </button>
    </div>
  </div>

  <!-- HERO WITH NEWS -->
  <div class="w-full items-center px-4 md:px-24 lg:px-32">

    <div class="wrapper">	
      <div class="panel">
        <div style="width: 100%; background-image: url('background.png'); background-size: cover; background-position: center center;" class="rounded-lg shadow-xl w-full py-6 md:py-32 px-8 py-6 panel__img-col"> 
          <div class="max-w-xs">
            <h1 class="text-3xl font-semibold">💻 Application is in development</h1>
            <p>Pigeon Messenger enters the development stage. Soon we will be posting news to our new blog, which is about to appear...</p>
          
            <button class="my-6 text-sm flex items-center">
              <p>Read more</p><img style="width: 1.4em; height: 1.4em;" class="mx-2" src="icons/arrow-right.svg" alt="Right arrow">
            </button>
          </div>          
        </div>
      </div>
    </div>

    <!-- <div style="background-image: url('background.png'); background-size: cover; background-position: center center;" class="rounded-lg shadow-xl w-full py-6 md:py-32 px-8 py-6">
      <div class="max-w-xs">
        <h1 class="text-3xl font-semibold">💻 Application is in development</h1>
        <p>Pigeon Messenger enters the development stage. Soon we will be posting news to our new blog, which is about to appear...</p>
      
        <button class="my-6 text-sm flex items-center">
          <p>Read more</p><img style="width: 1.4em; height: 1.4em;" class="mx-2" src="icons/arrow-right.svg" alt="Right arrow">
        </button>
      </div>
    </div> -->
  </div>

  <!-- FOOTER -->

  <div class="w-full flex justify-between px-4 absolute inset-x-0 bottom-0">
    <p class="logotype text-xl" style="font-weight: 600;">Wavees</p>

    <div class="flex text-sm">
      <p class="mx-2">Projects</p>
      <p class="mx-2">About</p>
      <p class="mx-2">Contact</p>
    </div>
  </div>

  <!-- HERO -->
  <!-- <div class="bg-white rounded-lg shadow-lg px-12 py-6">
    <div class="flex my-6 justify-center items-center">
      <img style="width: 3.5vw; heigth: 3.5vw;" src="icons/logo/pigeon.svg" alt="Pigeon Messenger logo">
      
      <div>
        <p class="text-2xl mx-2 font-bold">Pigeon Messenger</p>
        <p class="text-sm">🌊 Dive into new Messenging Dimension!</p>
      </div>
    </div>
    
    New thing in this Big Internet

    <div>
      <p>Register for updates</p>

      <input type="email" placeholder="email" />
      <button class="mt-4 bg-transparent text-base text-dark font-semibold py-2 px-4 border border-solid hover:border-transparent rounded">
        😥 Registers disabled
      </button>
    </div>
  </div>

  <div class="w-full flex justify-between px-4 absolute inset-x-0 bottom-0">
    <p class="logotype text-xl" style="font-weight: 600;">Wavees</p>

    <div class="flex text-sm text-white">
      <p class="mx-2">Projects</p>
      <p class="mx-2">About</p>
      <p class="mx-2">Contact</p>
    </div>
  </div> -->
</div>