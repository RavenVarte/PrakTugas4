<template>
  <div class="background">
  <img src="../assets/th.jpg" />
  </div>
  <h3>Ini dari component Button</h3>
  <button class="submit">Submit</button>
  <button class="cancel">Cancel</button>
  <TextCom />
  <emit />

  <footer class="footer">
    <div class="footer-content">
      <p>&copy; 2024 ebby arrahman tarif</p>
    </div>
    </footer>
</template>

<script setup>
import TextCom from './Text.vue'
import emit from './EmitBut.vue'
</script>

<style scoped>
button {
  margin: 20px;
}

.submit {
  background-color: green;
}

.cancel {
  background-color: red;
}

.background img{
  position: fixed;
  top: 0;
  left: 0;
  min-height: 90%;
  min-width: 500px;
  width: 100%;
  height: 100%;
  overflow: hidden;
  z-index: -2;
  object-fit: cover;
  -webkit-background-size:cover; -moz-background-size:cover; -o-background-size:cover; background-size: cover;
  filter: brightness(0.8);
}

.footer {
  background-color: #333;
  color: white;
  height: 30px;
  width: 1310px;
  text-align: center;
}
</style>