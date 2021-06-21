<template>
  <div class="row">
    <header>
      <div
        class="
          hidden
          lg:flex
          justify-center
          bg-gradient-to-t
          from-emerald-100
          to-cyan-100
        "
      >
        <div
          class="
            flex
            justify-between
            items-center
            w-11/12
            lg:max-w-7xl
            py-1
            text-teal-600 text-sm
            font-semibold
          "
          data-title="top-bar"
        >
          <div class="flex-1">Social media sharing links</div>
          <nav class="flex-2 flex lg:space-x-6 xl:space-x-10 justify-end">
            <ul>
              <li>
                <a href="">Login</a>
              </li>
              <li>|</li>
              <li>
                <a href="">Register</a>
              </li>
            </ul>
            <ul>
              <li>
                <a href="" class="font-bold">0 items</a>
              </li>
              <li>|</li>
              <li>
                <a href="">Chceckout </a>
              </li>
            </ul>
            <ul class="top-menu">
              <li>
                <a href="">About</a>
              </li>
              <li>
                <a href="">Partner Program </a>
              </li>
              <li>
                <a href="">Franchise </a>
              </li>
              <li>
                <a href="">How to Order </a>
              </li>
              <li>
                <a href="">Contact </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
      <div
        class="
          flex flex-col
          justify-center
          py-6
          space-y-4
          mx-auto
          w-11/12
          lg:max-w-7xl
        "
      >
        <div class="hidden lg:flex justify-end">
          <form action="#">
            <div class="flex relative max-w-max items-center">
              <input type="text" id="search" class="border-1 border-gray-200" />
              <img
                src="/images/icons/search.svg"
                alt=""
                class="absolute right-0 w-5 h-5"
              />
            </div>
          </form>
        </div>
        <div class="flex justify-between items-center">
          <div class="flex-1">
            <img src="/images/logo.png" alt="" class="w-60" />
          </div>
          <div class="my-2 px-2 lg:hidden flex flex-row">
            <div class="lg:hidden self-end flex flex-1 w-full">
              <button
                id="nav-toggle"
                class="text-first"
                aria-haspopup="true"
                aria-expanded="false"
                aria-controls="menu"
                aria-label="Burger-area"
              >
                <img
                  :class="[
                    'open align-end h-10 w-10',
                    { hidden: toggle === true },
                  ]"
                  src="/images/icons/open.svg"
                  alt="Burger ouvert"
                  @click="toggle = !toggle"
                />
                <img
                  :class="[
                    'open align-end h-10 w-10',
                    { hidden: toggle === false },
                  ]"
                  src="/images/icons/close.svg"
                  alt="Burger fermé"
                  @click="toggle = !toggle"
                />
              </button>
            </div>
          </div>
          <nav class="hidden lg:flex flex-1 justify-end">
            <ul class="flex space-x-10 text-xl text-teal-500 font-light">
              <li>
                <NuxtLink to="/">
                  <img src="/images/icons/home.svg" alt="" class="w-5 h-5" />
                </NuxtLink>
              </li>
              <li>
                <a href="">CUPS </a>
              </li>
              <li>
                <a href="">SPOONS </a>
              </li>
              <li>
                <a href="">LIDS </a>
              </li>
              <li>
                <a href="">ACCESSORIES </a>
              </li>
              <li>
                <a href="">MARKETING </a>
              </li>
            </ul>
          </nav>
        </div>
        <div
          :class="[
            ' absolute top-24 text-teal-500 block  opacity-100 bg-white shadow-lg right-[5] p-10 z-20 w-11/12 rounded-2xl transition-all delay-100 duration-500 ease-in-out',
            { 'opacity-0 hidden': toggle === false },
          ]"
          data-title="mobile-menu"
        >
          <nav
            class="
              menu-mobile
              flex flex-col
              sm:flex-row sm:space-x-6
              md:space-x-12
              space-y-4
              sm:space-y-0
            "
          >
            <ul>
              <li>
                <a href="">Login</a>
              </li>

              <li>
                <a href="">Register</a>
              </li>
            </ul>
            <ul>
              <li>
                <a href="" class="font-bold">0 items</a>
              </li>

              <li>
                <a href="">Chceckout </a>
              </li>
            </ul>
            <ul>
              <li>
                <a href="">About</a>
              </li>
              <li>
                <a href="">Partner Program </a>
              </li>
              <li>
                <a href="">Franchise </a>
              </li>
              <li>
                <a href="">How to Order </a>
              </li>
              <li>
                <a href="">Contact </a>
              </li>
            </ul>

            <ul class="text-xl text-teal-500 font-light">
              <li>
                <a href="">CUPS </a>
              </li>
              <li>
                <a href="">SPOONS </a>
              </li>
              <li>
                <a href="">LIDS </a>
              </li>
              <li>
                <a href="">ACCESSORIES </a>
              </li>
              <li>
                <a href="">MARKETING </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  data() {
    return {
      toggle: false,
    }
  },
}
</script>

<style scoped>
header ul li {
  display: inline;
}
header .top-menu li {
  /* prefer add style for all header li either than adding a class for each */

  padding: 0 0 0 1rem;
}

.menu-mobile ul li {
  display: block;
}
</style>
