<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import { ChevronLeftIcon, ChevronRightIcon } from '@heroicons/vue/20/solid'
</script>

<template>
  <!-- parent div -->
  <div class="mx-5 my-5">
    <!-- wallpaper | midafood -->
    <div class="bg-[url('/src/assets/midafood.png')] bg-cover h-[713px] relative">
      <!-- date -->
      <div class="bg-[#ff2c2c] h-20 w-20 transform -skew-x-6 absolute -bottom-5 ml-16">
        <div class="uppercase py-2 flex flex-col text-center justify-center">
          <p class="font-semibold text-white text-4xl">13</p>
          <p class="font-normal tracking-wider text-white text-md">jan</p>
        </div>
        <div class="absolute -right-1 -mt-5">
          <img
            src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAX0lEQVR4nO3Pyw1AUBRFUSY0oBFDbepEQWpZxoJ434F4J7nTtXO7ru2zw4ipFj5gw1ITVzzgjJcNuOLlAu7xMgHPeH7gBc8LBODpgUA8LRCBxwfQY8UeeHP0B21tP9wBjQNMtpuYiBgAAAAASUVORK5CYII="
          />
        </div>
      </div>
      <!-- end of date -->
      <!-- share button/link -->
      <div>
        <a href="" class="absolute -bottom-5 -my-7 right-4 flex text-sm pt-5 uppercase"
          ><span>
            <img
              class="mr-1"
              src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABkAAAAZCAYAAADE6YVjAAAACXBIWXMAAAsTAAALEwEAmpwYAAABE0lEQVR4nO3UsSuFURzG8Y8rw5VsUohJqbuYWZVN6u6SKHURKTab2eBKWZTRIPkLTCYlBjYsJCXFYLx66wy3m3jf1z2D8q2znJ7ze/qd33MO//yTkWkURaaGCwzENlnFA0ZjmiSM4xmLmkALSihjoc4kYRDX2EFbnuKlcPgJVzjAFlYadJ04wSm60hZvRxX3WEp5sIBN3GH4J3F3SE41mGVlD7ffCTpwieUcxQtpO9nHdsNea5jNBCpYx3zemYyENoshTZM4whsecYZj7P4mXUnBWYzhPKzk2oa+0Na/kyR5c1LQixdshESVQzdNffEVfISh96TQ10KnfTJwiNcMH95Mnl/4Bmsi847+2CZTsQ38eT4Bui47yuCZUlAAAAAASUVORK5CYII="
            />
          </span>
          share
        </a>
      </div>
      <!-- end of share button -->
    </div>
    <!-- end of wallpaper | midafood -->
    <!-- divider -->
    <div class="flex-grow border-b border-gray-300 py-8"></div>
    <!-- end of divider -->

    <!-- body -->
    <div>
      <article class="pb-12">
        <p class="text-[#ff2c2c] font-semibold text-md">Darwin tumaneng</p>
        <H1 class="font-bold text-4xl">
          Toyota Mobility Solutions PH empowers seafood wholesaler Mida Food with digital logistics
          platform.
        </H1>

        <p class="py-4 text-xl">
          Logistics Platform addresses limitations in Mida Food's delivery operations.
        </p>

        <a href="">
          <span class="uppercase font-bold underline tracking-tight underline-offset-2">
            Read article
          </span>
        </a>
      </article>
    </div>
    <!-- end of body -->

    <!-- pagination -->
    <div class="flex items-center justify-center bg-white py-3">
      <div class="hidden sm:flex sm:flex-1 sm:items-center sm:justify-between">
        <div>
          <nav class="isolate inline-flex -space-x-px rounded-md shadow-sm" aria-label="Pagination">
            <a
              href="#"
              class="relative inline-flex items-center rounded-l-md px-2 py-2 text-gray-400 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              <span class="sr-only">Previous</span>
              <ChevronLeftIcon class="h-5 w-5" aria-hidden="true" />
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              1</a
            >
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              2</a
            >
            <a
              href="#"
              class="relative hidden items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0 md:inline-flex"
              >...</a
            >
            <span
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-700 ring-1 ring-inset ring-gray-300 focus:outline-offset-0"
            >
              8
            </span>
            <a
              href="#"
              class="relative hidden items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0 md:inline-flex"
              >9</a
            >
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
              >10</a
            >
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 bg-[#ff2c2c] text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              11
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              12
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              13
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              14
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              ...
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              56
            </a>
            <a
              href="#"
              class="relative inline-flex items-center px-4 py-2 text-sm font-semibold text-gray-900 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              57
            </a>
            <a
              href="#"
              class="relative inline-flex items-center rounded-r-md px-2 py-2 text-gray-400 ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus:z-20 focus:outline-offset-0"
            >
              <span class="sr-only">Next</span>
              <ChevronRightIcon class="h-5 w-5" aria-hidden="true" />
            </a>
          </nav>
        </div>
      </div>
    </div>
    <!-- end of pagination -->
  </div>
  <!-- end of parent div -->
</template>
