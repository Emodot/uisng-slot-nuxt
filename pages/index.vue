<template>
  <div class="main-container">
    <div class="ctn">
      <h1 class="header">Home Page</h1>
      <InfoModal>
        <template #content>
          <div>
            <h2>Contact Us</h2>
            <h4>This is a contact form</h4>
            <form action="">
              <div class="input-ctn">
                <label for="">Name</label>
                <input type="text" />
              </div>
              <div class="input-ctn">
                <label for="">Message</label>
                <input type="text" />
              </div>
            </form>
          </div>
        </template>
      </InfoModal>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style scoped>
.header {
  text-align: center;
  margin-top: 20vh;
}
.input-ctn {
  margin-top: 15px;
}
</style>
