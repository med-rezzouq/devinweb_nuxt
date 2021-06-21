<template>
  <div class="flex flex-col items-center">
    <!--  slider -->
    <main class="carousel-slider py-6 lg:py-12 w-11/12 lg:max-w-7xl">
      <client-only placeholder="Carousel loading...">
        <carousel />
      </client-only>
    </main>
    <!-- fin de slider -->

    <div
      class="
        grid grid-cols-1
        md:grid-cols-2
        lg:grid-cols-3
        justify-center
        items-center
        mx-auto
        gap-x-6
        lg:gap-x-10
        gap-y-6
        text-teal-500
        py-6
        lg:py-12
        w-11/12
        lg:max-w-7xl
      "
    >
      <div class="flex items-center justify-center h-52 bg-emerald-200">
        <i class="font-black text-2xl md:text-3xl lg:text-4xl">Banner one</i>
      </div>

      <div class="flex items-center justify-center h-52 bg-emerald-200">
        <i class="font-black text-2xl md:text-3xl lg:text-4xl">Banner two</i>
      </div>

      <div class="flex items-center justify-center h-52 bg-emerald-200">
        <i class="font-black text-2xl md:text-3xl lg:text-4xl">Banner three</i>
      </div>
    </div>
    <!-- ///////////// -->

    <div
      class="
        grid grid-cols-1
        md:grid-cols-2
        lg:grid-cols-4
        justify-center
        items-center
        mx-auto
        w-11/12
        gap-x-6 gap-y-6
        lg:max-w-7xl lg:gap-x-10 lg:gap-y-10
        py-6
        lg:py-12
      "
    >
      <div class="lg:col-span-4 md:col-span-2">
        <h2
          class="
            text-teal-500 text-2xl
            md:text-3xl
            lg:text-4xl
            font-bold
            max-w-max
            mx-auto
          "
        >
          Featured Products
        </h2>
      </div>
      <div class="flex flex-col items-center justify-center space-y-3">
        <div class="bg-emerald-200 h-60 w-full"></div>
        <div class="flex justify-between text-teal-500">
          <a href="" class="flex-2 font-medium"
            >Vestibulum tincidunt tellus a metus hendrer</a
          >
          <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
        </div>
        <NuxtLink to="/product" class="text-white bg-teal-500 py-[0.3rem] px-4">
          Add to Cart
        </NuxtLink>
      </div>

      <div class="flex flex-col items-center justify-center space-y-3">
        <div class="bg-emerald-200 h-60 w-full"></div>
        <div class="flex justify-between text-teal-500">
          <a href="" class="flex-2 font-medium"
            >Vestibulum tincidunt tellus a metus hendrer</a
          >
          <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
        </div>
        <NuxtLink to="/product" class="text-white bg-teal-500 py-[0.3rem] px-4">
          Add to Cart
        </NuxtLink>
      </div>

      <div class="flex flex-col items-center justify-center space-y-3">
        <div class="bg-emerald-200 h-60 w-full"></div>
        <div class="flex justify-between text-teal-500">
          <a href="" class="flex-2 font-medium"
            >Vestibulum tincidunt tellus a metus hendrer</a
          >
          <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
        </div>
        <NuxtLink to="/product" class="text-white bg-teal-500 py-[0.3rem] px-4">
          Add to Cart
        </NuxtLink>
      </div>

      <div class="flex flex-col items-center justify-center space-y-3">
        <div class="bg-emerald-200 h-60 w-full"></div>
        <div class="flex justify-between text-teal-500">
          <a href="" class="flex-2 font-medium"
            >Vestibulum tincidunt tellus a metus hendrer</a
          >
          <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
        </div>
        <NuxtLink to="/product" class="text-white bg-teal-500 py-[0.3rem] px-4">
          Add to Cart
        </NuxtLink>
      </div>

      <div class="flex justify-center py-10 lg:col-span-4 md:col-span-2">
        <a href="/products"
          ><img src="/images/icons/right-arrow.svg" alt="" class="w-10 h-10"
        /></a>
      </div>
    </div>

    <!-- ///////////// -->
  </div>
</template>

<script>
import Carousel from '~/components/Carousel.vue'
export default {
  components: {
    Carousel,
  },
}
</script>

<style></style>
