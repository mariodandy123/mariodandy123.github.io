<!DOCTYPE html>
<html>
<head>
  <meta charset='UTF-8'/>
  <meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/>
  <meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Nerko+One&display=swap" rel="stylesheet">
  <script type="text/javascript" src="https://general.kompiwin.repl.co/general.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script><link href="style.css" rel="stylesheet" type="text/css" />
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>

  <meta content="IE=edge" http-equiv="X-UA-Compatible">
  <title>Script HTML Bucin - Jika Benar</title>
  <meta name="description" content="Script HTML Bucin Jika Benar">
  <meta name="keywords" content="script html bucin">
  <link rel="icon" href="https://www.kompiwin.com/wp-content/uploads/2021/07/cropped-favicon_kompiwin-32x32.png" sizes="32x32" />
  <link rel="icon" href="https://www.kompiwin.com/wp-content/uploads/2021/07/cropped-favicon_kompiwin-192x192.png" sizes="192x192" />
  <link rel="apple-touch-icon" href="https://www.kompiwin.com/wp-content/uploads/2021/07/cropped-favicon_kompiwin-180x180.png" />
  <meta name="msapplication-TileImage" content="https://www.kompiwin.com/wp-content/uploads/2021/07/cropped-favicon_kompiwin-270x270.png" />
  
</head>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="terbangjauh.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="1.jpg" id="wallpaper"/>
   </div>
   
   <div id='Content'>

     <div id="ftAwal">
       <!-- Stiker Pembuka -->
       <img src="heart.png" id="ftoAwal"/>
     </div>

     <div id="loveIn">
       <!-- Tombol LOVE --><label class='lovein'>❤️</label>
     </div>
     <p id="ket">Sentuh LOVEnya!</p>

     <div class="kumpulan">
     	<img src="2.jpg" id="wallpaper2"/>
         <img src="3.jpg" id="wallpaper3"/>
         <img src="4.jpg" id="wallpaper4"/>
         <img src="5.jpg" id="wallpaper5"/>
     </div>
     
     <div><blockquote id='bq'>
       <p id="kalimat"></p>
       
       <p id="pesanAkhir" class="gaya4"></p>
       
       <p id="ketlanjut">Klik untuk Lanjut ya!</p>
       
     </blockquote></div>
     
     <!-- Tombol Kirim Pesan -->
     <div id="Tombol">
       <a id="By">&#128140; Balas</a>
     </div>

   </div>

<!-- Jangan Edit Bagian Ini --><script>
  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2500, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); audio = new Audio('' + linkmp3.src); ftganti=0;fungsi=0;fungsiAwal=0;function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);Content.style = "opacity:1;margin-top:14vh"; const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageHeight: 80,}); 
  const inip = []; const iniwp = []; iden = 1; iniwp[1] = wallpaper.src; iniwp[2] = wallpaper2.src; iniwp[3] = wallpaper3.src; iniwp[4] = wallpaper4.src; iniwp[5] = wallpaper5.src;

inip[1] = "haiii Anggieow,<br><br>minta maaf nda sempat ngucapin ulang tahun hahahhahahahha";
inip[2] = "semoga sukses selalu,<br><br>di murahkan rejekinya";
inip[3] = "paling penting dengar apa na bilang macemu,<br><br>semangat jalani hidup";
inip[4] = "karena hidup kadang Kidding,<br><br>sehat selalu";
inip[5] = "rajin2 share video lucu<br><br> mauja share tapi nda bisaka karena takut sok asik hahahahhahah<br><br>karena video lucu dari kau sangat berarti bagiku..HAHAHAHHAHAHHAHAHAH SALAM DARI MARIO DANDI";

pesanAkhir1 = inip[iden];
pesanAkhir3 = "stay with me.";

totalPesan = 5; //Input total pesan (slide) di sini ya!
</script>
<script src="script.js"></script>
<!-- Sampai Sini -->
</body>
</html>
