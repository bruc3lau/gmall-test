<template lang="">
    <div >
      <h3> Header is here!!</h3>
        <div>data.name:{{name}}</div>
        <div>root.prop.a:{{a}}</div>
        <div>
            <p>
                搜索：<input></input>
                <button @click="onSearch()">OK</button>
            </p>
        </div>
    <hr/>
    </div>
</template>
<script>
console.log("top!");
export default {
    name: "top",
    props: ["a"],
    data() {
        return { name: "header component name" };
    },
    methods:{
        onSearch(){
            alert("search")
        }
    }
};
</script>
<style lang="">
</style>