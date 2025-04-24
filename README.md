html
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Dinda Aulia Natasya</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            color: white;
            text-align: center;
            scroll-behavior: smooth;
        }
        header {
            padding: 60px;
            background: rgba(0, 0, 0, 0.5);
            border-bottom: 5px solid #ffd700;
            position: relative;
        }
        header img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            margin-bottom: 15px;
            border: 4px solid #ffd700;
            box-shadow: 0 0 15px rgba(255, 215, 0, 0.6);
        }
        nav {
            background: rgba(0, 0, 0, 0.7);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 30px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #000000;
        }
        section {
            padding: 60px 20px;
        }
        .project {
            background: rgba(255, 255, 255, 0.15);
            padding: 20px;
            margin: 20px auto;
            border-radius: 15px;
            width: 80%;
            max-width: 600px;
            transition: transform 0.3s, background 0.3s;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
        }
        .project:hover {
            transform: scale(1.05);
            background: rgba(255, 255, 255, 0.25);
        }
        #contact {
            background: rgba(0, 0, 0, 0.6);
            padding: 50px;
        }
        .social-icons {
            margin-top: 20px;
        }
        .social-icons a {
            color: #d59dc7;
            font-size: 24px;
            margin: 0 15px;
            transition: color 0.3s;
        }
        .social-icons a:hover {
            color: #d59dc7;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dinda Aulia Natasya</h1>
        <p>Mahasiswa | Conten Creator</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about"><i class="fas fa-user"></i> Tentang Saya</a></li>
            <li><a href="#projects"><i class="fas fa-briefcase"></i> Proyek</a></li>
            <li><a href="#contact"><i class="fas fa-envelope"></i> Kontak</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>Tentang Saya</h2>
        <p>Saya adalah mahasiswa Universitas Lampung, dari Program Studi Pendidikan Teknologi Informasi, Kelas 24B.</p>
    </section>
    
    <section id="projects">
        <h2>Proyek</h2>
        <div class="project">
            <h3>Tugas Tokoh Perintis Grafika Komputer</h3>
            <p>TUGAS 1.</p>
            <p><strong>Link Video:</strong> 
                <a href="https://drive.google.com/file/d/1mN1Q2wmTdB_eoHhd-jipODGcxRlFZOtM/view?usp=drive_link" target="_blank" style="color:#fdfdfd;">Tap Hare</a>
              </p>
              <p><strong>Dokumen PDF:</strong> 
                <a href="dokumen/Tokoh_Perintis.pdf" target="_blank" style="color:#f9f9f9;">Lihat PDF</a>
              </p>
        </div>
        <div class="project">
            <h3>Tugas Garis</h3>
            <p>Tugas 2.</p>
            <p><strong>Link Video:</strong> 
                <a href="https://youtu.be/AAxLupcZe5Q?si=0WxF4IlwOWrdniRf" target="_blank" style="color:#ffffff;">Tap Here</a>
              </p>
              <p><strong>Dokumen PDF:</strong> 
                <a href="dokumen/Tugas_Garis.pdf" target="_blank" style="color:#ffffff;">Lihat PDF</a>
              </p>
        </div>
        <div class="project">
            <h3>Tugas Lingkaran Bresenham Dan Midpoint</h3>
            <p>TUGAS 3.</p>
            <p><strong>Link Video:</strong> 
                <a href="https://youtu.be/2Ylv7Nap2-8?si=KFxQ5-zoBbhSQ8Kw" target="_blank" style="color:#ffffff;">Tap Here</a>
              </p>
              <p><strong>Dokumen PDF:</strong> 
                <a href="dokumen/Tugas_Lingkaran.pdf" target="_blank" style="color:#ffffff;">Lihat PDF</a>
              </p>
        </div>
        <div class="project">
            <h3>Tugas Kurva</h3>
            <p>Tugas 4.</p>
            <p><strong>Link Video:</strong> 
                <a href="https://youtu.be/2U4qKDACwsY" target="_blank" style="color:#ffffff;">Tap Here</a>
              </p>
              <p><strong>Dokumen PDF:</strong> 
                <a href="dokumen/tugas_kurva.pdf" target="_blank" style="color:#ffffff;">Lihat PDF</a>
              </p>
    </section>
    
    <section id="contact">
        <h2>Kontak</h2>
        <p>Email: <a href="mailto:dindaaulianatasya91@gmail.com">dindaaulianatasya91@gmail.com</a></p>
        <p>Instagram: <a href="https://www.instagram.com/dinda.ntsy_?igsh=MXg3NnI0bDJwenZlYg==" target="_blank">Instagram</a></p>
        <div class="social-icons">
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </section>
</body>
</html>
