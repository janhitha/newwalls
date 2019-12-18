<template>

<div class="content-wrapper bg-background-primary font-sans text-copy-primary leading-normal flex flex-col min-h-screen">
    <header class="border-t-2 border-green-700">
      <nav class="container mx-auto flex flex-wrap justify-between items-center py-8">
        <ul
          class="uppercase tracking-wide font-bold w-full block flex-grow lg:flex lg:flex-initial lg:w-auto items-center mt-8 lg:mt-0"
          :class="isOpen ? 'block': 'hidden'"
        >
          <li class="mr-8 mb-6 lg:mb-0">
            <search-input />
          </li>
           <li class="mr-8 mb-6 lg:mb-0">
            <g-link to="/overview" class="text-copy-primary hover:text-gray-600">Overview</g-link>
          </li>
         <li class="relative mr-8 mb-6 lg:mb-0 group md:mb-0 flex sm:mb-12">
            <g-link class="text-copy-primary hover:text-gray-600" to="/location">Location</g-link>
         </li>
          <li class="mr-8 mb-6 lg:mb-0">
            <g-link to="/plans" class="text-copy-primary hover:text-gray-600">Plans</g-link>
          </li>
       <!--   <li class="mr-8 mb-6 lg:mb-0">
            <g-link to="/amenities" class="text-copy-primary hover:text-gray-600">Amenities</g-link>
          </li>
          <li class="mr-8 mb-6 lg:mb-0">
            <g-link to="/plans" class="text-copy-primary hover:text-gray-600">Plans</g-link>
          </li>
          <li>
            <g-link to="/loans" class="text-copy-primary hover:text-gray-600">Loan Approvals</g-link>
          </li> -->
          
        </ul>
      </nav>
    </header>



      <div>
      <slot/>
    </div>
</div>    
</template>

<style src="../css/main.css" />

