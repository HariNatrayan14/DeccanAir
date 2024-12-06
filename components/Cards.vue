<template>
    <div>
        <div class="flex flex-wrap items-center justify-center gap-2 mt-5 md:gap-4 md:mt-10 ">
            <div v-for="place in places" key="place"
                class=" hover:bg-blue-100 w-[190px] md:w-[300px]  px-2 py-2 md:py-2 md:px-3 border border-black/20 rounded-lg ">
                <div class=""> <img :src="place.img" alt="cardimage" class="w-[180px] md:w-[340px] lg:w[380px]">
                    <div class="flex justify-between mt-1">
                        <p class="font-bold">{{ place.name }}</p>
                        <p class="text-black text-opacity-50">{{ place.explore }}</p>
                    </div>
                    <div>
                        <p class="font-medium">{{ place.price }}</p>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            places: [
                { img: "/image/t7.png", name: "Paris", price: "15,000", explore: "Explore more" },
                { img: "/image/t8.png", name: "Rome", price: "25,000", explore: "Explore more" },
                { img: "/image/t9.png", name: "Japan", price: "21,000", explore: "Explore more" },
                { img: "/image/t10.png", name: "Bali", price: "27,000", explore: "Explore more" },
                { img: "/image/t11.png", name: "Pichhu", price: "12,000", explore: "Explore more" },
                { img: "/image/t12.png", name: "Venice", price: "8,000", explore: "Explore more" },
                { img: "/image/t13.png", name: "Cape", price: "65,000", explore: "Explore more" },
                { img: "/image/t14.png", name: "Maldives", price: "15,000", explore: "Explore more" }
            ]
        }
    }
}
</script>