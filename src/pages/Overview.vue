<template>
  <Layout>
    <div
      class="w-full flex flex-row flex-wrap bg-gray-600 p-10 py-20 justify-center"
      style="background-repeat: no-repeat; background-attachment: fixed; background-blend-mode: multiply;background-position: center center;background-image: url('building1.jpg');"
    >
      <div class="w-full text-center">
        <div class="text-3xl text-center text-white antialiased">On Going Projects</div>
      </div>
    </div>

    <Projectlayout>
     <div class="bg-gray-200 flex">
      <div class="px-8 py-6 max-w-md mx-auto sm:max-w-xl lg:max-w-full lg:w-1/2 lg:py-24 lg:px-12">
        <div class="xl:max-w-lg xl:ml-auto">
          <g-image class="mt-6 rounded-lg shadow-xl sm:mt-8 sm:w-full sm:object-cover sm:object-center lg:hidden" 
                   src='../../static/tavish.jpeg' />
          <h1 class="mt-6 text-2xl font-bold text-gray-900 leading-tight sm:mt-8 sm:text-4xl lg:text-3xl xl:text-4xl">
            Key Highlights </h1>
            <br class="hidden lg:inline"><span class="text-indigo-500">Super spacious residences in the heart of the city</span>
         <ul class="list-disc mt-2 text-gray-600 ">
            <li>16 limited edition homes with 1 car park each</li>
            <li>G+3 Total Floors</li>
            <li>Fully customisable interiors</li>
         </ul> 
          <div class="mt-4 sm:mt-6">
            <g-link to="/contact" class="btn btn-indigo shadow-lg sm:text-base">For booking pls contact</g-link>
          </div>
        </div>
      </div>
      <div class="hidden lg:block lg:w-1/2 lg:relative justify-center rounded">
        <g-image class="absolute  object-cover object-center" src="../../static/tavish.jpeg" />
      </div>
     
    </div>
    
    </Projectlayout>
  </Layout>
</template>