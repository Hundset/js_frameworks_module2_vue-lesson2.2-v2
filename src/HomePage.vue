<template>
    <LoginComponent message="Please Login to view jobs"/>
</template>

<script>
import LoginComponent from './components/LoginComponent.vue'

export default {
    name: 'HomePage',
    components: {
        LoginComponent
    }
}
</script>