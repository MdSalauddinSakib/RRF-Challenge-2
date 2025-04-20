<template>
    <!-- Header -->
    <section class="bg-[#fff9f3] relative mb-[380px]">
        <!-- Navbar -->
        <div class="bg-[#fff9f3] sticky top-0 z-50">
            <nav class="container flex justify-between items-center pt-5 pb-2 px-6 text-lg ">
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
                                <div
                                    class="absolute z-10 hidden group-hover:block w-44 bg-white rounded-md shadow-lg px-2">
                                    <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">White
                                        -Label CMS</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Websiite
                                        Builder</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Blogging
                                        Platform</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Membership
                                        Sites</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">SEO</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Airtable
                                        Integration</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Integrations</a>
                                    <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">UI
                                        Blocks
                                    </a>
                                    <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">AI
                                        Text
                                        Generator</a>
                                    <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">AI
                                        Image
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
                                <div
                                    class="absolute z-10 hidden group-hover:block w-44 bg-white rounded-md shadow-lg px-2">
                                    <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Wall
                                        of
                                        Love</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Blog</a>
                                    <a href="#"
                                        class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Success
                                        Stories</a>
                                    <a href="#" class="block px-4 py-2 text-sm text-[#17134a] hover:bg-[#fff8e0]">Made
                                        in
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
        </div>
        <hr class="border-t border-gray-300" />
        <!-- Navbar End -->

        <!-- Hero area -->
        <header class="pt-16 container pb-72">
            <h1 class="text-[#17134a] font-bold text-center text-6xl leading-16">Build Websites with <br>
                the Power of AI</h1>
            <p class="text-[#45426e] text-2xl text-center my-5">It takes minutes to finish a website with Dorik, it's
                simple, intuitive <br>
                and can be easily learned by beginners</p>
            <div class="flex justify-center items-center gap-4 mt-8 text-[#45426e] text-lg font-bold">
                <p><i class="fa-regular fa-circle-check text-[#4b41bf]"></i> Landing Pages</p>
                <p><i class="fa-regular fa-circle-check text-[#4b41bf]"></i> AI Generated Content</p>
                <p><i class="fa-regular fa-circle-check text-[#4b41bf]"></i> Free Stock Images</p>
                <p><i class="fa-regular fa-circle-check text-[#4b41bf]"></i> Blogs</p>
                <p><i class="fa-regular fa-circle-check text-[#4b41bf]"></i> Web Analytics</p>
                <p><i class="fa-regular fa-circle-check text-[#4b41bf]"></i> White-Label CMS</p>
            </div>
            <div class="flex justify-center py-10">
                <div class="bg-image text-center w-80">
                    <a href="#"
                        class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-bold py-4 px-6 rounded cursor-pointer inline-block">
                        Try it Free <i class="fa-solid fa-angle-right"></i>
                    </a>
                </div>
            </div>

            <div class="text-[#45426e]">
                <div class="flex items-center justify-center gap-8">
                    <div class="flex items-center gap-4">
                        <p>Featured on:</p>
                        <img class="w-30 h-12 object-contain" src="../assets/img/usa-today.svg" alt="">
                    </div>
                    <img class="w-30 h-12 object-contain" src="../assets/img/CNN.webp" alt="">
                    <img class="w-30 h-12 object-contain" src="../assets/img/pcmag.svg" alt="">
                    <img class="w-30 h-12 object-contain" src="../assets/img/hubspot_logo.svg" alt="">
                    <img class="w-30 h-12 object-contain" src="../assets/img/usnews.svg" alt="">
                </div>
            </div>

            <div class="flex justify-center w-1/4 mx-auto py-11">
                <a class="" href="#"><img src="../assets/img/Leader.png" alt=""></a>
            </div>

            <div class="flex justify-center">
                <div class="rounded-2xl inline-block border-[16px] border-[#ede7e9]">
                    <video class="w-full max-w-3xl rounded-2xl" src="../assets/video/Dorik-AI-Intro.mp4" controls>
                    </video>
                </div>
            </div>
        </header>

        <div class="container bg-white absolute left-1/2 -bottom-1/5 transform -translate-x-1/2">
            <div class="p-4 text-[#45426e] flex gap-8">
                <div class="flex flex-col justify-center items-center text-center  w-1/3">
                    <img class="w-20 h-20 rounded-full" src="../assets/img/employe.webp" alt="">
                    <p class="text-lg">I can't tell you how much I love Dorik! <span class="font-bold bg-amber-100">I
                            can create beautiful
                            websites without even touching a line of code.</span></p>
                    <h2 class="font-bold text-[#17136d] text-lg">Oday Mashalla</h2>
                    <p>Design Director @ humblebee</p>
                </div>

                <div class="flex flex-col justify-center items-center text-center w-1/3">
                    <img class="w-20 h-20 rounded-full" src="../assets/img/employe2.jpeg" alt="">
                    <p class="text-lg"><span class="font-bold bg-amber-100">One of
                            the best website building tools.</span>Great product!!</p>
                    <h2 class="font-bold text-[#17136d] text-lg">Upen V.</h2>
                    <p>Founder @ Siteoly</p>
                </div>

                <div class="flex flex-col justify-center items-center text-center w-1/3">
                    <img class="w-20 h-20 rounded-full" src="../assets/img/employe2.jpeg" alt="">
                    <p class="text-lg">I'm so in love with this tool! <span class="font-bold bg-amber-100">Building
                            websites
                            has never been this FAST and EASY!</span></p>
                    <h2 class="font-bold text-[#17136d] text-lg">Laura Ang</h2>
                    <p>Design Fellow (ODD3), On Deck</p>
                </div>
            </div>
            <hr class="border-t border-gray-300 mt-11" />
            <div class="pt-11 text-[#17136d]">
                <div class="text-center">
                    <p class="font-semibold text-lg"><i class="fa-regular fa-heart text-red-400"></i> &nbsp; Loved by
                        cool people from</p>
                </div>
                <div class="flex justify-between flex-wrap gap-2 px-2 py-8  grayscale-100">
                    <img class="w-30 h-14 object-contain" src="../assets/img/netflix.png" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/flippa-logo.png" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/stanford.webp" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/iimcb.png" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/taptap.png" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/decathlon-logo.svg" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/no-code.jpeg" alt="">
                    <img class="w-30 h-14 object-contain" src="../assets/img/vivacom.svg" alt="">
                </div>
            </div>
        </div>
    </section>
    <section class="container bg-[#fff9f3] p-8 rounded-lg">
        <div class="flex items-center gap-8">
            <div class="w-1/2">
                <h2 class="text-[#17134a] text-5xl font-semibold">Transform Your Ideas <br> into Reality with AI</h2>
                <p class="text-lg text-[#45426E] py-4">Bring your creative vision to life with Dorik AI</p>
                <div class="flex flex-col gap-4">
                    <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Website Generation</p>
                    <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> AI-Generated Contents (Text
                        &
                        Images)</p>
                    <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Build Website in Any
                        Language</p>
                </div>
                <div class="mt-10 w-80">
                    <a href="#"
                        class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                        Try Dorik Now <i class="fa-solid fa-angle-right"></i>
                    </a>
                </div>
            </div>

            <div class="w-1/2">
                <img src="../assets/img/website-generation.png" alt="">
                <p class="text-center text-lg text-[#45426E]">Prompt: <i>"Build a website for my coffeeshop"</i></p>
            </div>
        </div>
        <hr class="border-t border-gray-300 my-11" />
        <div class="flex justify-between gap-4">
            <div class="flex-1">
                <i class="fa-solid fa-table-columns text-[#45426E] text-2xl"></i>
                <p class="my-4 text-[#17136a] font-semibold text-lg">Stunning Websites</p>
                <p class="text-[#45426E]">Type a prompt, get a full website using the <br> power of cutting-edge AI
                    technology</p>
            </div>
            <div class="flex-1">
                <i class="fa-regular fa-pen-to-square text-[#45426E] text-2xl"></i>
                <p class="my-4 text-[#17136a] font-semibold text-lg">Compelling Copies</p>
                <p class="text-[#45426E]">Generate all your website content in two <br> steps—a prompt & a click!</p>
            </div>
            <div class="flex-1">
                <i class="fa-solid fa-image text-[#45426E] text-2xl"></i>
                <p class="my-4 text-[#17136a] font-semibold text-lg">Pixel Perfect Images</p>
                <p class="text-[#45426E]">Type a prompt and generate the exact <br> image on your mind.</p>
            </div>
        </div>
    </section>
    <div class="mt-20">
        <section class="container bg-[#fdeff7] p-8 rounded-lg">
            <div class="flex items-center gap-8">
                <div class="w-1/2">
                    <h2 class="text-[#17134a] text-5xl font-semibold">No-Code Website <br> Builder
                    </h2>
                    <p class="text-lg text-[#45426E] py-4">Unleash your creativity with our easy-to-use and powerful
                        website builder.</p>
                    <div class="flex flex-col gap-4">
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Create websites in
                            minutes without any code</p>
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Say goodbye to lengthy
                            development time</p>
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Customize everything to
                            match your vision</p>
                    </div>
                    <div class="mt-10 w-80">
                        <a href="#"
                            class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                            Try Dorik Now <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>

                <div class="w-1/2">
                    <img src="../assets/img/no-code.png" alt="">
                </div>
            </div>
            <hr class="border-t border-gray-300 my-11" />
            <div class="flex justify-between gap-4">
                <div class="flex-1">
                    <i class="fa-solid fa-pen-nib text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Drag & Drop Builder</p>
                    <p class="text-[#45426E]">Drag-and-drop builder makes website <br> creation a breeze. No coding is
                        required.</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-cube text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Templates
                    </p>
                    <p class="text-[#45426E]">With pre-designed templates, you can <br> quickly build your website.
                    </p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-cubes-stacked text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">250+ UI Blocks</p>
                    <p class="text-[#45426E]">Pre-designed UI blocks to make your <br> building journey faster</p>
                </div>
            </div>
        </section>
    </div>
    <div class="mt-20">
        <section class="container bg-[#f1faf7] p-8 rounded-lg">
            <div class="flex items-center gap-8">
                <div class="w-1/2">
                    <h2 class="text-[#17134a] text-5xl font-semibold">White-Label CMS
                    </h2>
                    <p class="text-lg text-[#45426E] py-4">A complete solution to build websites under your brand for
                        your clients.</p>
                    <div class="flex flex-col gap-4">
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Add your own brand’s
                            logo and colors</p>
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Dedicated dashboard for
                            your client</p>
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Build anything from
                            blogs to directories</p>
                    </div>
                    <div class="mt-10 w-80">
                        <a href="#"
                            class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                            Try Dorik Now <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>

                <div class="w-1/2">
                    <img src="../assets/img/white-label.png" alt="">
                </div>
            </div>
            <hr class="border-t border-gray-300 my-11" />
            <div class="flex justify-between gap-4">
                <div class="flex-1">
                    <i class="fa-solid fa-pencil text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Built-in Blogging Platform</p>
                    <p class="text-[#45426E]">Build and publish blogs with all the features you need to rank on Google
                        and grow audience.</p>
                </div>
                <div class="flex-1">
                    <i class="fa-regular fa-clipboard text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">White Label Dashboard
                    </p>
                    <p class="text-[#45426E]">A white-label dashboard for your clients that you can brand as your own
                    </p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-money-bill-trend-up text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Client Billing</p>
                    <p class="text-[#45426E]">Send invoices and receive payments from your clients directly from your
                        dashboard.</p>
                </div>
            </div>
        </section>
    </div>
    <div class="my-20">
        <section class="container bg-[#eeebfa] p-8 rounded-lg">
            <div class="flex items-center gap-8">
                <div class="w-1/2">
                    <h2 class="text-[#17134a] text-5xl font-semibold">Build with Airtable Data</h2>
                    <p class="text-lg text-[#45426E] py-4">Bring your Airtable Data to beautiful interfaces with our
                        Airtable elements</p>
                    <div class="flex flex-col gap-4">
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Present your data from
                            Airtable into beautiful interfaces</p>
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Easy-to-use filter and
                            search option for your users</p>
                        <p class="text-[#45426e] font-medium"><i class="fa-solid fa-check"></i> Create blogs, job
                            boards, shops, profiles, and more</p>
                    </div>
                    <div class="mt-10 w-80">
                        <a href="#"
                            class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                            Try Dorik Now <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>

                <div class="w-1/2">
                    <img src="../assets/img/airtable.png" alt="">
                </div>
            </div>
            <hr class="border-t border-gray-300 my-11" />
            <div class="flex justify-between gap-4">
                <div class="flex-1">
                    <i class="fa-solid fa-table-columns text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Beautiful Layouts</p>
                    <p class="text-[#45426E]">Showcase your data in any layout, like the grid, table, job board, etc.
                    </p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-bolt text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Realtime Update
                    </p>
                    <p class="text-[#45426E]">Update data on Airtable and it will be updated on your website instantly
                    </p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-database text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Advanced Customization</p>
                    <p class="text-[#45426E]">Use Airtable as a data source in Dorik CMS and customize everything.</p>
                </div>
            </div>
        </section>

        <section class="container">
            <div class="my-20 flex gap-8 items-center">
                <div class="flex-1">
                    <h2 class="text-6xl text-[#17134a] font-bold">Join over 100k+ happy users from around the world!
                    </h2>
                    <div class="mt-10 w-80">
                        <a href="#"
                            class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                            Wall of Love <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>
                <div class="pt-11 text-[#17136d] flex-1">
                    <div class="text-center">
                        <p class="font-semibold text-lg"><i class="fa-regular fa-heart text-red-400"></i> &nbsp; Loved
                            by
                            cool people from</p>
                    </div>
                    <div class="flex justify-center flex-wrap gap-2 px-2 py-8">
                        <img class="w-26 h-14 object-contain" src="../assets/img/netflix.png" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/flippa-logo.png" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/stanford.webp" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/iimcb.png" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/taptap.png" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/decathlon-logo.svg" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/no-code.jpeg" alt="">
                        <img class="w-26 h-14 object-contain" src="../assets/img/vivacom.svg" alt="">
                    </div>
                </div>
            </div>
        </section>
    </div>

    <div class="my-20 bg-[#030521]">
        <section class="container py-26 text-white">
            <div>
                <h2 class="text-6xl font-semibold">Beautiful designs, <br> Endless possibilities</h2>
            </div>
            <div class="mt-20 flex justify-between gap-8">
                <div class="text-[#d1d0db] border border-blue-950 p-8 flex-1">
                    <a href="#" class="hover:text-white text-xl font-medium leading-10">Amazing Templates</a>
                    <p>100+ <span class="underline decoration-blue-500">Beautiful Templates</span></p>
                </div>
                <div class="text-[#d1d0db] border border-blue-950 p-8 flex-1">
                    <a href="#" class="hover:text-white text-xl font-medium leading-10">UI Blocks</a>
                    <p class="text-white">250+ <span class="underline decoration-blue-500">Stunning UI Blocks </span>
                    </p>
                </div>
                <div class="text-[#d1d0db] border border-blue-950 p-8 flex-1">
                    <a href="#" class="hover:text-white text-xl font-medium leading-10">Elements</a>
                    <p>20+ Elements</p>
                </div>
            </div>
        </section>
        <div>
            <img src="../assets/img/template-3.webp" alt="">
        </div>
    </div>
    <section class="container">
        <div class="mt-30 text-center">
            <h2 class="text-6xl font-semibold text-[#17134a] my-8">No Maintenance, More Freedom.</h2>
            <p class="text-[#51486e] text-xl">The perfect launchpad for your online presence</p>
        </div>
        <div class="mb-30">
            <div class="flex mt-11">
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17134a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17134a] font-bold my-2 text-2xl">Free SSL/HTTPS</h2>
                    <p>Every website built and hosted on our platform comes with a free SSL certificate issued by Let's
                        Encrypt</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17134a] font-bold my-2 text-2xl">Team Collaboration</h2>
                    <p>Collaborate with your team and get input on designs, feedback, or brainstorming sessions.</p>
                </div>
            </div>
            <div class="flex mt-11">
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
            </div>
            <div class="flex mt-11">
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
            </div>
            <div class="flex mt-11">
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class="flex-1">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-[#fff9f3] my-30">
        <div class="text-center py-20 flex flex-col justify-center items-center">
            <h2 class="text-6xl font-semibold text-[#17134a] my-8">Affordable Pricing</h2>
            <p class="text-[#51486e] text-xl">Start building your websites for free. Upgrade to any paid plans to unlock
                features like forms, <br> custom
                domains, and more.</p>
            <div class="mt-10 w-80">
                <a href="#"
                    class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                    See Pricing <i class="fa-solid fa-angle-right"></i>
                </a>
            </div>
        </div>
    </section>
</template>
