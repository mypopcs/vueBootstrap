<template>
    <p>sideBar</p>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'SideBar',
    props: {
        msg: {
        type: String,
        required: true
        }
    },
    setup() {
        
    },
})
</script>
<style scoped>

</style>
