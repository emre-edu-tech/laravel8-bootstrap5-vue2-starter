<template>
    <div>
        {{ count }}
        <button @click="addOne()">Increment 1</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            count: 0,
        }
    },
    methods: {
        addOne(){
            return this.count++;
        }
    },
    mounted() {
        console.log('Example Component Loaded');
    }
}
</script>