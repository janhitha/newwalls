<template>
<div class="flex justify-center w-full object-fill .divparentclass .VueCarousel-pagination { position: absolute; display: block; paginationPosition: bottom-overlay }">
 <ClientOnly>
 <carousel  :autoplay="true" :perPage="1" :centerMode="true" :paginationPosition="bottom-overlay" class="VueCarousel-slide">
   <slide>
     <g-image class="rounded-lg flex-shrink-0 w-full h-64 object-fill object-center" src="../../static/building.jpg" style="min-height: 60vh" />
    </slide>
	<slide >
     <g-image class="rounded-lg flex-shrink-0 w-full h-64 object-fill object-center" src="../../static/building1.jpg" style="min-height: 60vh" />
    </slide>
    <slide>
     <g-image class="rounded-lg flex-shrink-0 w-full h-64 object-fill object-center" src="../../static/interior.jpg" style="min-height: 60vh" />
    </slide>
	<slide >
     <g-image class="rounded-lg flex-shrink-0 w-full h-64 object-fill object-center" src="../../static/kitchen.jpg" style="min-height: 60vh" />
    </slide>
 </carousel>
 </ClientOnly>
 </div>
</template>


<script>


export default {
   metaInfo: {
    title: 'New Walls'
  },
 components: {
      Carousel: () =>
        import ('vue-carousel')
        .then(m => m.Carousel)
        .catch(),
      Slide: () =>
        import ('vue-carousel')
        .then(m => m.Slide)
        .catch()
    },
};
</script>

<style scoped>
.VueCarousel-slide {
  visibility: visible;
  flex-basis: 100%;
  width: 100%;
}
</style>