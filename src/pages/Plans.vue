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
       <div class="container mx-auto">
        <h1 class="mt-6 text-2xl font-bold text-gray-900 leading-tight sm:mt-8 sm:text-4xl lg:text-3xl xl:text-4xl">
            Floor Plan </h1>
        <div class="mt-0">    
            <g-image class="object-fill object-center " src="../../static/plan1.jpg" />
     </div>  
       <div class="mt-0">
          <g-image class="object-fill object-center " src="../../static/plan2.jpg" />
       </div>
       </div>  

    </Projectlayout>
  </Layout>
</template>    