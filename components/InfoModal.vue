<template>
  <div class="container">
    <div class="inner">
      <div>
        <slot name="content" />
        <button class="btn">Submit</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: #2525252f;
  display: flex;
  height: 100vh;
  width: 100vw;
  align-items: center;
  justify-content: center;
}
.inner {
  text-align: center;
  width: 30%;
  background-color: #fff;
  padding: 20px;
  border-radius: 20px;
}

.btn {
  margin-top: 40px;
  padding: 10px 20px;
  background-color: rgb(37, 76, 236);
  border: none;
  color: white;
  border-radius: 10px;
}
</style>
