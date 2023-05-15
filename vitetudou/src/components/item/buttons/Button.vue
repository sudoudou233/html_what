<!--
    试试
    试试

<script>
export default {
    name: 'mybutton',
    data() {
        return {

        }
    },
}


</script>
<template>
    <button type="mybutton">
        
    </button>
</template>

-->

<script setup>
import HitButton from './HitsButton.vue'
import TimeButton from './TimeButton.vue'
</script>

<template>
    <ul>
        <li>
            <HitButton />
        </li>
        <li>
            <TimeButton />
    </li>
</ul></template>






