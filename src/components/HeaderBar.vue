<template>
    <p>headerBar</p>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'HeaderBar',
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
