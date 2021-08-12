---
title: "STRUKTUR DASAR HTML"
date: 2021-05-07T12:31:52Z
draft: false
tags : [ "artikel", "materi", "html", "pemrograman" ]
---
<center><img width="300" height="380" src="/img-asset/Struktur dasar html.png"></center>

😎 `Assalamualikum wr.wb`

<h1 align="center">Struktur Dasar HTML</h1>
<br>
<p class="justify">&nbsp; &nbsp; Setiap halaman HTML setidaknya memiliki struktur dasar yang terdiri dari : Tag DTD atau DOCTYPE, tag html, tag head, dan tag body. Inilah yang merupakan struktur paling dasar dari HTML, walaupun HTML tidak hanya berisi struktur tersebut.</p>
<!--more-->
<br>
<p class="justify">&nbsp; &nbsp; Agar lebih mudah memahaminya, silahkan buka text editor (Notepad++), lalu ketikkan kode berikut ini:</p>
<br>
<p>Contoh struktur dasar HTML:</p>
<br>
<table border="1" cellpadding="5">
<tr>
<td>
1. &lt;!DOCTYPE html&gt;
  <br>
2. &nbsp; &lt;html&gt;
<br>
3. &lt;head&gt;
<br>
4. &nbsp; &lt;title&gt;Title dari Websiteku&lt;/title&gt;
<br>
5. &nbsp; &lt;/head&gt;
<br>
6. &lt;body&gt;
<br>
7. &nbsp; &lt;p&gt;Selamat Pagi Dunia, Hello World!&lt;/p&gt;
<br>
8. &lt;/body&gt;
<br>
9. &lt;/html&gt;
<br>
</td>
</tr>
</table>
<br>
<p class="justify">&nbsp; &nbsp; Save sebagai halaman.html dan jalankan file dengan cara double klik file tersebut, atau klik kanan –> Open With –> Firefox.</p>
<br>
<center><img src="/img-asset/contoh-struktur-html.png"></center>
<br>

`Pengertian DTD atau DOCTYPE`

<p class="justify">&nbsp; &nbsp; Tag paling awal dari contoh HTML diatas adalah DTD atau DOCTYPE. DTD adalah singkatan dari Document Type Declaration. Yang berfungsi untuk memberi tahu kepada web browser bahwa dokumen yang akan diproses adalah HTML.</p>
<br>
<p class="justify">&nbsp; &nbsp; Jika kita tidak menuliskan DTD, browser akan tetap menampilkan dan memproses halaman web kita seperti tidak terjadi apa-apa. Namun browser sebenarnya menjalankan halaman HTML tersebut pada mode khusus yang disebut <b>quirk mode</b>.</p>
<br>
<p class="justify">&nbsp; &nbsp; Pada <b>quirk mode</b>, web browser menerjemahkan halaman web (terutama kode CSS) sedikit berbeda dari seharusnya. Ini karena web browser menganggap bahwa ketika DTD tidak ditemuka, halaman tersebut kemungkinan besar merupakan halaman web usang. Agar halaman ‘usang’ ini tetap tampil baik, web browser perlu menggunakan aturan-aturan yang berbeda, yakni: <b>quirk mode</b>.</p>
<br>
<p class="justify">&nbsp; &nbsp; Cara untuk mengetahui apakah web browser berjalan pada quirk mode atau standard mode lebih mudah jika menggunakan web browser Mozilla Firefox. Pada Firefox, klik kanan pada halaman web, lalu pilih Page Info. Pada bagian Render Mode akan terlihat apakah quirk mode, atau standard mode.</p>
<br>
<p> Seperti screenshoot berikut ini 😲👇</p>
<br>
<center><img src="/img-asset/quirk-mode.png"></center>
<br>

`Tag &lt;html&gt;`

<br>
<p class="justify">&nbsp; &nbsp; Setelah DTD, tag berikutnya adalah tag &lt;html&gt;.</p>
<br>
<p class="justify">&nbsp; &nbsp; Ini adalah tag pembuka dari keseluruhan halaman web. Semua kode HTML harus berada di dalam tag ini. Tag html dimulai dengan &lt;html&gt; dan diakhiri dengan &lt;/html&gt; </p>
<br>

`Tag &lt;head&gt;`

<br>
<p class="justify">&nbsp; &nbsp; Elemen pada tag &lt;head&gt; umumnya akan berisi berbagai definisi halaman, seperti kode CSS, JavaScript, dan kode-kode lainnya yang tidak tampil di browser.</p>
<br>

`Tag &lt;title&gt;`

<br>
<p class="justify">&nbsp; &nbsp; Dalam contoh kita sebelumnya digunakan untuk menampilkan title dari sebuah halaman web. Title ini biasanya ditampilkan pada bagian paling atas web browser. Contohnya pada tampilan halaman.html, ‘Title dari Websiteku’ akan ditampilkan pada tab browser.</p>
<br>

`Tag &lt;body&gt;`

<br>
<p class="justify">&nbsp; &nbsp; Tag &lt;body&gt; akan berisi semua elemen yang akan tampil dalam halaman web, seperti paragraf, tabel, link, gambar, dll. Tag body ini ditutup dengan &lt;/body&gt;. Sebagian besar waktu kita dalam merancang web akan dihabiskan di dalam tag &lt;body&gt; ini.</p>
<br>
<p class="justify">&nbsp; &nbsp; Perhatikan bahwa setiap tag akan diakhiri dengan penutup tag. Termasuk &lt;html&gt; yang merupakan tag paling awal dari sebuah halaman web.
<br>
<p class="justify">&nbsp; &nbsp; pada artikel kali ini mungkin hanya sekilas struktur dasar nya next time kita akan membahas tag yang lainnya ...sekian dulu dari penulis semoga bermanfaat, see you again ✌😲</p>

😎 `Wassalamualikum wr.wb`
