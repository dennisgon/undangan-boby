<template>
  <div class="container base-color base-text text-center pt-2">
    <div class="row justify-content-md-center">
      <div class="col col-4">
        <a href="#schedule" class="menu">Schedule</a>
      </div>
      <div class="col col-4">
        <img src="@/assets/logo.png" class="logo"/>
      </div>
      <div class="col col-4">
        <a href="#location" class="menu">Location</a>
      </div>
    </div>
    <div class="row my-5">
      <img src="@/assets/bismillah-png-20.png" class="gambar"/>
    </div>  
    <div class="row">
      <p>
        Maha Suci Allah telah menciptakan mahkluk hidup 
        <br>
        dengan berpasang-pasangan. Begitu pula dengan manusia.
        <br> 
        sungguh besar rahmat dan karunia yang diberikan-nya
        <br> 
        kepada keluarga kami
      </p>
    </div>
    <div class="row">
      <p>
        izinkan kami mengundang sekaligus mengharapkan do'a restu dari
        <br>
        Bapak/ibu dan Saudara/i dalam acara pernikahan Putra Putri kami.
      </p>
    </div>
    <div class="row">
      <h1 class="harrington">Finti Eka Sari </h1>
      <p>Putri dari Bapak Awi Astra dan Ibu Tusiyah</p>
      <h1 class="harrington">&</h1>
      <h1 class="harrington">Boby Supriadi</h1>
      <p>Putra dari Bapak M. Sandi & Ibu Suhana</p>
    </div>
    <div class="row justify-content-md-center my-5" id="schedule">
      <div class="col col-md-3 border-top border-right border-bottom">
        Akad Nikah
        <br>
        <br>
        09:00 WIB
      </div>
      <div class="col col-md-3 border">
        Minggu
        <br>
        <span  class="h1">22</span>
        <br>
        Mei 2022
      </div>
      <div class="col col-md-3 border-top border-right border-bottom">
        Resepsi
        <br>
        11:00 WIB
        <br>
        s/d
        <br>
        selesai
      </div>

    </div>
    <div class="row">
      <p>
        <br>
        atas Kehadiran dan do'a restu Bapak/Ibu dan Saudara/i 
        <br>
        Kami ucapkan terima kasih.
      </p>
    </div>
    <div class="row">
      <p>Kami yang berbahagia</p>
      <div class="col-6">
        <p>Kel. Bapak Awi Astra <br> & Ibu Tusiyah</p>
      </div>
      <div class="col-6">
        <p>Kel. Bapak M. Sandi <br> & Ibu Suhana</p>
      </div>
    </div>
    <div class="row">
      <p class="harrington">Finti & Boby</p>
    </div>
    <div class="row">
      <p>
        Berlokasi Di Lorong Guyub, Jl. Lingkar Timur 1
        <br>
        No. 158 Rt. 04 Kel. Ekajaya Jambi
      </p>
    </div>
    <div class="row justify-content-md-center" id="location">
      <div class="col col-md-6">
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d997.0574391281162!2d103.6532713!3d-1.6168801!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x5f6bf411b69ce201!2zMcKwMzcnMDAuMyJTIDEwM8KwMzknMTIuNiJF!5e0!3m2!1sen!2sid!4v1652206280072!5m2!1sen!2sid" width="300" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </div>
    <div class="row ustify-content-md-center" style="margin: 20px">
      <div class="col col-lg-4 pt-lg-5 mt-2">
        <img src="@/assets/Fot3.png" class="foto"/>
      </div>
      <div class="col col-lg-4 mt-2">
        <img src="@/assets/DAFF6648.jpg" class="foto"/>
      </div>
      <div class="col col-lg-4  pt-lg-5 mt-2">
        <img src="@/assets/DAFF6644.jpg" class="foto" />
      </div>

    </div>
    <div class="row">
      <p class="h1 harrington">Terima Kasih </p>
    </div>
  </div>

</template>

<style>
 @font-face {
    font-family: "Harrington";
    src: local("Harrington"),url(./fonts/HARRINGT.TTF) format("truetype");
  }
  @font-face {
    font-family: "frechscript";
    src: local("Harrington"),url(./fonts/frenchscriptmt-webfont.woff2) format("truetype");
  }
  .menu{
    font-family: "frechscript";
    font-size: 1.5rem;
    color: white;
    text-decoration: none;
  }
  .menu:hover{
    font-weight: bold;
    color: white;
  }
  .logo{
    width: 70px;
    height: 70px;
  }
  .harrington{
    font-family: "Harrington";
    font-size: 3rem;
  }
  .foto{
    width: 300px;
    height: 420px;
  }
  .gambar{
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 500px;
  }
  .schedule{
    margin-left: auto;
    margin-right: auto;
    width: 50%;
  }
</style>
