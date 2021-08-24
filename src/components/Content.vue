<template>
    <p>content</p>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'Content',
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
