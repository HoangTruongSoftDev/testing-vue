<script setup>
const verb = [
  "j'abandonne",
  "tu abandonnes",
  "il/elle/on abandonne",
  "nous abandonnons",
  "vous abandonnez",
  "ils/elles abandonnent",
];
</script>

<template>
  <div class="conjugation-container">
    <h2>Present</h2>
    <ul>
      <li><strong>je</strong> vais</li>
      <li><strong>tu</strong> vas</li>
      <li><strong>il/elle/on</strong> va</li>
      <li><strong>nous</strong> allons</li>
      <li><strong>vous</strong> allez</li>
      <li><strong>ils/elles</strong> vont</li>
    </ul>
  </div>
</template>

<style scoped>
.conjugation-container {
  background-color: #d3eaff;
  border: 1px solid #000;
  padding: 50px;
  text-align: center;
}

.conjugation-container h2 {
  font-weight: bold;
}

.conjugation-container ul {
  list-style-type: none;
  padding: 0;
}

.conjugation-container li {
  margin: 5px 0;
}
</style>
