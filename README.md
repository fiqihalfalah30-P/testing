<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DAOP 8 Surabaya</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --navy:#0A1A2F;
      --orange:#FF7A00;
      --text:#F5F7FA;
      --gray:#D9DCE1;
      --glass:rgba(255,255,255,0.06);
    }
    *{margin:0;padding:0;box-sizing:border-box;transition:0.25s ease;font-family:'Inter',sans-serif;}
    body{background:var(--navy);color:var(--text);}
    nav{
      display:flex;justify-content:space-between;align-items:center;
      padding:18px 40px;background:var(--glass);backdrop-filter:blur(12px);
      position:sticky;top:0;z-index:1000;border-bottom:1px solid rgba(255,255,255,0.08);
    }
    nav .logo{height:55px;}
    nav a{color:white;text-decoration:none;margin-left:22px;font-weight:500;}
    nav a:hover{color:var(--orange);}    

    .hero{
      display:flex;justify-content:space-between;align-items:center;
      padding:80px 40px;gap:40px;
    }
    .hero-text{max-width:520px;}
    .hero-text h1{font-size:48px;margin-bottom:20px;color:var(--orange);}    
    .hero-text p{font-size:18px;margin-bottom:28px;line-height:1.6;}    
    .btn-primary{
      display:inline-block;background:var(--orange);color:white;
      padding:14px 26px;border-radius:12px;text-decoration:none;font-weight:600;
    }
    .btn-primary:hover{background:#ffa44c;transform:translateY(-3px);
      box-shadow:0 8px 20px rgba(255,122,0,0.35);}    

    .hero-img{width:100%;max-width:420px;border-radius:18px;
      box-shadow:0 10px 25px rgba(0,0,0,0.15);}    

    .section{padding:60px 40px;}
    .section h2{font-size:36px;margin-bottom:25px;color:var(--orange);}    
    .section h3{color:var(--gray);margin-bottom:12px;font-size:22px;}
    .section p, ul{color:var(--text);opacity:0.9;line-height:1.7;}
    ul{margin-left:22px;}

    .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px;}    
    .card{
      background:var(--glass);padding:22px;border-radius:18px;
      border:1px solid rgba(255,255,255,0.08);
    }
    .card:hover{transform:translateY(-5px);box-shadow:0 10px 25px rgba(0,0,0,0.2);}    

    footer{
      padding:35px;text-align:center;margin-top:60px;
      background:rgba(255,255,255,0.05);
      border-top:1px solid rgba(255,255,255,0.08);
    }

    @media(max-width:800px){
      .hero{flex-direction:column;text-align:center;}
    }
  </style>
</head>
<body>
  <nav>
    <img src="kai-logo.png" alt="KAI Logo" class="logo">
    <div>
      <a href="#profil">Profil</a>
      <a href="#layanan">Layanan</a>
      <a href="#berita">Berita</a>
    </div>
  </nav>

  <section class="hero">
    <div class="hero-text">
      <h1>DAOP 8 Surabaya</h1>
      <p>Mengenal lebih dekat perjalanan, layanan, dan sejarah perkeretaapian di wilayah DAOP 8 Surabaya.</p>
      <a href="#profil" class="btn-primary">Mulai Jelajahi</a>
    </div>

    <img src="images/hero.jpg" alt="Foto Kereta" class="hero-img">
  </section>

  <section id="profil" class="section">
    <h2>Profil DAOP 8 Surabaya</h2>
    <p>DAOP 8 Surabaya merupakan wilayah operasi yang menangani perjalanan kereta, perawatan fasilitas, serta pengelolaan sarana dan prasarana di wilayah Jawa Timur bagian timur. DAOP 8 mencakup jalur-jalur strategis seperti Surabaya – Malang, Surabaya – Jember, hingga Surabaya – Ketapang.</p>

    <h3 style="margin-top:25px;color:var(--gray);">Peran Teknisi Kereta</h3>
    <p>Teknisi kereta berperan dalam memastikan kondisi kereta selalu aman, layak operasi, dan nyaman bagi penumpang. Fokus pekerjaannya berada pada pemeriksaan komponen, pengecekan sistem mekanik, perbaikan kerusakan ringan hingga sedang, serta memastikan seluruh rangkaian siap beroperasi.</p>

    <h3 style="margin-top:25px;color:var(--gray);">Pengalaman Magang</h3>
    <p>Sebagai peserta magang di DAOP 8 Surabaya, khususnya di bagian kereta, pembelajaran meliputi:</p>
    <ul style="margin-left:18px;margin-top:10px;line-height:1.6;">
      <li>Memahami struktur dasar kereta dan fungsi tiap komponennya.</li>
      <li>Menganalisis kerusakan yang sering terjadi pada kereta.</li>
      <li>Mempelajari prosedur pengecekan dan standar operasional.</li>
      <li>Melihat alur kerja teknisi dari persiapan hingga finishing.</li>
    </ul>

    <h3 style="margin-top:25px;color:var(--gray);">Tinjauan Magang</h3>
    <p>Magang di DAOP 8 membantu mahasiswa memahami dunia kerja nyata, membangun kedisiplinan, serta menguatkan kemampuan teknis. Selain itu, magang memberikan wawasan luas mengenai keselamatan, budaya kerja, dan tanggung jawab dalam bidang perkeretaapian.</p>
  </section>

  <section id="layanan" class="section">
    <h2>Layanan</h2>
    <div class="cards">
      <div class="card"><h3>Cara Mengajukan Magang</h3>
