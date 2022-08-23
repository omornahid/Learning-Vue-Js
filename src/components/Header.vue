<template>
  <!-- This is how prop works -->
  <div class="container">
    <div class="row">
      <div class="col">
        <p class="h3 mb-4 text-primary">Customer - This is from prop</p>
        <ul class="list-group">
          <li class="list-group-item">Name : {{ name }}</li>
          <li class="list-group-item">Age : {{ age }}</li>
          <li class="list-group-item">Designation : {{ deg }}</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderItem",
  props: {
    name: { type: String, required: true },
    age: { type: Number },
    deg: { type: String },
  },
};
</script>

<style scoped>
h2 {
  background-color: darkgoldenrod;
}
</style>
