
<script>
/*
addEventListener('click',)
function fire() {
    //这里给把整个页面按照热度排行
}
*/
const num = 0
if (num == 0) {/*未选中状态*/ }
else if (num == 1) {/*选中正序*/ }
else if (num == 2) { /*选中倒序*/ }
else { num = 0 }

</script>

<template>
    <button type="button" @click="num++">
        <div>
            <img src="../../style/icon/fire.png" class="fire" alt="热度或许" />
        </div>
    </button>
</template>