<p><strong>1. Persiapan Dokumen</strong><br>
Persiapkan dokumen-dokumen penting seperti surat pengantar dari kampus atau sekolah, proposal pengajuan magang ke DAOP 8 Surabaya, CV, KTM, serta identitas diri lainnya. Semua dokumen dijadikan satu berkas.</p>

<p><strong>2. Pengajuan ke Gubeng</strong><br>
Datang langsung ke Stasiun Surabaya Gubeng dan menuju gedung administrasi DAOP 8. Untuk mahasiswa, gunakan almamater kampus. Sampaikan kepada satpam alasan dan tujuan datang, lalu kamu akan diarahkan ke bagian administrasi. Jangan lupa membawa KTP atau KTM.</p>

<p><strong>3. Proses Menunggu</strong><br>
Setelah dokumen diserahkan, proses verifikasi memerlukan waktu. Biasanya surat panggilan akan diberikan sekitar 2 minggu sebelum jadwal pelaksanaan magang. Pihak KAI akan menghubungi melalui kontak yang kamu cantumkan.</p></div>
      <div class="card"><h3>Langkah Setelah Menerima Pengumuman Magang</h3>
<p><strong>1. Membaca Surat Panggilan</strong><br>
Setelah menerima pengumuman dari KAI, cek isi surat panggilan dengan teliti: tanggal mulai magang, lokasi lapor, aturan pakaian, serta dokumen yang perlu dibawa.</p>

<p><strong>2. Menyiapkan Dokumen Awal</strong><br>
Siapkan berkas seperti fotokopi KTP/KTM, surat pengantar kampus, proposal, dan dokumen tambahan jika diminta. Pastikan semuanya sudah lengkap sebelum hari pelaporan.</p>

<p><strong>3. Kedatangan ke Lokasi Magang</strong><br>
Datang ke lokasi sesuai jadwal yang tertera, biasanya di Stasiun Sidotopo sesuai penempatan dari DAOP 8. Gunakan pakaian rapi atau almamater kampus jika diwajibkan. Sampaikan kepada satpam bahwa kamu datang untuk lapor magang.</p>

<p><strong>4. Briefing & Pembagian Penempatan</strong><br>
Peserta magang akan diarahkan untuk mengikuti briefing awal, pengenalan aturan KAI, serta pembagian tempat magang (misalnya sarana, prasarana, atau administrasi).</p>

<p><strong>5. Mulai Pelaksanaan Magang</strong><br>
Setelah proses administrasi selesai, peserta dapat mulai mengikuti kegiatan magang sesuai pembagian shift atau jadwal yang sudah ditetapkan.</p></div>
      <div class="card"><h3>Template Proposal Pengajuan Magang</h3>
<p>Berikut contoh susunan proposal pengajuan magang ke DAOP 8 Surabaya:</p>
<ul>
  <li><strong>Halaman Judul</strong> — berisi judul proposal, nama mahasiswa, NIM, prodi, dan kampus.</li>
  <li><strong>Surat Pengantar Kampus</strong> — surat resmi yang ditujukan ke DAOP 8 Surabaya.</li>
  <li><strong>Latar Belakang</strong> — alasan pengajuan magang dan manfaat bagi mahasiswa.</li>
  <li><strong>Tujuan Magang</strong> — tujuan akademik dan praktis dari pelaksanaan magang.</li>
  <li><strong>Profil Singkat Kampus</strong> — informasi universitas/sekolah.</li>
  <li><strong>Data Mahasiswa</strong> — nama, NIM/NIS, kontak, alamat, dan lampiran identitas.</li>
  <li><strong>Waktu Pelaksanaan</strong> — jadwal magang yang diajukan.</li>
  <li><strong>Penutup</strong> — ucapan terima kasih dan harapan persetujuan.</li>
</ul>
<p>Dokumen ini dapat dicetak atau dijadikan PDF sebelum diserahkan ke administrasi DAOP 8.</p>

<h4 style="margin-top:15px;color:var(--gray);">Download Template</h4>
<ul>
  <li><a href="PROPOSAL KAI clear.pdf" download style="color:var(--orange);text-decoration:underline;">Download Proposal Magang (PDF)</a></li>
  <li><a href="surat pengantar kai.pdf" download style="color:var(--orange);text-decoration:underline;">Download Surat Pengantar (PDF)</a></li>
</ul>
</div>
    </div>
  </section>

  <section id="berita" class="section">
    <h2>Berita Terkini</h2>
    <div class="cards">
      <div class="card"><h3>Judul Berita</h3><p>Ringkasan berita.</p></div>
      <div class="card"><h3>Judul Berita</h3><p>Ringkasan berita.</p></div>
      <div class="card"><h3>Judul Berita</h3><p>Ringkasan berita.</p></div>
    </div>
  </section>

  <footer>
    © 2025 DAOP 8 Surabaya — Magang Project
  </footer>
</body>
</html>
