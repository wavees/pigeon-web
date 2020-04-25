<div style="width: 100%; height: 100vh; overflow: hidden;" class="flex">
  <!-- Sidebar -->
  <div style="height: 100vh; max-width: 18rem;" class="relative w-full">
    <div class="h-full bg-white rounded-r-lg shadow-lg flex flex-col items-center justify-start">
      <!-- Logotype -->

      <div class="my-4 w-full flex justify-center items-center">
        <div class="flex">
          <img style="width: 3vw; height: 3vw;" src="icons/logo/pigeon.svg" alt="Pigeon Logotype">
        </div>
        
        <p class="text-lg mx-2 font-bold">Pigeon</p>
      </div>

      <div class="my-2 flex">
        <div class="rounded-full relative mx-2" style="background-image: url('https://i.insider.com/5df126b679d7570ad2044f3e'); background-size: cover; background-position: center center; width: 3vw; height: 3vw;">
          <span class="absolute top-0 right-0 rounded-full bg-green-400" style="width: 1.2vw; height: 1.2vw; border: 4px solid white;"></span>
        </div>
        <div class="flex flex-col">
          <h2 class="text-base font-semibold">Владимир Владимирович</h2>

          <p class="text-sm">Telegram</p>
        </div>
      </div>
      
      <!-- Sidebar footer -->
      <div class="absolute inset-x-0 bottom-0 px-4">
        <!-- Other icons -->
        <div class="flex justify-around text-xs">
          <div class="flex flex-col justify-center items-center">
            <img style="width: 1.5vw; height: 1.5vw;" src="icons/gift.svg" alt="Apps">
            <p>Presents</p>
          </div>

          <div class="flex flex-col justify-center items-center">
            <img style="width: 1.5vw; height: 1.5vw;" src="icons/grid.svg" alt="Apps">
            <p>Apps</p>
          </div>
          
          <div class="flex flex-col justify-center items-center">
            <img style="width: 1.5vw; height: 1.5vw;" src="icons/settings.svg" alt="Apps">
            <p>Settings</p>
          </div>
        </div>

        <!-- My account -->
        <div class="my-4 flex w-full justify-start items-center relative">
          <div class="rounded-full relative mx-2" style="background-image: url('icons/daddy.png'); background-size: cover; background-position: center center; width: 3.2vw; height: 3.2vw;">
            <span class="absolute top-0 right-0 rounded-full bg-green-400" style="width: 1.2vw; height: 1.2vw; border: 4px solid white;"></span>
          </div>

          <div class="flex flex-col">
            <p class="text-base font-semibold">Далматинец из...</p>
            <p class="text-sm">🛀 Моет попу</p>
          </div>

          <!-- <div class="absolute inset-y-0 right-0 rounded-full bg-gray-200 hover:bg-gray-600 flex justify-center items-center p-2">
            <img style="width: 1.8vw; height: 1.8vw;" src="icons/chevron-right.svg" alt="">
          </div> -->
        </div>
      </div>
    </div>
  </div>
  
  <div style="width: 100%; height: 100vh;">
    <slot></slot>
  </div>

</div>