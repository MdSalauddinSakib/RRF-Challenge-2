<template>
    <!-- Header -->
    <section class="bg-[#fff9f3]">
        <!-- Navbar -->
        <nav class="container flex justify-between items-center pt-5 pb-2 px-6 text-lg">
            <!-- logo -->
            <div class="logo w-22 cursor-pointer">
                <img src="../assets/img/dorik-logo.svg" alt="Logo" />
            </div>
            <!-- Navigation links -->
            <div class="text-lg font-medium">
                <ul class="nav-links flex items-center gap-5 text-[#17134a]">
                    <li class="hover:text-[#3a30ba]"><a href="#home">Dorik AI</a></li>
                    <li class="hover:text-[#3a30ba]">
                        <div class="relative inline-block text-left group">
                            <!-- Dropdown Button -->
                            <a href="#" class="inline-flex justify-center items-center w-full focus:outline-none">
                                Product
                                <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" stroke-width="2"
                                    viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
                                </svg>
                            </a>

                            <!-- Dropdown Content -->
                            <div class="absolute z-10 hidden group-hover:block w-44 bg-white rounded-md shadow-lg px-2">
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">White
                                    -Label CMS</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Websiite
                                    Builder</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Blogging
                                    Platform</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Membership
                                    Sites</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">SEO</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Airtable
                                    Integration</a>
                                <a href="#"
                                    class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Integrations</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">UI Blocks
                                </a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">AI Text
                                    Generator</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">AI Image
                                    Generator</a>
                            </div>
                        </div>
                    </li>
                    <li class="hover:text-[#3a30ba]"><a href="#contact">
                            Templates</a></li>
                    <li class="hover:text-[#3a30ba]"><a href="#services">
                            Pricing</a></li>
                    <li class="hover:text-[#3a30ba]">
                        <div class="relative inline-block text-left group">
                            <!-- Dropdown Button -->
                            <a href="#" class="inline-flex justify-center items-center w-full focus:outline-none">
                                Resources
                                <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" stroke-width="2"
                                    viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
                                </svg>
                            </a>

                            <!-- Dropdown Content -->
                            <div class="absolute z-10 hidden group-hover:block w-44 bg-white rounded-md shadow-lg px-2">
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Wall of
                                    Love</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Blog</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Success
                                    Stories</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Made in
                                    Dorik</a>
                                <a href="#"
                                    class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Documentation</a>
                                <a href="#"
                                    class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Community</a>
                                <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Video
                                    Tutorials</a>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
            <!-- Login / Sign up btn -->
            <div class="flex items-center gap-4">
                <a href="#" class="text-[#3a30ba]">Login</a>
                <a href="#" class="text-[#3a30ba] border border-[#3a30ba] px-4 py-2 rounded-md">Sign Up</a>
            </div>
        </nav>

    </section>
    <hr class="border-t border-gray-300" />
</template>
