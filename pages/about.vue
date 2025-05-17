<template>

    <div>
        <!--<p>{{ greet ? 'Hello' : 'Nice' }}</p>-->
        
        <p v-if="greet===1">Hello</p>
        <p v-else-if="greet===2">Nice</p>
        <p v-else-if="greet===3">how</p>
        <p v-else-if="greet===4">are</p>
        <p v-else>you?</p>
        
        <button @click="greet++">click</button>
        
    </div>
</template>
<script setup>

        const greet = ref(1)
         
</script>