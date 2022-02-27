<template>
  <div class="" id="landing-page">
  <div class="min-h-screen bg-gradient-to-br from-transparent to-purple-200">
    <div class=" p-6  max-w-6xl mx-auto flex justify-between ">
      <p class="text-xl font-semibold tracking-tighter">Nairobi Hot Girls</p>
      <div class="hidden md:flex space-x-3">
        <a href=""><p class="text-red-600 border-b-2  border-black hover:bg-white p-2 rounded-t-md">About</p></a>
        <a href=""><p class=" hover:bg-white p-2 rounded-t-md">Pricing</p></a>
        <a href=""><p class=" hover:bg-white p-2 rounded-t-md">Terms of Service</p></a>
        <a href=""><p class=" hover:bg-white p-2 rounded-t-md">Add Me</p></a>
        <div class="flex items-center bg-red-200 p-2 rounded-lg">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
          </svg>
          <p class="text-xs ml-1 mr-2 font-semibold">Add Me</p>
        </div>
      </div>
      <div class="flex items-center bg-red-200 p-2 rounded-lg md:hidden">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
          </svg>
           <p class="text-xs ml-1 mr-2 my-1 font-semibold">Add Me</p>
        </div>
  </div>

  <div class="relative h-screen md:hidden">
    <img class="absolute top-0 left-0 right-0 object-cover h-full w-full" src="https://img.freepik.com/free-photo/sexy-girl-woman-red-white-streak-panties-body-part_186202-7290.jpg?w=996" alt="">
    <div class="absolute top-16 left-3 right-3 flex flex-col bg-black bg-opacity-25 rounded-lg shadow-md">
      <div class="p-8">
        <p class="text-3xl font-semibold leading-4">I'm a</p>
        <div class="flex space-x-5">
          <div class="border border-gray-300 h-12 w-1/2 p-2 mt-5 rounded-lg flex justify-between items-center shadow-md">
           <p class="text-sm">Male</p>
           <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
          </div>
          <div class="border border-red-300 h-12 w-1/2  p-2 mt-5 rounded-lg flex justify-between items-center shadow-md">
           <p class="text-sm">Female</p>
           <!-- <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6  " fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg> -->
          </div>
        </div>
        <label for="company-size" class="block text-sm font-medium text-gray-700 mt-6">Find me</label>
          <div class="mt-1">
            <select name="company-size" id="company-size" class=" w-full border border-gray-300 px-1 py-3 rounded-lg shadow-sm focus:outline-none focus:border-gray-400 focus:ring-1 focus:ring-red-400">
              <option value="">Options</option>
              <option value="small">Females Near Me</option>
            </select>
          </div>
            <button class="border p-3 w-full mt-5 ring-white bg-red-200 rounded-lg text-black">
              Continue
            </button>
            <div class="flex items-center">
          <input id="terms-and-privacy" name="terms-and-privacy" type="checkbox" class="rounded border-green-500 text-green-800 focus:ring-1 focus:ring-black" />
          <label for="terms-and-privacy" class="ml-2 block text-sm text-gray-900"
            >I agree to the
            <a href="#" class="text-indigo-600 hover:text-indigo-500">Terms</a>
            and
            <a href="#" class="text-indigo-600 hover:text-indigo-500">Privacy Policy</a>.
          </label>
        </div>
      </div>
      
      </div>
  
  </div>

  <!-- <div class="hidden flex flex-col px-8 mt-9">
    <div class="w-full  relative">
      <img class="absolute top-0 object-cover h-28" src="https://img.icons8.com/color/344/filled-like.png" alt="">
      <div class="absolute top-16 left-0 right-0 flex flex-col">
      <p class="text-3xl font-semibold leading-4">I'm a</p>
        <div class="flex space-x-5">
          <div class="border border-gray-300 h-12 w-1/2 p-2 mt-5 rounded-lg flex justify-between items-center shadow-md">
           <p class="text-sm">Male</p>
           <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
          </div>
          <div class="border border-red-300 h-12 w-1/2  p-2 mt-5 rounded-lg flex justify-between items-center shadow-md">
           <p class="text-sm">Female</p>
          </div>
        </div>
        
      </div>
    </div>
  </div> -->

   <div id="" class="hidden p-6  max-w-6xl mx-auto md:grid grid-cols-2">
    <div class="flex flex-col relative p-8">
      <img class="absolute top-0 object-cover h-28" src="https://img.icons8.com/color/344/filled-like.png" alt="">
      <img class="absolute right-60 top-0 object-cover h-28 rotate-45" src="https://img.icons8.com/color/344/filled-like.png" alt="">
      <img class="absolute left-0 bottom-0 object-cover h-28 -rotate-45" src="https://img.icons8.com/color/344/filled-like.png" alt="">
      <img class="absolute top-0 h-28" src="https://img.icons8.com/external-kmg-design-detailed-outline-kmg-design/344/external-love-love-kmg-design-detailed-outline-kmg-design-2.png" alt="">
      <img class="absolute bottom-0 right-60 h-28" src="https://img.icons8.com/external-kmg-design-detailed-outline-kmg-design/344/external-love-love-kmg-design-detailed-outline-kmg-design-2.png" alt="">
 <!-- absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 -->
      <div class=" absolute top-1/2 left-1/4 right-1/4 transform -translate-x-1/2 -translate-y-1/2 w-2/3">
        <p class="text-3xl font-semibold leading-4">I'm a</p>
        <div class="flex space-x-5">
          <div class="border border-gray-300 h-12 w-1/2 p-2 mt-5 rounded-lg flex justify-between items-center shadow-md">
           <p class="text-sm">Male</p>
           <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
          </div>
          <div class="border border-red-300 h-12 w-1/2  p-2 mt-5 rounded-lg flex justify-between items-center shadow-md">
           <p class="text-sm">Female</p>
           <!-- <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6  " fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg> -->
          </div>
        </div>
        <div>
          <label for="company-size" class="block text-sm font-medium text-gray-700 mt-6">Find me</label>
          <div class="mt-1">
            <select name="company-size" id="company-size" class=" w-full border border-gray-300 px-1 py-3 rounded-lg shadow-sm focus:outline-none focus:border-gray-400 focus:ring-1 focus:ring-red-400">
              <option value="">Options</option>
              <option value="small">Females Near Me</option>
            </select>
          </div>
        </div>
        <button class="border p-3 w-full mt-5 ring-white bg-red-200 rounded-lg text-black">
          Continue
        </button>
      </div>
    </div>
    <div class="flex flex-col justify-center items-center w-full">
      <!-- <img class="h-96 w-96 object-cover rounded-full" src="https://img.freepik.com/free-photo/woman-with-beautiful-body_144627-37972.jpg?w=740" alt=""> -->
      <img class="h-96 w-96 object-cover rounded-full" src=" https://img.freepik.com/free-photo/beautiful-sexy-girl-with-tattoo-body-portrait-young-adult-woman-girl-with-brown-hair-sexy-female-with-nude-body-covers-breast-with-arms_186202-4548.jpg?w=740" alt="">
     
      <p class="mt-8 text-2xl">Register</p>
      <p class="text-xs">Get connected to the guys near you</p>
      <div class="max-w-md flex justify-center space-x-1 mt-3">
        <div class="rounded-full h-2 w-2 bg-gray-600">
        </div>
        <div class="rounded-full h-2 w-2 bg-red-600">
        </div>
      </div>
    </div>
  </div>
  </div>
  
</div>
</template>

<script>


export default {
  name: 'Home',
  components: {
    
  }
}
</script>
