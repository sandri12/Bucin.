<html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet">
  
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><link href="https://feeldreams.github.io/matahari/style.css" rel="stylesheet" type="text/css" />
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  
<head>
<title>Hanya Kamu yang Aku Sayang</title>
<meta name="description" content="HTML Bucin Malas.id">
<link rel="icon" type="image/x-icon" href="https://malasid.github.io/favicon.png">
</head>
<body>
	
   <!-- Ganti Audio di sini --><audio src="https://feeldreams.github.io/matahari/matahari.mp3" id="linkmp3"></audio><script>audio = new Audio('' + linkmp3.src);</script>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://feeldreams.github.io/wp10.jpg" id="wallpaper"/><div id="beneranblur"></div>
   </div>

   <div id='Content'>
   	
     <div id="suratin" onClick="memulai();">
       <!-- Tombol Surat --><img src="https://rayyscoding.github.io/envelope.png"/>
     </div>
     <p id="ket">Klik Pesannya!</p>
   
     <div>
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotoakhir"/>
         <img src="https://feeldreams.github.io/pandakuning.gif" id="fotoakhir1"/>
         <img src="https://feeldreams.github.io/weee.gif" id="fotoakhir2"/>

         <img src="https://feeldreams.github.io/smprt.gif" id="fotoAkhir"/>
     </div>
     <div><blockquote id='bq'>
  
       <!-- Konten Penerapan -->
       <p id="kalimat">Matahari Boleh Bersinar Terang..</p>
       <p id="kalimata">Tapi Hanya Kamu yang Paling Aku Sayang 😆</p>
       <p id="kalimatb">Aacuaakss~</p>

       <!-- Konten Pertanyaan -->
       <p id="kalimat2">Iyaa Ga Sih? 😆❤️</p>

       <!-- Konten Jawaban -->
       <p id="kalimat3">Jawabanmu: </p>
       <p id="kalimatb3">Kirim jawabannya ke WhatsApp aku yaa~</p>
     </blockquote></div>
   
     <!-- Tombol Multifungsi -->
     <div id="Tombol">
       <a id="By" onClick="multifungsi()">
         <b id="tmbl">Lanjut</b>
       </a>
     </div>
     
   </div>

<!-- Jangan Edit Bagian Ini --><script>
  async function menuju(){await swals.fire('OK!', 'Kirim pesan ke WhatsApp aku, ya!', 'success');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;Tombol.style="margin-top:15px;opacity:1;transform: scale(1);";}
  const swalst = Swal.mixin({timer: 2777, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 100,}); const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,}); const body = document.querySelector("body");function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
  function mulaikonten(){fungsi=1;suratin.style="display:none";ket.style="display:none";Content.style = "opacity:1;margin-top:4vh;";bodyblur.style="opacity:.4;animation:none";wallpaper.style="transform: scale(1);";bq.style = "position:relative;opacity:1;visibility:visible;margin-top:0;";

                          audio.play();ftganti=0;ftmuncul();
                          setTimeout(fmulaiketik1,300);setTimeout(mulaiketik1,300);
                          setTimeout(fmulaiketik1b,2000);setTimeout(mulaiketik1b,2000);
                          setTimeout(fmulaiketik2,3955);setTimeout(mulaiketik2,3955);
                         }
  
   async function jawab(){
           var { value: jawaban } = await swals.fire({
               title: 'Tulis Pesan &#128073;&#128072;', input: 'text', allowOutsideClick: false, showCancelButton: false,
           });
           if(jawaban && jawaban.length < 19){
           	window.jawaban = jawaban;
               pesanwhatsapp = jawaban;
               balasan = jawaban;
               otomatis3();setTimeout(stakhir,1000);
           } else {
               await swals.fire('Ups!', 'Jawaban tidak boleh kosong atau lebih dari 18 karakter, ya!');
           }
       }
</script>
<script src="https://malasid.github.io/html/hanyakamusayang.js"></script>
<!-- Sampai Sini -->
</body>
</html>
