<template>
  <LocomotiveScroll
    ref="scroller"
    :getted-options="{
      offset: ['30%', 0],
      direction: 'vertical',
      smooth: true,
      getSpeed: true,
      lerp: 0.1
    }" class="bg-black text-white pb-4">
    <main class="w-screen">
      <section class="w-full h-screen relative bg-[url('~/assets/hero.jpg')] bg-cover bg-center px-12">
        <Nav />
        <div class="absolute sm:bottom-12 bottom-24 sm:left-12 left-0 sm:px-0 px-9 sm:w-2/3 w-full text-white">
          <h1 class="font-bold text-4xl sm:text-5xl lg:text-7xl mb-4">
            <span>Digital Product Design and Development Agency</span>
          </h1>
          <p class="sm:w-1/2 w-full">
            <span>
              Axer Studios is a digital product design and
              development agency working with
              ambitious companies to craft tailor-made
              brands and digital experiences.
            </span>
          </p>
        </div>
        <h1 class="absolute bottom-12 right-12 text-white"><a href="mailto:hey@axerstudios.com">hey@axerstudios.com</a></h1>
      </section>
      <section class="w-full pt-36">
        <div class="px-12 sm:px-28 relative">
          <h1 class="font-bold text-4xl sm:text-5xl lg:text-8xl mb-24">
            <span>Featured</span>
          </h1>
          <p class="sm:w-1/2 lg:w-2/5 sm:mb-24 ml-auto font-sans text-xl">
            Our transparency showcased in these projects in our goal to pursue empathy in our client works.
          </p>
          <div class="w-full mb-20 mt-20 sm:mt-0">
            <div class="card w-full sm:w-1/2 h-80 sm:h-[85vh] relative">
              <div class="absolute h-full w-full bg-gray-900 opacity-40"></div>
              <div class="absolute left-0 bottom-0 -translate-y-8 translate-x-8 z-50">
                <h1 class="font-bold text-2xl sm:text-4xl lg:text-6xl mb-2">Roomxix</h1>
                <p class="font-sans text-sm">Fashion Agency Site</p>
              </div>
              <img src="~/assets/raamin-ka-uR51HXLO7G0-unsplash.jpg" class="w-full h-full object-cover " alt="">
            </div>
          </div>
          <div class="w-full">
            <div class="card w-full sm:w-1/2 ml-auto h-80 sm:h-[85vh] relative">
              <div class="absolute h-full w-full bg-gray-900 opacity-40"></div>
              <div class="absolute left-0 bottom-0 -translate-y-8 translate-x-8 z-50">
                <h1 class="font-bold text-2xl sm:text-4xl lg:text-6xl mb-2">NCDC Coronavirus</h1>
                <p class="font-sans text-sm">Nigeria Covid-19 Site</p>
              </div>
              <img src="~/assets/diego-san-2hRHb1OGRYs-unsplash.jpg" class="w-full h-full object-cover" alt="">
            </div>
          </div>
        </div>
      </section>
      <section class="w-full h-screen flex justify-center items-center text-center relative">
        <div class="absolute h-64 w-56 bg-white left-12 bottom-0 lg:block hidden">
          <img src="~/assets/alex-sh-n5DSvj6xZ5k-unsplash.jpg" class="w-full h-full object-cover" alt="">
        </div>
        <div class="absolute h-64 w-56 bg-white right-12 bottom-1/2 lg:block hidden">
          <img src="~/assets/alex-sh-Q325PHMtpVI-unsplash.jpg" class="w-full h-full object-cover" alt="">
        </div>
        <div class="absolute h-64 w-56 bg-white left-48 bottom-3/4 lg:block hidden">
          <img src="~/assets/alex-sh-tahjhrbznXw-unsplash.jpg" class="w-full h-full object-cover" alt="">
        </div>
        <div class="w-3/5">
            <h1 class="font-sans text-xl text-gray-400">
              We work with empathy in mind, we apply strategic and design thinking in solving these common design problems.
              We work to deliver the best we can and put in our work experience and expertise and this has caused so many instances of <span class="text-white"><b>customer retention</b></span>
              Our <span class="text-white"><b>product adoption</b></span> at the very end shows that we are here for you and your interest at large. How <span class="text-white"><b>effective</b></span> our work is cannot be 
              comparable to any. Our topmost priority is your <span class="text-white"><b>satisfaction</b></span> and that is what we live for.
            </h1>
        </div>
      </section>
    </main>
  </LocomotiveScroll>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
