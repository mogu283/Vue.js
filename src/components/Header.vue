

<template>
    <div class="header">
<button @click="showText">表示</button>
<p>{{text}}</p>
    </div>
</template>
<script>
export default {
    data(){
        return{
            text:""
        }
    },
    props:["parentText"],
    methods:{
        showText(){
this.text=this.parentText
        }
    }

}
</script>