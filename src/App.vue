<template>
<!--การบ้าน
   <body>
    <header class="top">
      <a href="#" target="_blank">List</a>
      <a href="#" target="_blank">Home</a>
      <img id="logo" alt="Vue logo" src="./assets/logo.png" />
    </header>
    <section class="section">
      <section class="section1">Section 1</section>
      <section class="section2">Section 2</section>
    </section>
  </body> -->
  <body>
    <img src="./assets/logo.jpg" alt="Pimon Food" class="logo">
    <nav class="topNav">
      <a href="#" rel="noopener noreferrer">อาหาร</a>
      <a href="#" rel="noopener noreferrer">สมาชิก</a>
      <a href="#" rel="noopener noreferrer">รายการสั่งซื้อ</a>
    </nav>
    <section class="card">
      <img src="./assets/01ปลากะพงทอดราดพริก 3 รส.jpg" alt="ปลากระพง">
      <article class="des">
        <p>ปลากะพงทอดราดพริก 3 รส</p>
        <p>200 baht</p>
        
      </article>
    </section>
  </body>
</template>

<script>
export default {};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

* {
  margin: 0;
  padding: 0;
  list-style: none;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}
.logo{
  height: 200px;
  border-radius: 50%;
  border: 10px solid #fff;
}
.topNav{
  padding: 0.25cm 0;
  margin: 30px 250px 20px;
  overflow: hidden;
  background-color: #652929;
}
.topNav a{
  color: #fbe0df;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}
.topNav a:hover{
  background-color: #fbe0df;
  color: #652929;
}
.topNav a:active{
  background-color: aqua;
  color: black;
}
/*การบ้าน
 .top {
  background-color: #cdf3c9;
  box-shadow: 0px 0px 30px 0px rgba(50, 50, 50, 0.2);
  padding: 25px 50px;
}
.top a {
  float: right;
  color: #798776;
  text-align: center;
  text-decoration: none;
  padding: 17px 25px;
  font-size: 20px;
  font-weight: bold;
}
.top a:hover {
  background-color: #40b983;
  color: #cdf3c9;
}
#logo{
  height: 60px;
}

section {
  width: 100%;
  display: flex;
}
.section1 {
  width: 60%;
  color: #798776;
  margin: 40px 20px;
  height: 500px;
  border-radius: 15px;
  box-shadow: 0px 0px 10px 0px rgba(50, 50, 50, 0.2);
  align-items: center;
  justify-content: center;
}
.section2 {
  width: 40%;
  color: #798776;
  margin: 40px 20px;
  height: 500px;
  border-radius: 15px;
  box-shadow: 0px 0px 10px 0px rgba(50, 50, 50, 0.2);
  align-items: center;
  justify-content: center;
} */
</style>
