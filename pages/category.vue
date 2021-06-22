<template>
  <div class="flex flex-col items-center">
    <div
      class="
        grid grid-cols-1
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
      <div class="breadcrumb flex items-center">
        <NuxtLink to="/">Home</NuxtLink> &nbsp;&#x3e;&nbsp;<NuxtLink
          to="/category"
          >Category Name
        </NuxtLink>
      </div>

      <div class="flex items-center h-40 bg-emerald-200 pl-4">
        <h1 class="font-black text-2xl md:text-3xl lg:text-4xl">
          Category Banner
        </h1>
      </div>
    </div>
    <!-- ///////////// -->

    <div
      class="
        flex flex-col
        lg:flex-row lg:justify-between lg:space-x-12
        xl:space-x-30
        w-11/12
        lg:max-w-7xl
        py-6
        lg:py-12
        space-y-10
        lg:space-y-0
      "
    >
      <div class="flex flex-col space-y-8 lg:w-1/4 text-teal-500">
        <div class="">
          <h3
            class="text-xl font-bold bg-emerald-200 py-1 pl-2 max-w-max pr-10"
          >
            FILTER NAME
          </h3>
          <ul class="mt-2 space-x-4 lg:space-x-0">
            <li class="inline lg:block">
              <a href="">Option One </a>
            </li>
            <li class="inline lg:block">
              <a href="">Second Option </a>
            </li>
            <li class="inline lg:block">
              <a href="">Another Option </a>
            </li>
            <li class="inline lg:block">
              <a href="">Last Option </a>
            </li>
          </ul>
        </div>

        <div class="mt-6">
          <h3
            class="text-xl font-bold bg-emerald-200 py-1 pl-2 max-w-max pr-10"
          >
            FILTER NAME
          </h3>
          <ul class="mt-2 space-x-4 lg:space-x-0">
            <li class="inline lg:block">
              <a href="">Option One </a>
            </li>
            <li class="inline lg:block">
              <a href="">Second Option </a>
            </li>
            <li class="inline lg:block">
              <a href="">Another Option </a>
            </li>
            <li class="inline lg:block">
              <a href="">Last Option </a>
            </li>
          </ul>
        </div>
      </div>
      <div
        class="
          grid grid-cols-1
          md:grid-cols-2
          lg:grid-cols-3
          justify-start
          items-start
          lg:mx-auto
          gap-x-6 gap-y-6
          lg:gap-x-10 lg:gap-y-10 lg:w-3/4
        "
      >
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product6.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product5.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product3.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product2.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product6.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product1.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product7.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product2.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
        <div class="flex flex-col items-center justify-center space-y-3">
          <div class="bg-emerald-200 h-60 w-full">
            <img src="/images/product4.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="flex justify-between text-teal-500">
            <a href="" class="flex-2 font-medium"
              >Vestibulum tincidunt tellus a metus hendrer</a
            >
            <span class="flex-1 text-right font-bold"> $&nbsp;199.29 </span>
          </div>
          <NuxtLink
            to="/product"
            class="text-white bg-teal-500 py-[0.3rem] px-4"
          >
            Add to Cart
          </NuxtLink>
        </div>
      </div>
    </div>

    <!-- ///////////// -->
  </div>
</template>

<script>
export default {}
</script>

<style></style>
