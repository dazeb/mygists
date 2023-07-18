```
<template>
    <header class="bg-white dark:bg-slate-900 drop-shadow-sm">
        <!-- The header section of the navbar -->
        <div class="max-w-screen-xl px-4 mx-auto sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="md:flex md:items-center md:gap-12">
                    <!-- The logo and heading section of the navbar -->
                    <a class="block text-teal-600" href="/">
                        <span class="sr-only">Home</span>
                        <img
                            class="w-10 h-max"
                            src="/assets/rocket.png"
                            alt="Logo"
                        />
                        <a
                            class="hidden -m-3 text-2xl font-black text-gray-900 transition align md:block hover:text-gray-500/75"
                            href="/"
                        >
                            Heading
                        </a>
                    </a>
                </div>

                <div class="hidden pl-14 md:block">
                    <!-- The navigation links section of the navbar -->
                    <nav aria-label="Global">
                        <ul class="flex items-center gap-6 pl-10 text-sm">
                            <li>
                                <NuxtLink
                                    class="text-gray-500 transition hover:text-gray-500/75"
                                    to="/"
                                >
                                    About
                                </NuxtLink>
                            </li>

                            <li>
                                <NuxtLink
                                    class="text-gray-500 transition hover:text-gray-500/75"
                                    to="/"
                                >
                                    Careers
                                </NuxtLink>
                            </li>

                            <li>
                                <NuxtLink
                                    class="text-gray-500 transition hover:text-gray-500/75"
                                    to="/"
                                >
                                    History
                                </NuxtLink>
                            </li>

                            <li>
                                <NuxtLink
                                    class="text-gray-500 transition hover:text-gray-500/75"
                                    to="/"
                                >
                                    Services
                                </NuxtLink>
                            </li>

                            <li>
                                <NuxtLink
                                    class="text-gray-500 transition hover:text-gray-500/75"
                                    to="/"
                                >
                                    Projects
                                </NuxtLink>
                            </li>

                            <li>
                                <NuxtLink
                                    class="text-gray-500 transition hover:text-gray-500/75"
                                    to="/"
                                >
                                    Blog
                                </NuxtLink>
                            </li>
                        </ul>
                    </nav>
                </div>
                <div class="flex items-center gap-4">
                    <!-- The search bar and color mode button section of the navbar -->
                    <SearchBar />
                    <ColorModeButton />
                    <GrometIconsGithub />
                </div>
            </div>
        </div>
    </header>
</template>
```
