<template>
  <main class="page">
    <div class="box">
      <img class="image" src="src/assets/images/asnicon.png" />
      <div class="text">asnmp_</div>
    </div>
  </main>
</template>
<script>
export default {
  name: "Page",
  components: {}
};
</script>
<style scoped>
.page {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 100%;
  min-height: 100%;
}
.box {
  display: flex;
  flex-direction: column;
  flex: 0 1;
  justify-content: center;
  align-items: center;
  height: 374px;
}
.image {
  width: 150px;
  height: 150px;
  border-radius: 100px;
  box-shadow: 0px 0px 53px 4px rgba(0, 0, 0, 0.21);
}
.text {
  font-family: "Ubuntu", sans-serif;
  font-weight: 900;
  font-size: 2.25rem;
  line-height: 2.5rem;
}
</style>
