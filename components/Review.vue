<template>
    <div class="flex justify-start gap-5 p-6 mt-5 overflow-hidden bg-black/10 md:justify-center md:gap-6 md:mt-7">
        <div v-for="Review in Reviews" key="Review" class="hover:bg-white hover:text-yellow-500 hover:rounded-2xl">

            <div
                class="md:border border-[#E3A841]  flex items-center gap-2 h-[100px] w-[330px] md:h-[130px] px-2 md:w-[350px] rounded-2xl">
                <div>
                    <img :src="Review.img" alt="personimager" class="w-[60px] md:w-[80px]">
                </div>
                <div>
                    <p class="text-[16px] md:text-[22px] "> {{ Review.review }}</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            Reviews: [
                { img: "/image/img38.png", review: "Jet set go made my dream vacation a reality! Thnak you" },
                { img: "/image/img39.png", review: "Jet set go made my dream vacation a reality! Thnak you" },
                { img: "/image/img40.png", review: "From flights to hotels, everything was seamless." },
            ]
        }
    }
}</script>