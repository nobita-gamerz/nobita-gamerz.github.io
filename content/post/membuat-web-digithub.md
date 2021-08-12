---
title: "Membuat Website Di github"
date: 2021-04-24T15:24:47Z
draft: false
tags: [ "artikel", "materi", "website", "github", "pemrograman" ]
---
<center><img width="300" height="200" src="/img-asset/github-pages.jpeg"></center>

😎 `Assalamualikum wr.wb`
 
<html>

<h1 align="center"><strong>Cara Membuat Website di Github</strong></h1>
<br>
<p class="justify">&nbsp; &nbsp;Halo guys ok next share lagi kali ini saya akan share cara membuat blog di github dan sebelumnya yang belum tau apa itu github bisa di cek di marih 😎👉 <a href="/post/pengenalan-github/">Apa itu github..?</a> .Nah sekarang kita akan membuat blog/website sederhana menggunakan hosting github..yup namun perlu di ingat cara ini adalah membuat web dari nol he...😜 namun langsung di onlinekan projectnya...yaa harusnya offline dulu yaa...baru belajar di hostingkan he...😜</p>
<!--more-->
<br>
<p class="justify">&nbsp; &nbsp;Halaman Github (Github Pages) merupakan layanan hosting web statis yang diberikan oleh Github. Layanan ini diberikan secara gratis dan kita juga akan mendapatkan subdomain .github.io.</p>
<br>
<p class="justify">Bagaimanakah cara membuatnya?</p>
<br>
<p class="justify">&nbsp; &nbsp; Baiklah, pastikan kalian sudah punya akun Github jika belum kalian bisa daftar dulu di sini <a href="https://github.com">Daftar Github</a> dan sudah menginstal Git nah untuk git sesuaikan dengan os kalian ya bila menggunakan windows tinggal download saja git untuk windows atau bisa menggunakan cygwin. Kemudian silahkan ikuti langkah-langkah berikut, tidak sampai 20 menitan guys 😜.</p>
<br>

`1. Membuat Repositori Baru`

<p class="justify">&nbsp; &nbsp; Nah disini saya akan mencontohkan menggunakan sistem operasi android atau Hp android dan menggunakan aplikasi termux ,perlu diingat sesuaikan OS nya,Buatlah repositori baru dengan nama username.github.io. Gunakan username github Anda, contoh noob.github.io.</p>
<br>
<center><img src="/img-asset/create-akun1.jpg"></center>
<br>
<center><img src="/img-asset/create-akun2.jpg"></center>
<br>
<center><ing src="/img-asset/create-akun3.jpg"></center>
<br>
<p class="justify">Nah Tinggal Creat saja ok 😜. Bila sudah kita mulai ke tahap selanjutnya....
<br>

`2. Membuat Repositori Dikomputer`

<p class="justify">&nbsp; &nbsp; Buka terminal atau CMD,nah disini saya menggunakan android via termux, kemudian buatlah repositori baru. Kita akan mengisi, repositori ini dengan file index.html saja. Silahkan ikuti perintah berikut ini.</p>
<br>
<table border="1" cellpadding="5">
<tr>
<td>
mkdir pages-github
<br>
cd pages-github
<br>
echo "Test Website cuk" >> index.html
<br>
git init
<br>
git add index.html /atau bisa (git add .)
<br>
git commit -m "Test web online"
<br>
git branch -M main / git branch -M master (sesuikan saja)
<br>
</td>
</tr>
</table>
<br>

`3. Tambahkan URL Remote Repositori`

<br>
<p class="justify">&nbsp; &nbsp; Nah sekarang coba cek url repositori github kalian cek di website githubnya terus copy tinggal tambah saja "git remote add origin" ok lihat contoh dibawah ini :</p>
<br>
<p class="justify">&nbsp; &nbsp; Ok jelasnya lihat gambar dibawah ini 🤓</p>
<br>
<center><img src="/img-asset/create-akun4.jpg"></center>
<br>
<table border="1" cellpadding="5">
<tr>
<td>
<br>
git remote add origin https://github.com/noovieta/noovieta.github.io.git
<br>
<br>
</td>
</tr>
</table>
<br>

  `ingat sesuaikan dengan url repositori kalian`

`4. Kirim Ke Github`

<p class="justify">&nbsp; &nbsp; Nah setelah itu kita lanjukan dengan mengirim project kita dengan perintah dibawah ini :</p>
<br>
<table border="1" cellpadding="5">
<tr>
<td>
<br>
git push -u origin master / git push -u origin main (sesuikan saja)
<br>
<br>
</td>
</tr>
</table>
<br>

`5. Test Hasil`

<p class="justify">&nbsp; &nbsp; Nah sekarang kita coba cek dengan https://username.github.io contoh yang saya buat https://noovieta.github.io</p>
<br>
<p class="justify">&nbsp; &nbsp; Ok cek di video saya untuk contohnya ya..🤓</p>
<br>
<center><iframe width="300" height="200" src="https://www.youtube.com/embed/8MgZc-bA4-Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
<br>
<br>
<p class="justify">&nbsp; &nbsp; Nah! Bagaimana, tidak sampai 20 menit kan he...🤓? Selanjutnya kalian bisa kembangkan sendiri websitenya. kelebihannya ya kita bisa membuat project lanjutan nya secara offline tinggal push saja nah untuk cara update blog di terminal setelah di update secara offline untuk di push atau di kirim ke github next time ok 😁 ...Sekian dulu ya , semoga bermanfaat 😁</p>
<br>

😎 `Wassalamualikum wr.wb`

</html>
