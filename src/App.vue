<template>
  <div class="container my-4">
    <div class="grid">
      <div class="row">
        <div class="col">
          <h1 class="text-info">Core Concepts</h1>
          <p class="text-success fst-italic">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Provident placeat
            pariatur exercitationem et temporibus beatae explicabo! Natus sunt deleniti
            dolorum.
          </p>
        </div>
      </div>
    </div>
  </div>

  <header-item name="Omor" age="25" deg="Engg" />
  <employee-info></employee-info>
  <counter-info></counter-info>>
  <!-- <demo-info></demo-info> -->
  <greet-ing></greet-ing>
  
</template>

<script>
// import demoInfo from "./components/Demo.vue"
import CounterInfo from "./components/Counter.vue";
import EmployeeInfo from "./components/Employee.vue";
import HeaderItem from "./components/Header.vue";
import greetIng from "./components/Greeting.vue"

export default {
  name: "App",
  components: {
    HeaderItem,
    EmployeeInfo,
    CounterInfo,
    // demoInfo,
    greetIng,
    
  },
};
</script>

<style>
@import "./style.css";
</style>
