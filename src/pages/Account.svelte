  <div style="width: 100%; height: 100vh" class="relative bg-gray-100 flex">
    <div style="width: 25rem; max-width: 25rem;" class="py-6 px-6 relative">
      <div class="w-full my-4 flex justify-center items-center">
        <h1 class="text-lg font-semibold">My Account</h1>
      </div>

      <!-- Account settings -->
      <div class="flex flex-col justify-start items-center">
        <!-- General -->
        <div style="border-radius: 30px;" class="flex my-2 px-6 py-2 bg-white">
          <!-- <img class="fill-current text-indigo-400" src="/icons/user.svg" alt="User Icon"> -->
          <div class="flex items-center justify-center">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#673AB7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-user block"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
          </div>

          <div class="mx-2">
            <h2>General</h2>
            <p class="text-xs">Avatar, Username, Status</p>
          </div>
        </div>

        <!-- Security -->
        <div class="flex my-2 px-4 py-2">
          <img src="/icons/shield.svg" alt="User Icon">

          <div class="mx-2">
            <h2>Security</h2>
            <p class="text-xs">Change Password, Email</p>
          </div>
        </div>
      </div>

      <div class="py-2 absolute inset-x-0 bottom-0 text-center w-full">
        <p style="font-size: 0.6em;" class="text-gray-700">Web-App version: 0.0.1 DEV; © Wavees Group, 2020</p>
      </div>
    </div>
    
    <!-- MAIN PAGE -->
    <div style="width: 100%; height: 100vh;" class="w-full py-8 relative bg-white">
      <div class="w-full text-center">
        <h1 class="text-2xl font-semibold">General Settings</h1>
      </div>

      <!-- Avatar -->
      <div class="w-full px-6 md:px-12 my-6 flex">
        <div class="rounded-full relative mx-2" style="background-image: url('icons/daddy.png'); background-size: cover; background-position: center center; width: 8vw; height: 8vw;">
          <div style="background-color:rgba(0, 0, 0, 0.5);" class="w-full h-full flex justify-center items-center rounded-full">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-upload"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="17 8 12 3 7 8"></polyline><line x1="12" y1="3" x2="12" y2="15"></line></svg>
          </div>
        </div>
        
        <div class="mx-4 relative">
          <p class="text-lg font-semibold">Username:</p>
          <p>Далматинец из далматинцев</p>
        
          
          <!-- <div class="absolute inset-x-0 bottom-0 text-sm flex"> -->
            <!-- <p class="mx-4">Change avatar only on this site</p> -->
            <!-- <p class="mx-4">Delete avatar</p> -->
          <!-- </div> -->
        </div>
      </div>
    </div>
  </div>