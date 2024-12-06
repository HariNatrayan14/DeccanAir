<template>
    <!-- <div class="py-24 bg-white sm:py-32">
        <div class="px-6 mx-auto max-w-7xl lg:px-8">
            <div v-for="(stat, index) in stats" :key="index" ;
                class="grid grid-cols-1 text-center gap-x-8 gap-y-16 lg:grid-cols-3">
                <div class="flex flex-col max-w-xs mx-auto gap-y-4">
                    <dt class="text-gray-600 text-base/7">{{ stat.name }}</dt>
                    <dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl">
                        {{ stat.number }}
                    </dd>
                </div>
            </div>
        </div>
    </div>

    <div class="flex gap-5">
        <img v-for="stat in 5" :key="stat" src="/image/t6.png" class="bg-indigo-700 rounded-lg w-[100px] ">


    </div>

    <div>
        <div v-for="item in items" :key="items">{{ item }}</div>
    </div>

    <div v-for="(person, index) in people" :key="index">
        {{ index + 1 }}{{ person.name }}{{ person.age }} This is our student

    </div> -->

    <!-- <div v-for="item in items " key="item.id">
        <p v-if="item.visible">{{ item.name }}
            <img :src="item.img" alt="item image" class="w-[60px]">
        </p>
    </div> -->
    <!-- v-model  -->
    <!-- 
        <label for="name">Name</label><input type="text" name="" id="" v-model="inpText">
        <input type="text" name="" id="" v-model="inpText">
        <p>inpText:"{{ inpText }}"</p>
    </div> -->

    <!-- v-bhind -->
    <!-- <div class="flex items-center justify-center gap-8">
        <input type="text" v-model="inputField" class="border w-[248px] h-[28px] rounded"
            :class="checkBox ? 'border-[#aaaaaa] w-5 ' : 'border-green-500 w-60'" />
        <input type="checkbox" class="border border-[#aaaaaa] w-[24px] h-[24px]" v-model="checkBox" />
    </div>
    <p class="items-center">{{ inputField }}</p> -->

    <div>

        <div v-html="htmlcontent"></div>
    </div>

</template>
<script>
export default {
    data() {
        return {
            // stats: [
            //     { name: "HARI", number: 225555 },
            //     { name: "IYU", number: 88888 },
            //     { name: "SURE", number: 5425 },
            //     { name: "JEGAN", number: 5686848 },
            //     { name: "MARI", number: 63546856 }

            // ],
            // stat: [{

            // }],
            // items: ["pencil", "pen", "book", "box", "bag"],

            // people: [
            //     { id: 1, name: "hari", age: "21" },
            //     { id: 2, name: "yiscg", age: "27" },
            //     { id: 3, name: "khbsx", age: "44" },
            //     { id: 4, name: "kjsbx", age: "245" }
            // ],
            // items: [
            //     { id: 1, img: "/image/t6.png", name: "Hari natrayan", visible: true },
            //     { id: 2, img: "/image/t5.png", name: "Hri", visible: true },
            //     { id: 3, name: "Hari natrayan", visible: false }
            // ]
            //     inpText: 'Hello hari'

            // }

            // checkBox: false,
            // inputField: "",
            htmlcontent: '<ol class="font-bold bg-blue-500"><li>Toatoes</li><li>potatoes</li></ol>',
        }



    }
}</script>