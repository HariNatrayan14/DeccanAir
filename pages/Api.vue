<template>
    <div>
        <h1 class="text-2xl font-bold">User List</h1>
        <ul v-if="users.length" class="flex flex-col gap-2 mt-4 bg-green-300">
            <li v-for="user in users" :key="user.id" class="p-2 border-b">
                <strong>{{ user.id }}{{ user.name }}</strong> - {{ user.email }}{{ user.phone }}{{ user.username }}{{
                    user.website }}
            </li>
        </ul>
        <p v-else>Loading...</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            users: [],
        };
    },
    methods: {
        async fetchUsers() {
            try {
                const response = await fetch(
                    "https://jsonplaceholder.typicode.com/users"
                );
                if (!response.ok) throw new Error("Failed to fetch users");
                this.users = await response.json();
                console.log("Users fetched successfully:", this.users);
            } catch (error) {
                console.error("Error fetching users:", error);
            }
        },
    },
    mounted() {
        this.fetchUsers();
    },
};
</script>

<style scoped>
ul {
    list-style-type: none;
}
</style>