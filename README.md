<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portofolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
        }
        section {
            padding: 20px;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        .profile {
            text-align: center;
            padding: 20px;
        }
        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }
        .project {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portofolio</h1>
    </header>
    <section id="profile">
        <div class="container profile">
            <img src="img/profilephoto.jpg" alt="Foto Profil">
            <h2>Ni Made Deni Sikiandani</h2>
            <p>Information Technology Udayana University</p>
        </div>
    </section>
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>A final-year student at Udayana University with an interest in artificial intelligence, data science, and cloud computing. Have good skills in 
using Ms Office and familiar with processing data with various software. Able to adapt to new environment and can work together with the 
team.</p>
        </div>
    </section>
    <section id="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project">
                <h3>Proyek 1</h3>
                <p>Deskripsi singkat proyek.</p>
                <a href="#">Lihat Detail</a>
            </div>
            <div class="project">
                <h3>Proyek 2</h3>
                <p>Deskripsi singkat proyek.</p>
                <a href="#">Lihat Detail</a>
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Kontak</h2>
            <p>Email: contoh@email.com</p>
            <p>GitHub: <a href="https://github.com/username" target="_blank">github.com/username</a></p>
        </div>
    </section>
</body>
</html>
