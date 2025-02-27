<!DOCTYPE html>
<html lang="lv">
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Būvniecības Uzņēmums</title>
    <style>
        /* Vispārīgie stili */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        /* Galvenais fons ar attēlu */
        .hero {
            background-image: url('https://images.unsplash.com/photo-1560179707-f14e90ef3623?ixid=M3wxMzcxOTN8MHwxfHNlYXJjaHw2fHxvZmZpY2UlMjBidWlsZGluZ3xlbnwwfHx8fDE2ODk2NzM0MjJ8MA&ixlib=rb-4.0.3&fm=jpg&w=3368&h=2239&fit=max');
            background-size: cover;
            background-position: center;
            padding: 100px 20px;
            text-align: center;
            color: white;
            height: 100vh;
        }

        .hero h1 {
            font-size: 4em;
            margin: 0;
            text-transform: uppercase;
        }

        .hero p {
            font-size: 1.5em;
            margin-top: 20px;
        }

        /* Bloki ar tekstu un bildēm */
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 40px 20px;
            background-color: #fff;
        }

        .card {
            width: 45%;
            margin: 10px 0;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s;
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card h3 {
            font-size: 2em;
            padding: 20px;
            background-color: #003366;
            color: white;
        }

        .card p {
            padding: 20px;
            font-size: 1.1em;
            color: #333;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        /* Atgriešanās uz augšu, kad ir vairāk satura */
        .footer {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .footer a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            background-color: #005f87;
            border-radius: 5px;
        }

    </style>
</head>
<body>
    <a href="https://www.google.com" target="_blank">Atvērt Google</a>


    <!-- Hero sekcija ar fona attēlu -->
    <div class="hero">
        <h1>Būvniecības Uzņēmums</h1>
        <p>Augstākās kvalitātes celtniecības un renovācijas pakalpojumi</p>
    </div>

    <!-- Galvenais saturs -->
    <div class="content">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1560179707-f14e90ef3623?ixid=M3wxMzcxOTN8MHwxfHNlYXJjaHw2fHxvZmZpY2UlMjBidWlsZGluZ3xlbnwwfHx8fDE2ODk2NzM0MjJ8MA&ixlib=rb-4.0.3&fm=jpg&w=3368&h=2239&fit=max" alt="Būvniecība">
            <h3>Dzīvojamo ēku būvniecība</h3>
            <p>Veicam dzīvojamo ēku celtniecību, sākot no pamatiem līdz pilnīgai apdarei. Kvalitāte un drošība ir mūsu galvenās prioritātes.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1560179707-f14e90ef3623?ixid=M3wxMzcxOTN8MHwxfHNlYXJjaHw2fHxvZmZpY2UlMjBidWlsZGluZ3xlbnwwfHx8fDE2ODk2NzM0MjJ8MA&ixlib=rb-4.0.3&fm=jpg&w=3368&h=2239&fit=max" alt="Būvniecība">
            <h3>Komercēku būvniecība</h3>
            <p>Mēs piedāvājam komercēku būvniecību visā Latvijas teritorijā, nodrošinot augstu kvalitāti un profesionālu pieeju katram projektam.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1560179707-f14e90ef3623?ixid=M3wxMzcxOTN8MHwxfHNlYXJjaHw2fHxvZmZpY2UlMjBidWlsZGluZ3xlbnwwfHx8fDE2ODk2NzM0MjJ8MA&ixlib=rb-4.0.3&fm=jpg&w=3368&h=2239&fit=max" alt="Būvniecība">
            <h3>Renovācija un Apdare</h3>
            <p>Renovējam vecās ēkas, uzlabojot to struktūru, izskatu un funkcionalitāti, piešķirot tām jaunu dzīvotspēju.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1560179707-f14e90ef3623?ixid=M3wxMzcxOTN8MHwxfHNlYXJjaHw2fHxvZmZpY2UlMjBidWlsZGluZ3xlbnwwfHx8fDE2ODk2NzM0MjJ8MA&ixlib=rb-4.0.3&fm=jpg&w=3368&h=2239&fit=max" alt="Būvniecība">
            <h3>Interjera dizains</h3>
            <p>Piedāvājam pilnīgu interjera dizainu, kas atbilst mūsdienu tendencēm un jūsu vajadzībām. Veidojam funkcionālas un stilīgas telpas.</p>
        </div>
    </div>

    <!-- Apakšējā kāja ar saiti uz Google lapu -->
    <div class="footer">
        <p>Uzziniet vairāk par mūsu pakalpojumiem un projektiem.</p>
        <a href="https://www.google.com" target="_blank">Atvērt Google</a>
    </div>

</body>
</html>
