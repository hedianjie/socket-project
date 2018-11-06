<template>
    <div class="container">
        <nav-header></nav-header>
        <chat-view></chat-view>
        <tool-footer></tool-footer>
    </div>
</template>
<script>
import navHeader from './components/header.vue'
import chatView from './components/chat.vue'
import toolFooter from './components/footer.vue'
export default {
    data () {
        return {

        }
    },
    components: { 
        navHeader,
        chatView,
        toolFooter
    }
}
</script>

