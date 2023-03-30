<template>
<MainLayout>

    <div>
        <p>Index</p>
        <Link href="/show">Show</Link>
        <p>This message is : {{ message }}</p>
    </div>
</MainLayout>
</template>
<script setup>

import { Link } from "@inertiajs/vue3"

import MainLayout from "../../Layouts/MainLayout.vue";
defineProps({
    message: String
})

</script>
