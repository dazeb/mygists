```
<template>
  <div>
    <header class="bg-white border-b-2 border-gray-100 dark:bg-gray-900">
      <div class="mx-auto max-w-screen-xl px-4 sm:px-6 lg:px-8">
        <div class="flex h-16 items-center justify-between">
          <div class="md:flex md:items-center md:gap-12">
            <NuxtLink to="/">
              <img src="@/assets/logo.png" class="h-8" alt="Logo" />
            </NuxtLink>
          </div>

          <div class="hidden md:block">
            <nav aria-label="Global">
              <div class="flex items-center gap-2 text-sm">
                <SearchBar />
              </div>
            </nav>
          </div>

          <div class="flex items-center gap-4">
            <div class="sm:flex sm:gap-4">
              <a
                class="rounded-md bg-blue-600 px-5 py-2 text-sm font-medium text-white shadow"
                href="/"
              >
                Login
              </a>

              <!-- <div class="hidden sm:flex">
                <a
                  class="rounded-md bg-gray-100 px-5 py-2.5 text-sm font-medium text-teal-600"
                  href="/"
                >
                  Register
                </a>
              </div> -->
              <ColorModeButton />
            </div>

            <div class="block md:hidden">
              <button
                class="rounded bg-gray-100 p-2 text-gray-600 transition hover:text-gray-600/75"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M4 6h16M4 12h16M4 18h16"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </header>
    <nuxt />
  </div>
</template>

```
