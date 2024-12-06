<template>
    <div>
        <Header />
    </div>
    <!-- img  -->
    <div class="md:relative">
        <!-- img & button md -->
        <div class="relative">
            <img src="/image/t1.png" class="w-full ">
            <h1 class="font-bold text-white text-[16px] absolute top-10 left-4 md:text-[30px] md:top-36 md:left-36">
                EXPLORE THE UNSEEN <br>WORLD WITH US!
            </h1>
            <p class="text-white/60 absolute top-24 left-4 text-[10px] md:text-[28px] md:top-60 md:left-36">Exclusive
                Deals
                on Flights, Hotels,
                and Tours.</p>
        </div>
        <!--mob button -->
        <div class="mt-8 md:absolute md:bottom-96 md:left-40">
            <div class="relative mx-4">
                <div class="relative mx-2">
                    <div
                        class="flex justify-around w-[350px] gap-6  h-[46px] border border-black/50 md:bg-white py-2 px-2 md:py-3 md:px-3  rounded-full ">
                        <div><input type="text" placeholder="From" class="border-none w-[100px] w"></div>
                        <img src="/image/t2.png" alt="image" class="w-[22px] md:w-[26px]">
                        <div><input type="text" placeholder="To" class="border-none w-[100px]"></div>
                    </div>
                    <button
                        class="bg-[#056CB9] hover:bg-[#57656f] text-[14px] md:text-[18px] absolute -bottom-4 -right-4 md:-bottom-12 md:-right-28 text-white w-[140px] md:w-[200px] px-2 py-2 md:px-4 md:py-4 rounded-2xl">
                        Start Your Journey
                    </button>
                </div>
                <div
                    class="bg-[#c67b2a] absolute -top-7 md:-top-10 md:-left-5   md:text-[18px] text-white/80 hover:bg-[#ffa03b] w-[130px] md:w-[160px] px-1 py-1 md:px-3 md:py-3  rounded-2xl">
                    <p>Where to Next ?</p>
                </div>
            </div>
        </div>
    </div>
    <!-- ani  -->
    <!-- <img src="/nuxt-app/public/image/giphy.webp" alt="animi" class="w-[250px]"> -->
    <!-- mini con -->
    <div class="m-6 gap-7 md:flex md:justify-center">
        <div
            class="md:flex flex mt-10 md:mt-5  items-center py-2 gap-3 rounded-xl hover:bg-blue-400 hover:text-white px-2 bg-black/10 md:bg-white md:border border-black/30 w-[360px]">
            <img src="/image/t3.png" class=" w-[35px] h-[40px] md:w-[40px]">
            <div class="flex-col md:flex">
                <h1 class="font-bold">Live Chat and 24/7 Support</h1>
                <p class="text-black/50 hover:text-white/70">Instant assistance through a chatbot or live agent.</p>
            </div>

        </div>
        <div
            class="md:flex flex mt-5 items-center py-2 gap-3 rounded-xl hover:bg-blue-400 hover:text-white px-3 bg-black/10 md:bg-white md:border border-black/30 w-[360px]">
            <img src="/image/t4.png" class=" w-[35px] h-[40px] md:w-[40px]">
            <div class="flex-col md:flex">
                <h1 class="font-bold">Review and Rating System</h1>
                <p class="text-black/50 hover:text-white/70">Users can rate destinations, tours, and services to help
                    others decide.</p>
            </div>

        </div>
        <div
            class="md:flex flex mt-5 items-center py-2 gap-3 rounded-xl hover:bg-blue-400 hover:text-white px-2 bg-black/10 md:bg-white md:border border-black/30 w-[360px]">
            <img src="/image/t5.png" class=" w-[35px] h-[40px] md:w-[40px]">
            <div class="flex-col md:flex">
                <h1 class="font-bold">Search and Booking System</h1>
                <p class="text-black/50 hover:text-white/70">Real-time availability and pricing updates for flights,
                    hotels, and tours.</p>
            </div>

        </div>
    </div>
    <!-- img para -->
    <div class="flex items-center justify-center gap-1 mt-10 md:gap-10">
        <img src="/image/t6.png" class=" w-[150px] md:w-[350px]">
        <div class="flex flex-col gap-2 md:gap-3">
            <p class="text-[16px] md:text-[24px]">Why Choose JetSetGo?</p>
            <h1 class="font-medium md:text-[30px]">Hassle-Free Travel Planning</h1>
            <p class="text-[14px] md:text-[30px]">We simplify your travel experience by <br> offering an all-in-one
                platform for<br>
                flights,
                hotels, and tours. Say goodbye <br> to complicated bookings and hello to<br> seamless travel planning.
            </p>
            <button
                class="bg-[#e3a841] hover:bg-[#ffb93f] text-white font-semibold w-[80px] md:w-[100px] py-1 px-1 md:py-2 md:px-2 rounded-lg">EXPLORE</button>
        </div>
    </div>
    <!-- card  -->
    <div class="flex flex-col items-center mt-10">
        <h6 class="text-[20px]">Discover Our</h6>
        <h3 class="font-semibold text-[26px]">Famous Tour Plans</h3>
    </div>
    <Cards />
    <!-- review -->
    <div class="mt-5 text-center md:mt-10">
        <p class="font-bold text-[16px] md:text-[30px] ">Testimonials</p>
    </div>
    <Review />

    <!-- Latest News & Blogs -->

    <div class="m-2 mt-5 md:mt-10">
        <h1 class="font-bold text-center text-[16px] md:text-[24px]">Latest News & Blogs</h1>
    </div>
    <div class="bg-[#F8C449]/30 px-2 py-2 mt-10">
        <div class="items-center m-5 mt-2 md:flex md:justify-center md:gap-20 md md:mt-10">
            <div><img src="/image/t15.png" alt="blogimage" class="w-[350px] md:w-[600px]"></div>
            <div class="md:flex md:flex-col w-[350px] mt-2 md:gap-2 md:w-[500px]">
                <h1 class="font-bold md:text-[24px] text-[16px]">Top 10 Packing Hacks for Stress-Free Travel</h1>
                <p class="text-[14px] md:text-[18px]">Packing for a trip can often feel overwhelming, but it doesn't
                    have to
                    be.
                    Whether you're planning a short
                    weekend getaway or a long international vacation, these packing hacks will save you time, space,
                    and
                    stress.
                </p>
                <button
                    class="bg-[#4AAFF7] mt-2  hover:bg-[#3889c3]  text-white font-semibold w-[80px] md:w-[100px] py-1 px-1 md:py-2 md:px-2 rounded-lg">EXPLORE</button>

            </div>
        </div>
        <div class="items-center m-5 md:flex md:justify-center md:gap-20 md md:mt-10">
            <div><img src="/image/t16.png" alt="blogimage" class="w-[350px] mt-5 md:hidden "></div>

            <div class="md:flex md:flex-col md:gap-2 md:w-[500px] mt-2">

                <h1 class="font-bold  md:text-[24px] text-[16px]">Discover the Hidden Gems of Bali</h1>
                <p class="text-[14px] w-[350px] md:text-[18px]">Bali is often associated with its beautiful beaches
                    and
                    vibrant
                    nightlife, but there’s so much more to explore. Let’s uncover some lesser-known treasures of the
                    Island
                    of Gods.
                </p>
                <button
                    class="bg-[#4AAFF7] mt-2 hover:bg-[#3889c3] text-white font-semibold w-[80px] md:w-[100px] py-1 px-1 md:py-2 md:px-2 rounded-lg">EXPLORE</button>

            </div>
            <div><img src="/image/t16.png" alt="blogimage" class=" hidden md:block md:w-[600px]"></div>

        </div>
    </div>

    <!-- form -->
    <Form />

    <Footer />
</template>