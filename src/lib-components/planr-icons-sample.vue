<template >
       <span :class="'p-icon-'+ classIcon" :style="{fontSize: fontSize,color: color }"></span>
      
</template>


<script>

export default {
    props: {
        classIcon:{
            type: String,
        },
        fontSize:{
            type: String,
        },
        color:{
            type: String,
        }
    }
}
</script>
<style>
@import '../plan-r.css'

</style>