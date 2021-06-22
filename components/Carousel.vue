<template>
  <agile :options="myOptions">
    <div
      class="
        relative
        flex flex-col
        items-end
        text-right
        justify-center
        h-96
        bg-emerald-200
        text-white
        space-y-8
        slide
      "
    >
      <div class="absolute top-0 right-0 w-full h-full">
        <img
          src="/images/product6.jpg"
          alt=""
          class="w-full h-full object-cover"
        />
      </div>
      <h1 class="font-black text-3xl md:text-4xl lg:text-5xl max-w-lg z-10">
        Suspendisse interdum rutrum nise
      </h1>
      <p
        class="
          max-w-[35ch]
          text-2xl
          md:text-3xl
          lg:text-4xl lg:leading-14
          font-light
          z-10
        "
      >
        Lorem ipsum dolor sit amet consectetur adipisicing elit Vero voluptates
        cumque accusantium quas labore
      </p>
    </div>
    <div
      class="
        flex flex-col
        items-end
        text-right
        justify-center
        h-96
        bg-emerald-200
        text-white
        space-y-8
        px-6
        slide
        relative
      "
    >
      <div class="absolute top-0 right-0 w-full h-full">
        <img
          src="/images/product3.jpg"
          alt=""
          class="w-full h-full object-cover"
        />
      </div>
      <h1 class="font-black text-3xl md:text-4xl lg:text-5xl max-w-lg z-10">
        Suspendisse interdum rutrum nise
      </h1>
      <p
        class="
          max-w-[35ch]
          text-2xl
          md:text-3xl
          lg:text-4xl lg:leading-14
          font-light
          z-10
        "
      >
        Lorem ipsum dolor sit amet consectetur adipisicing elit Vero voluptates
        cumque accusantium quas labore
      </p>
    </div>
    <div
      class="
        flex flex-col
        items-end
        text-right
        justify-center
        h-96
        bg-emerald-200
        text-white
        space-y-8
        px-6
        slide
        relative
      "
    >
      <div class="absolute top-0 right-0 w-full h-full">
        <img
          src="/images/product4.jpg"
          alt=""
          class="w-full h-full object-cover"
        />
      </div>
      <h1 class="font-black text-3xl md:text-4xl lg:text-5xl max-w-lg z-10">
        Suspendisse interdum rutrum nise
      </h1>
      <p
        class="
          z-10
          max-w-[35ch]
          text-2xl
          md:text-3xl
          lg:text-4xl lg:leading-14
          font-light
        "
      >
        Lorem ipsum dolor sit amet consectetur adipisicing elit Vero voluptates
        cumque accusantium quas labore
      </p>
    </div>
  </agile>
</template>

<script>
export default {
  name: 'Carousel',
  data() {
    return {
      myOptions: {
        navButtons: false,
        autoplay: true,
      },
    }
  },
}
</script>

<style>
.agile {
  width: 100%;
}

.agile__actions {
  margin-top: 20px;
}

.agile__nav-button {
  background: transparent;
  border: none;
  color: #ccc;
  cursor: pointer;
  font-size: 24px;
  transition-duration: 0.3s;
}

.agile__nav-button:hover {
  color: #888;
}

.agile__dots {
  margin: 0 10px;
  width: 100%;
  display: flex;
  justify-content: center;
}

.agile__dots button {
  background-color: #14b8a6;
  border: none;
  border-radius: 50%;
  cursor: pointer;
  display: block;
  z-index: 9999;
  height: 10px;
  font-size: 0;
  line-height: 0;
  margin: 0.5rem;
  padding: 0.5rem;
  transition-duration: 0.3s;
  width: 10px;
}

.agile__dot--current button,
.agile__dot:hover button {
  background-color: #5eead4;
}

.slide {
  align-items: end;

  display: flex;

  justify-content: center;
}
</style>
