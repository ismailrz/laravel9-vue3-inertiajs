<template>
    <div>
        <p>Index</p>
        <Link href="/show">Show</Link>
        <p>This message is : {{ message }}</p>
    </div>
</template>
<script setup>

import { Link } from "@inertiajs/vue3"

defineProps({
    message: String
})

</script>

<script>
import MainLayout from "../../Layouts/MainLayout.vue";

export default {
    layout: MainLayout
}
</script>
