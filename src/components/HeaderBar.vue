<template>
    <header id="headerBar" class="navbar navbar-expand container-fluid navbar-light bg-light">
        <button type="button" class="btn btn-default navbar-toggler">
            <i class="bi bi-list"></i>
        </button>
        <div class="navbar-brand me-auto">
            <a href="#" class="logo">
                <img src="../assets/logo.png" class="img-fluid" alt="woiio logo">
            </a>
        </div>
        <div class="navbar-collapse collapse">
            <ul class="navbar-nav navbar-align">
                <li class="nav-item dropdown">
                    <a class="nav-icon dropdown-toggle" href="#" id="msgDropdown" data-bs-toggle="dropdown">
                        <div class="ps-r">
                            <i class="bi bi-bell-fill fs-5"></i>
                            <span class="indicator rounded-circle">4</span>
                        </div>
                    </a>
                    <div class="dropdown-menu dropdown-menu-lg dropdown-menu-end py-0" aria-labelledby="messagesDropdown"></div>
                </li>
                <li class="nav-item dropdown">
                   <a class="nav-link dropdown-toggle d-none d-sm-inline-block" href="#" data-bs-toggle="dropdown" aria-expanded="false">
                       <figure class="figure">
                           <img src="../assets/avatar.jpeg" class="avatar img-fluid rounded-circle me-1" alt="header img">
                           <figcaption class="figure-caption">Kim@woiio.com</figcaption>
                       </figure>
                   </a>
                </li>
            </ul>
        </div>
    </header>
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
