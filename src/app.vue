<template>
    <div class="container">
        <nav-header></nav-header>
        <chat-view></chat-view>
    </div>
</template>
<script>
import navHeader from './components/header.vue'
import chatView from './components/chat.vue'
export default {
    data () {

    },
    components: { navHeader, chatView }
}
</script>

