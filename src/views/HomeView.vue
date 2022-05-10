<template>

<div class="container base-color base-text text-center fill">
  <div class="row" style="margin: 20px">
      <p class="text-center">The Wedding Of</p>
      <h1 class="text-center harrington">Finti & Boby</h1>
  </div>
  <div class="row justify-content-center" style="margin: 20px">
    <button type="button" @click="$router.push('undangan')" class="btn btn-color btn-circle btn-xl base-text" id="btn">JOIN</button>
  </div>
  <div class="row" style="margin: 20px">
    <p>Minggu, 22 Mei 2022</p>
  </div>
  <div class="row" style="margin: 20px">
    <p>
      Kepada Yth.
      <br>
      Bapak/ Ibu/ Saudara/ i
    </p>
  </div>
  <div class="row">
    <div class="undangan ">
      <p>
        {{this.$route.query.nama}}
        <br>
          &
        <br>
        Pasangan
      </p>
      
    </div>
  </div>
  <div class="row">
    <p><small>Mohon maaf apabila ada kesalahan dalam penulisan nama & gelar</small></p>
  </div>
</div>
</template>

<style>
  @font-face {
    font-family: "Harrington";
    src: local("Harrington"),url(./fonts/HARRINGT.TTF) format("truetype");
  }
  .harrington{
    font-family: "Harrington";
    font-size: 3rem;
  }
  .undangan{
    background-color: white;
    color: black;
    width: 200px;
    margin: 20px auto;
    padding: 20px;
    border-radius: 22%;
  }
  p{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  .text-center{
    text-align: center;
  }
  .base-text{
    color:white;
    font-family: Segoe UI
  }
  .base-color{
    background-color: #333;
  }
  .btn-color{
    background-color: #C6F7FF;
  }
  .btn-color:hover{
    color:white;
    font-weight:bold;
    padding: 50px 0px 0px 0px;
  }
  .fill{
    padding: 50px 10px;
    height: 100vh;
  }
  .btn-circle.btn-sm {
      width: 30px;
      height: 30px;
      padding: 6px 0px;
      border-radius: 15px;
      font-size: 8px;
      text-align: center;
  }
  .btn-circle.btn-md {
      width: 50px;
      height: 50px;
      padding: 7px 10px;
      border-radius: 25px;
      font-size: 10px;
      text-align: center;
  }
  .btn-circle.btn-xl {
      width: 100px;
      height: 100px;
      padding: 10px 16px;
      border-radius: 100%;
      font-size: 12px;
      text-align: center;
      font-size: 1.5rem;
  }

</style>
