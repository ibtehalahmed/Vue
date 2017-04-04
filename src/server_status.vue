<template>
    <div>
        <h1>{{status}}</h1>
        <br>
        <button @click="changeStatus">change</button>
    </div>
</template>

<script>
    export default {
        data: function () {
            return {
                status: "critical"
            }
        },
        methods: {
            changeStatus(){
            this.status = "123"
            }
    }
}
</script>