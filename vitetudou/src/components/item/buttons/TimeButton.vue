
<script>
const num = 0
const style_c = String

if (num == 0) {/*未选中状态*/ }
else if (num == 1) {/*选中正序*/ }
else if (num == 2) { /*选中倒序*/ }
else { num = 0 }

</script>

<template>
    <button class="timebutton" type="button" @click="num++">
        <div>
            <img src="../../style/icon/clock.png" class="time" alt="时间或许" />
        </div>
    </button>
</template>


<style scoped>
    .timebutton{
        color: #cd2020;
    }
</style>