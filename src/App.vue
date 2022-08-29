<template>
  <div>
    <h1 class="text-red-800">This is App</h1>
   <RegisterComponent></RegisterComponent>
    
  </div>
</template>

<script>
import RegisterComponent from './components/RegisterComponent.vue';
export default {
    setup() {
        return {};
    },
    components: { RegisterComponent }
}
</script>

<style lang="scss" scoped>

</style>