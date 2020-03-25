<template>
  <div class="main">
    <h1 class="title">辅助教学网站</h1>
    <h3 class="client">
      <router-link to="/client" :replace="false">客户端</router-link>
    </h3>
    <h3 class="admin">
      <router-link to="/admin" :replace="false">管理端</router-link>
    </h3>
  </div>
</template>

<script>
export default {
  name: "IndexPage"
};
</script>

<style scoped>
.main {
  width: 100%;
  height: 100%;
  background: url(../public/assets/bg.jpg) no-repeat;
  background-size: 100% 100%;
  text-align: center;
  box-sizing: border-box;
  padding-top: 10%;
}

.title {
  font-size: 56px;
  letter-spacing: 20px;
  color: rgb(14, 4, 4);
}

.client,
.admin {
  margin: 30px auto;
  width: 160px;
  height: 50px;
  line-height: 50px;
  text-align: center;
  font-size: 30px;
  letter-spacing: 10px;
  border: 2px solid rgb(93, 83, 187);
  border-radius: 12px;
}
</style>
