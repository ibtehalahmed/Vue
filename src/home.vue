<template>
    <div>
        <server-status v-for="server in 5" :key="server"></server-status>
    </div>
</template>

<script>
    import ServerStatus from './server_status.vue'
    export default {
        components: {
            'server-status': ServerStatus
        }
    }
</script>