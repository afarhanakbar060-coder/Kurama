<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kelompok Tulip</title>
    <style>
        /* Gaya dasar halaman */
        body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #FFC0CB; /* Latar belakang pink muda */
            color: #333333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        /* Wadah utama */
        .container {
            text-align: center;
            padding: 30px;
            background: rgba(255, 255, 255, 0.6); /* Efek transparan putih tipis */
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            max-width: 500px;
            width: 90%;
        }

        /* Judul Kelompok */
        h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #d15276; /* Warna pink yang lebih gelap untuk kontras */
        }

        /* Daftar Anggota */
        .member-list {
            list-style: none;
            padding: 0;
            margin: 20px 0;
        }

        .member-list li {
            font-size: 1.2rem;
            margin: 10px 0;
            padding: 10px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            text-transform: capitalize;
        }

        /* Teks Bergerak (Running Text) */
        .running-text-container {
            overflow: hidden;
            white-space: nowrap;
            background-color: #ffffff;
            padding: 10px 0;
            border-radius: 20px;
            margin-top: 25px;
            box-shadow: inset 0 2px 5px rgba(0,0,0,0.05);
        }

        .running-text {
            display: inline-block;
            font-size: 1rem;
            font-weight: bold;
            color: #555555;
            padding-left: 100%;
            animation: jalan 10s linear infinite;
        }

        /* Animasi untuk teks bergerak */
        @keyframes jalan {
            0% {
                transform: translate(0, 0);
            }
            100% {
                transform: translate(-100%, 0);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Nama Kelompok -->
        <h1>Kelompok Tulip</h1>
        
        <!-- Daftar Anggota -->
        <ul class="member-list">
            <li>Aira</li>
            <li>Alya</li>
            <li>Arthur</li>
            <li>Farhan</li>
        </ul>

        <!-- Teks Bergerak -->
        <div class="running-text-container">
            <div class="running-text">Desain oleh Farhan &nbsp;&bull;&nbsp; Desain oleh Farhan &nbsp;&bull;&nbsp; Desain oleh Farhan</div>
        </div>
    </div>

</body>
</html>
