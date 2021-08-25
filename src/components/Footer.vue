<template>
    <footer id="FooterBar">
        <p>FooterBar</p>
    </footer>
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
