<template>
<div id="items" class="container">
    <item-component></item-component>
    <item-component></item-component>
    <item-component></item-component>
    <item-component></item-component>
</div>
  
</template>

<script>
import itemComponent from "./itemComponent.vue"

export default{ 
    components: { itemComponent },
    name:"items"

}
</script>

<style>
#items{
    background-color: gray;
    height: 1000px;
    margin: 0;
    padding: 0;
}

</style>