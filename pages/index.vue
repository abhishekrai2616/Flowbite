<template>
    <div>
        <div class="relative">
            <Navbar />
        </div>
        <div class="bg-gray-400 relative">
            <Dropdown />
        </div>
        <div class="relative">
            <Sidebar />
        </div>
    </div>
</template>

<script setup>
    import { initFlowbite } from 'flowbite'
    onMounted(() => {
        initFlowbite();
    })
</script>

<style scoped>

</style>