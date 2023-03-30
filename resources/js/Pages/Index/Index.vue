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
