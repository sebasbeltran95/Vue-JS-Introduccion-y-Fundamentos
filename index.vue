<template>
    <div>
        <p>hola</p>
        <div>
            {{ text }}
        </div>
    </div>
</template>


<script>
    export default {
        data() {
            return {
                text: "hola vue"
            };
        }
    };
</script>

<style>
    p 
    {
        color: red;
    }
</style>
