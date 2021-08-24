<template>
    <p>FooterBar</p>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'FooterBar',
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
