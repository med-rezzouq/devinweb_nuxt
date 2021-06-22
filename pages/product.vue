<template>
  <div class="flex flex-col items-center">
    <div
      class="
        grid grid-cols-1
        lg:grid-cols-11
        justify-center
        items-center
        mx-auto
        gap-x-2
        lg:gap-x-2
        gap-y-6
        text-teal-500
        py-6
        lg:py-12
        w-11/12
        lg:max-w-7xl
      "
    >
      <div class="breadcrumb flex items-center flex-wrap lg:col-span-11">
        <NuxtLink to="/">Home</NuxtLink> &nbsp;&#x3e;&nbsp;<NuxtLink
          to="/category"
          >Category Name </NuxtLink
        >&nbsp;&#x3e;&nbsp;<NuxtLink to="/product">Product Name </NuxtLink>
      </div>

      <div class="flex flex-col flex-1 lg:col-span-5">
        <div
          class="
            h-[250px]
            sm:h-[300px]
            md:h-[450px]
            lg:h-[400px]
            bg-emerald-100
            w-full
          "
        >
          <img src="/images/product6.jpg" alt="" class="w-full h-full" />
        </div>
        <div class="flex justify-center space-x-3 mt-3 flex-wrap">
          <div class="h-20 sm:h-24 md:h-32 lg:h-28 bg-emerald-100 flex-1">
            <img src="/images/product6.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="h-20 sm:h-24 md:h-32 lg:h-28 bg-emerald-100 flex-1">
            <img src="/images/product6.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="h-20 sm:h-24 md:h-32 lg:h-28 bg-emerald-100 flex-1">
            <img src="/images/product6.jpg" alt="" class="w-full h-full" />
          </div>
          <div class="h-20 sm:h-24 md:h-32 lg:h-28 bg-emerald-100 flex-1">
            <img src="/images/product6.jpg" alt="" class="w-full h-full" />
          </div>
        </div>
      </div>
      <div class="flex flex-col flex-1 lg:col-span-6 self-stretch">
        <div
          class="
            grid grid-cols-1
            lg:grid-cols-3
            mx-auto
            gap-x-6
            lg:gap-x-6
            gap-y-6
            text-teal-500
            w-11/12
            lg:max-w-7xl
          "
        >
          <div class="lg:col-span-3">
            <h1 class="text-4xl font-bold">5oz Frozen Yogurt Cups</h1>
            <p class="text-lg">Lorem ipsum dolor sit subtitle</p>
            <hr />
          </div>

          <div class="lg:col-span-2 space-y-4">
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed
              consequuntur debitis nulla.
            </p>

            <p class="text-lg max-w-[30ch]">
              Packaged in 1,000 cups per case standard double PE coating
            </p>

            <div
              class="
                h-28
                w-4/5
                bg-emerald-100
                flex flex-col
                justify-center
                items-center
                space-y-6
                px-3
                py-16
              "
            >
              <h2 class="text-xl font-bold">Custom Print Service Available.</h2>
              <button
                class="
                  col-span-2
                  mt-3
                  text-white
                  bg-teal-500
                  block
                  max-w-max
                  text-lg
                  px-6
                  py-1
                  rounded-[3px]
                "
              >
                Learn More
              </button>
            </div>

            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente
              explicabo reiciendis eaque. Assumenda, saepe nulla voluptatum
              dolorem porro quam consectetur!
            </p>
          </div>
          <div class="lg:col-span-1">
            <div class="grid grid-cols-2 gap-3 items-center">
              <b>Price</b> <b>$119</b>

              <b>Quantity</b>
              <input
                type="text"
                id="newsleter"
                class="block border-1 border-teal-500"
              />
              <b>Color</b> <span>White</span>
              <button
                class="
                  col-span-2
                  mt-3
                  font-bold
                  text-white
                  bg-teal-500
                  block
                  text-xl
                  md:text-2xl
                  max-w-max
                  px-4
                  py-3
                  rounded-[8px]
                "
              >
                Add to Cart
              </button>

              <p class="col-span-2">Share this</p>
            </div>
          </div>
        </div>
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
      <div
        class="
          grid grid-cols-1
          md:grid-cols-2
          lg:grid-cols-4
          justify-start
          items-start
          lg:mx-auto
          gap-x-6 gap-y-6
          lg:gap-x-10 lg:gap-y-10
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
            "
          >
            You may also be interested in&nbsp;:
          </h2>
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
