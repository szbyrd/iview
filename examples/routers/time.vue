<template>
    <div>
        <Time :time="1526608921" />
        <Time :time="1652839997" />
        <Time :time="ddd" :interval="1" />


    </div>
</template>
<script>
    export default {
        data () {
            return {
                ddd: new Date()
            };
        },
        computed: {},
        methods: {}
    };
</script>