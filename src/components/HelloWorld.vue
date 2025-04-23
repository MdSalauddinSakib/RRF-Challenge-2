<template>
    <!-- Header -->
    <section class="bg-[#fff9f3] relative mb-[380px]">
        <!-- Navbar -->
        <div class="bg-[#fff9f3] sticky top-0 z-100">
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
            <h1 class="font-satoshi text-[#17134a] font-bold text-center text-6xl leading-16">Build Websites with <br>
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
                <h2 class="font-satoshi text-[#17134a] text-5xl font-semibold">Transform Your Ideas <br> into Reality
                    with AI</h2>
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
            <div class=" ">
                <i class="fa-solid fa-table-columns text-[#45426E] text-2xl"></i>
                <p class="my-4 text-[#17136a] font-semibold text-lg">Stunning Websites</p>
                <p class="text-[#45426E]">Type a prompt, get a full website using the <br> power of cutting-edge AI
                    technology</p>
            </div>
            <div class=" ">
                <i class="fa-regular fa-pen-to-square text-[#45426E] text-2xl"></i>
                <p class="my-4 text-[#17136a] font-semibold text-lg">Compelling Copies</p>
                <p class="text-[#45426E]">Generate all your website content in two <br> steps—a prompt & a click!</p>
            </div>
            <div class=" ">
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
                    <h2 class="font-satoshi text-[#17134a] text-5xl font-semibold">No-Code Website <br> Builder
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
                <div class=" ">
                    <i class="fa-solid fa-pen-nib text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Drag & Drop Builder</p>
                    <p class="text-[#45426E]">Drag-and-drop builder makes website <br> creation a breeze. No coding is
                        required.</p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-cube text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Templates
                    </p>
                    <p class="text-[#45426E]">With pre-designed templates, you can <br> quickly build your website.
                    </p>
                </div>
                <div class=" ">
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
                    <h2 class="font-satoshi text-[#17134a] text-5xl font-semibold">White-Label CMS
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
                <div class=" ">
                    <i class="fa-solid fa-pencil text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Built-in Blogging Platform</p>
                    <p class="text-[#45426E]">Build and publish blogs with all the features you need to rank on Google
                        and grow audience.</p>
                </div>
                <div class=" ">
                    <i class="fa-regular fa-clipboard text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">White Label Dashboard
                    </p>
                    <p class="text-[#45426E]">A white-label dashboard for your clients that you can brand as your own
                    </p>
                </div>
                <div class=" ">
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
                    <h2 class="font-satoshi text-[#17134a] text-5xl font-semibold">Build with Airtable Data</h2>
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
                <div class=" ">
                    <i class="fa-solid fa-table-columns text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Beautiful Layouts</p>
                    <p class="text-[#45426E]">Showcase your data in any layout, like the grid, table, job board, etc.
                    </p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-bolt text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Realtime Update
                    </p>
                    <p class="text-[#45426E]">Update data on Airtable and it will be updated on your website instantly
                    </p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-database text-[#45426E] text-2xl"></i>
                    <p class="my-4 text-[#17136a] font-semibold text-lg">Advanced Customization</p>
                    <p class="text-[#45426E]">Use Airtable as a data source in Dorik CMS and customize everything.</p>
                </div>
            </div>
        </section>

        <section class="container">
            <div class="my-20 flex gap-8 items-center">
                <div class=" ">
                    <h2 class="font-satoshi text-6xl text-[#17134a] font-bold">Join over 100k+ happy users from around
                        the world!
                    </h2>
                    <div class="mt-10 w-80">
                        <a href="#"
                            class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-medium py-4 px-8 rounded cursor-pointer inline-block">
                            Wall of Love <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>
                <div class="pt-11 text-[#17136d]  ">
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
                <h2 class="font-satoshi text-6xl font-semibold">Beautiful designs, <br> Endless possibilities</h2>
            </div>
            <div class="mt-20 flex justify-between gap-8">
                <div class="text-[#d1d0db] border border-blue-950 p-8  ">
                    <a href="#" class="hover:text-white text-xl font-medium leading-10">Amazing Templates</a>
                    <p>100+ <span class="underline decoration-blue-500">Beautiful Templates</span></p>
                </div>
                <div class="text-[#d1d0db] border border-blue-950 p-8  ">
                    <a href="#" class="hover:text-white text-xl font-medium leading-10">UI Blocks</a>
                    <p class="text-white">250+ <span class="underline decoration-blue-500">Stunning UI Blocks </span>
                    </p>
                </div>
                <div class="text-[#d1d0db] border border-blue-950 p-8  ">
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
            <h2 class="font-satoshi text-6xl font-semibold text-[#17134a] my-8">No Maintenance, More Freedom.</h2>
            <p class="text-[#51486e] text-xl">The perfect launchpad for your online presence</p>
        </div>
        <div class="mb-30">
            <div class="flex mt-11 gap-4 text-[#45426e]">
                <div class=" ">
                    <i class="fa-solid fa-shield text-[#9143fc]"></i>
                    <h2 class="text-[#17134a] font-bold my-2 text-2xl">Reliable Hosting & CDN</h2>
                    <p>We host the websites on AWS & DigitalOcean and serve static content from our Global CDN</p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-shield text-[#df2b92]"></i>
                    <h2 class="text-[#17134a] font-bold my-2 text-2xl">Free SSL/HTTPS</h2>
                    <p>Every website built and hosted on our platform comes with a free SSL certificate issued by Let's
                        Encrypt</p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-user-plus text-[#30aafe]"></i>
                    <h2 class="text-[#17134a] font-bold my-2 text-2xl">Team Collaboration</h2>
                    <p>Collaborate with your team and get input on designs, feedback, or brainstorming sessions.</p>
                </div>
            </div>
            <div class="flex mt-11 gap-4 text-[#45426e]">
                <div class=" ">
                    <i class="fa-regular fa-credit-card text-[#4ab4fe]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Payment Integration</h2>
                    <p>Integrate PayPal, Stripe, & Gumroad without code to receive payments from your users. </p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-cloud text-[#8e3efc]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Unlimited Storage & Bandwidth</h2>
                    <p>Don’t worry about your site’s storage and bandwidth because Dorik provides you with all the site
                        storage you need.</p>
                </div>
                <div class=" ">
                    <i class="fa-brands fa-wpforms text-[#e659aa]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Forms</h2>
                    <p>Add subscription & contact form easily to your website. Connect popular platforms like Zapier,
                        MailChimp, etc.</p>
                </div>
            </div>
            <div class="flex mt-11 gap-4 text-[#45426e]">
                <div class=" ">
                    <i class="fa-solid fa-chart-simple text-[#ea76b8]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">User Analytics</h2>
                    <p>Measure and analyze user data to get an understanding of user behavior across your web pages</p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-lock text-[#3baefe]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Password Protected Pages</h2>
                    <p>Protect any page on your website with a password. Securely share your pages with your clients.
                    </p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-magnifying-glass text-[#8c3bfc]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Native SEO</h2>
                    <p>Optimize your content for SEO and social media to maximize the reach of each post.</p>
                </div>
            </div>
            <div class="flex mt-11 gap-4 text-[#45426e]">
                <div class=" ">
                    <i class="fa-solid fa-shield text-[#17134a]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Custom Domain</h2>
                    <p>Connect your custom domain or subdomain easily from any domain provider to our platform.</p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-code text-[#e23f9d]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">AI Code Export</h2>
                    <p>Export your AI-generated website's clean and un-minified HTML/CSS/JS code with Media files.</p>
                </div>
                <div class=" ">
                    <i class="fa-solid fa-share-nodes text-[#27a6fe]"></i>
                    <h2 class="text-[#17136a] font-bold my-2 text-2xl">Integrations</h2>
                    <p>Collect and send data to popular platforms like Zapier, MailChimp, Airtable, etc using forms.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-[#fff9f3] my-30">
        <div class="text-center py-20 flex flex-col justify-center items-center">
            <h2 class="font-satoshi text-6xl font-semibold text-[#17134a] my-8">Affordable Pricing</h2>
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

    <section class="container">
        <div>
            <h2 class="text-6xl text-center font-semibold text-[#17134a] my-8 font-satoshi">Extended Guides, Live
                Support <br> &
                Community to help you
            </h2>
        </div>

        <div class="my-26 flex gap-8">
            <div class="bg-[#f6f6fc] p-8 rounded-lg border-b-4 border-b-[#8f40fc]">
                <h2 class="text-[#17134a] text-xl font-bold">Documentation</h2>
                <p class="text-[#51486e] text-xl my-2">We have extensive documentation on getting started with Dorik, as
                    well
                    as how to design and customize
                    your website.</p>
                <a class="text-[#17134a] text-lg font-medium hover:text-blue-900" href="#">Dorik Helpdesk <i
                        class="fa-solid fa-angle-right"></i></a>
            </div>
            <div class="bg-[#f6f6fc] p-8 rounded-lg border-b-4 border-b-[#de238e]">
                <h2 class="text-[#17134a] text-xl font-bold">Live Chat Support</h2>
                <p class="text-[#51486e] text-xl my-2">We have extensive documentation on getting started with Dorik, as
                    well
                    as how to design and customize
                    your website.</p>
                <a class="text-[#17134a] text-lg font-medium hover:text-blue-900" href="#">Start Live Chat <i
                        class="fa-solid fa-angle-right"></i></a>
            </div>
            <div class="bg-[#f6f6fc] p-8 rounded-lg border-b-4 border-b-[#ffcd88]">
                <h2 class="text-[#17134a] text-xl font-bold">Online Forum</h2>
                <p class="text-[#51486e] text-xl my-2">We have extensive documentation on getting started with Dorik, as
                    well
                    as how to design and customize
                    your website.</p>
                <a class="text-[#17134a] text-lg font-medium hover:text-blue-900" href="#">Facebook Community <i
                        class="fa-solid fa-angle-right"></i></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <section class="bg-[#030521] text-white pt-28">
        <div class="container">
            <div class="flex flex-col items-center gap-10">
                <h2 class="text-6xl font-semibold">Start Building Your Website!</h2>
                <div class="bg-image text-center w-80">
                    <a href="#"
                        class="bg-[#3a30ba] hover:bg-[#12126e] transition  text-white font-bold py-4 px-6 rounded cursor-pointer inline-block">
                        Try Dorik Now <i class="fa-solid fa-angle-right"></i>
                    </a>
                </div>
            </div>
            <hr class="border-t border-[#45426e] my-20" />
            <div class="flex justify-between gap-4">
                <div class="flex flex-col gap-4 text-xl">
                    <img class="w-40" src="../assets/img/dorik-white.svg" alt="">
                    <p class="text-[#a2a1b7]"><i class="fa-solid fa-heart text-[#f8312f]"></i> This website is built
                        with Dorik, without
                        writing any <br> code</p>
                    <div>
                        <img class="w-80" src="../assets/img/top-post.svg" alt="">
                    </div>
                    <a href="#" class="text-white font-bold bg-[#2b2b2b] p-4 rounded-xl hover:bg-[#424242]"><i
                            class="fa-solid fa-circle text-[#33b17e]"></i> All
                        systems operational</a>
                </div>

                <div class="text-[#a2a1b7] flex flex-col   gap-2 text-xl">
                    <h3 class="uppercase text-white text-xl font-medium">General</h3>
                    <a class="hover:text-white" href="#">About Dorik</a>
                    <a class="hover:text-white" href="#">Public Roadmap</a>
                    <a class="hover:text-white" href="#">Changelog</a>
                    <a class="hover:text-white" href="#">Affiliate Program</a>

                    <h3 class="uppercase text-white text-xl font-medium mt-8">Resources</h3>
                    <a class="hover:text-white" href="#">
                        Documentation</a>
                    <a class="hover:text-white" href="#">
                        Tutorial Videos</a>
                    <a class="hover:text-white" href="#">
                        Community</a>
                    <a class="hover:text-white" href="#">Dorik Blog</a>
                    <a class="hover:text-white" href="#">
                        Free Illustrations</a>
                    <a class="hover:text-white" href="#">Partners</a>
                    <a class="hover:text-white" href="#">AI Tools Directory</a>
                    <a class="hover:text-white" href="#">Write for Dorik</a>
                </div>

                <div class="text-[#a2a1b7] flex flex-col   gap-2 text-xl">
                    <h3 class="uppercase text-white text-xl font-medium">Follow Us</h3>
                    <a class="hover:text-white" href="#">Twitter</a>
                    <a class="hover:text-white" href="#">LinkedIn</a>
                    <a class="hover:text-white" href="#">Facebook</a>
                    <a class="hover:text-white" href="#">Discord <i class="fa-brands fa-discord text-[#ffcc85]"></i></a>
                    <a class="hover:text-white" href="#">Instagram</a>
                    <a class="hover:text-white" href="#">TikTok</a>
                </div>

                <div class="text-[#a2a1b7] flex flex-col   gap-2 text-xl">
                    <h3 class="uppercase text-white text-xl font-medium">Partner Program</h3>
                    <p class="text-[#d8def1]">Earn up to 40% <br> recurring commission</p>
                    <a class="text-[#ffcc85] hover:text-white" href="#">Become a Partner <i
                            class="fa-solid fa-arrow-right"></i></a>
                </div>
            </div>
            <hr class="border-t border-[#45426e] mt-11" />
            <div class="flex justify-between items-center text-xl py-11">
                <p class="text-[#a2a1b7]">© 2025 Dorik, Inc. All rights reserved</p>
                <div class="flex gap-4 text-[#a2a1b7]">
                    <a href="#">Terms & Conditions</a>
                    <a href="#">Privacy Policy</a>
                </div>
            </div>
        </div>
    </section>
</template>
