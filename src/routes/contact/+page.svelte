
<style>
    *{
      font-family: "Cambay", sans-serif;
    font-weight: 700;
    font-style: normal;
    }
    *::selection{
        display: none;
    }
  </style>
  <script>

    import myImage from '$lib/Designer.png'
      const backgroundColor = '#000000';
      const headingColor = '#1dcd8d'
  </script>

  <div class="fixed inset-0 items-center" style="background-color: {backgroundColor}">
    <!-- Navbar -->
      <nav
          class="relative flex w-full flex-nowrap items-center justify-between py-4 lg:flex-wrap lg:justify-start lg:py-8 lg:px-7" data-twe-navbar-ref>
          <div class="flex w-full flex-wrap items-center justify-between px-3">
              <button
                  class="block  bg-transparent px-2 text-black/50 hover:no-underline hover:shadow-none focus:no-underline focus:shadow-none focus:outline-none focus:ring-0 dark:text-neutral-200 lg:hidden"
                  type="button"
                  data-twe-collapse-init
                  data-twe-target="#navbarSupportedContent7"
                  aria-controls="navbarSupportedContent7"
                  aria-expanded="false"
                  aria-label="Toggle navigation"
              >
                  <!-- Hamburger icon -->
                  <span class="[&>svg]:w-7 [&>svg]:stroke-black/50 dark:[&>svg]:stroke-neutral-200">
                      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                          <path
                              fill-rule="evenodd"
                              d="M3 6.75A.75.75 0 013.75 6h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 6.75zM3 12a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 12zm0 5.25a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75a.75.75 0 01-.75-.75z"
                              clip-rule="evenodd"
                          />
                      </svg>
                  </span>
              </button>

              <!-- Collapsible navbar container -->
              <div class="!visible mt-2 hidden flex-grow basis-[100%] items-center lg:mt-0 lg:!flex lg:basis-auto" id="navbarSupportedContent7"data-twe-collapse-item>
                  <!-- Left links -->
                  <ul
                      class="list-style-none ms-auto flex flex-col ps-0 lg:mt-1 lg:flex-row"
                      data-twe-navbar-nav-ref
                  >
                      <!-- Home link -->
                      <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
                          <a
                              class="text-black dark:text-white lg:px-2 text-xl"
                              aria-current="page"
                              href="/"
                              data-twe-nav-link-ref>HOME</a
                          >
                      </li>
            <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
                          <a
                              class="text-black dark:text-white lg:px-2 text-xl"
                              aria-current="page"
                              href="about"
                              data-twe-nav-link-ref>ABOUT</a
                          >
                      </li>
            <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
                          <a
                              class="text-black dark:text-white lg:px-2 text-xl"
                              href="service"
                              data-twe-nav-link-ref>SERVICES</a
                          >
                      </li>
            <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
                          <a
                              class="text-black dark:text-white lg:px-2 text-xl"
                              href="why-us"
                              data-twe-nav-link-ref>WHY US</a
                          >
                      </li>
            <li class="my-4 ps-2 lg:my-0 lg:pe-1 lg:ps-2" data-twe-nav-item-ref>
                          <a
                              class="text-black dark:text-white lg:px-2 text-xl"
                              href="contact"
                              data-twe-nav-link-ref>CONTACT US</a
                          >
                      </li>
                  </ul>
              </div>
          </div>
      </nav>
      <div class=" h-20">
          <h1 class="px-12 py-5 text-5xl" style="color: {headingColor};">Contact Us</h1>
      </div>
      <div class=" h-screen flex">
        <div class=" h-4/6 w-full">
            <img src="{myImage}" alt="" class="object-contain h-full w-full">
        </div>
        <div class=" h-full w-full">
            <div class="py-24 px-4 flex-col">
                <div class=" h-10 flex items-center text-3xl justify-between" style="color: {headingColor};">PHONE</div>
                <div class=" text-2xl justify-between" style="color: white;">+91 9883697525</div>
                <div class=" text-2xl justify-between" style="color: white;">+91 9832494606</div>
                <div class=" h-10 flex items-center justify-between text-3xl" style="color: {headingColor};">EMAIL</div>
                <div class=" text-xl justify-between" style="color: white;">studiotwentyfiebusiness@gmail.com</div>
                <div class=" text-xl justify-between" style="color: white;">priyanshugupta0047@gmail.com</div>
                <div class=" h-10 flex items-center justify-between text-3xl" style="color: {headingColor};">SOCIAL</div>
                <div class=" h-12 w-36 flex justify-between">
                    <a href="/" class="h-full w-full flex items-center px-1 text-white text-2xl hover:text-green-500 cursor-pointer"><i class="fa-brands fa-facebook-f"></i></a>
                    <a href="/" class="h-full w-full flex items-center px-1 text-white text-2xl hover:text-green-500 cursor-pointer"><i class="fa-brands fa-twitter"></i></a>
                    <a href="/" class="h-full w-full flex items-center px-1 text-white text-3xl hover:text-green-500 cursor-pointer"><i class="fa-brands fa-instagram"></i></a>
                </div>
            </div>
        </div>
      </div>
  </div>
