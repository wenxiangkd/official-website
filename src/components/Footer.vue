<template>
  <div id="footer" class="container-fluid">
    <div class="logo">
      <img src="@/assets/ximg/logob.png" alt="logo图">
    </div>
    <p class="title">多安科技</p>
    <p class="address_tel_fax">
      <span>地址：江西省南昌市青云谱区世纪欧美中心A栋1006</span>
      <span>姜经理：17370000889</span>
      <span>刘经理：17370095889</span>
    </p>
    <p class="email_wx">
      <span>邮箱：liyunkun_11@163.com</span>
      <span>公司微信公众号DuoanSoft</span>
    </p>
    <p class="copy">Copyright &copy; 2018 - 2019 多安科技</p>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data() {
    return {};
  }
};
</script>
<style scoped>
#footer {
  width: 100%;
  height: 100%;
  color: #fff;
  background: #474747;
  overflow: hidden;
  text-align: center;
}
.logo {
  width: 147px;
  height: 45px;
  margin: 50px auto 20px;
}
.logo img{
  height: 45px;
}
.title {
  font-size: 25px;
  margin-bottom: 20px;
}
.address_tel_fax {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0;
}
.email_wx {
  color: #d3d3d3;
  font-size: 14px;
}
.copy {
  color: #d3d3d3;
  font-size: 14px;
  margin: 50px 0 10px;
}
@media screen and (max-width: 997px) {
  .title {
    font-size: 20px;
  }
  .address_tel_fax {
    font-size: 12px;
  }
  .email_wx {

  font-size: 12px;
}
.copy {
  font-size: 12px;
  margin: 30px 0 10px;
}
}
</style>

