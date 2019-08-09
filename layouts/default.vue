<template>
  <div class="antialiased">
    <div class="max-w-5xl mx-auto px-6 md:px-8 text-lg sm:text-xl md:text-2xl lg:text-3xl md:font-light text-gray-700 leading-tight">
      <div>
        <div class="flex justify-between items-center mt-10"><h1
          class="text-lg sm:text-xl md:text-2xl lg:text-3xl text-gray-900 font-medium md:font-normal leading-none"><a
          href="/">Cory Rosenwald</a></h1>
          <div class="block lg:hidden">
            <button type="button">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M2 6H22V7H2V6ZM2 12H22V13H2V12ZM22 18H2V19H22V18Z" class="fill-current text-gray-900"></path>
              </svg> <!----></button>
          </div>
        </div>
        <div class="lg:block hidden">
          <div
            class="w-full block lg:flex lg:justify-between lg:border-b lg:border-gray-400 mt-10 text-gray-700 font-medium lg:text-lg">
            <div class="lg:flex -mb-px">
              <a href="/book" class="block pb-6 border-b border-transparent lg:mt-0 lg:mr-8 hover:text-gray-900">About</a>
              <a href="/projects" class="block pb-6 border-b border-transparent lg:mt-0 lg:mr-8 hover:text-gray-900">Projects</a>
              <a href="/interviews" class="block pb-6 border-b border-transparent lg:mt-0 lg:mr-8 hover:text-gray-900">Technology</a>
              <a href="/speaking" class="block pb-6 border-b border-transparent lg:mt-0 lg:mr-8 hover:text-gray-900">Uses</a>
            </div>
            <div class="lg:flex">
              <a href="https://www.instagram.com/steveschoger/"
                    class="block mt-6 lg:mt-0 lg:ml-8 flex align-center hover:text-gray-900">
                <div>Contact</div>
                <svg width="25" height="25" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg"
                     class="ml-1 -mt-px">
                  <path d="M16.5 13V18.5H6.5V8.5H12" stroke="#4A5568"></path>
                  <path d="M10 15L18.5 6.5" stroke="#4A5568"></path>
                  <path d="M14 6.5H18.5V11" stroke="#4A5568"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
      <nuxt/>
    </div>
  </div>
</template>
