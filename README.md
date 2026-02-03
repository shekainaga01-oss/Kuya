<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Kuya Nicholas</title>
    <style>
        body {
            background-color: #fff5f5;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #4a4a4a;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            border: 2px solid #ffb7b7;
        }
        h1 { color: #d63384; margin-bottom: 10px; }
        .nickname { font-style: italic; color: #888; margin-bottom: 30px; }
        
        /* Photo Gallery */
        .photo-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin: 20px 0;
        }
        .photo-frame {
            width: 100%;
            height: 200px;
            background: #eee;
            border-radius: 10px;
            overflow: hidden;
            border: 5px solid white;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .photo-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Poem Section */
        .poem-box {
            background: #fff0f6;
            padding: 25px;
            border-left: 5px solid #d63384;
            margin: 30px 0;
            line-height: 1.8;
            font-size: 1.1rem;
            text-align: left;
        }

        .button {
            background-color: #d63384;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-size: 16px;
            transition: transform 0.2s;
        }
        .button:hover { transform: scale(1.05); }
        
        #surprise { display: none; margin-top: 20px; font-weight: bold; color: #d63384; }
    </style>
</head>
<body>

    <div class="container">
        <h1>Another Surprise, Kuya ko!</h1>
        <p class="nickname">To: Nicholas Llewellyn</p>

        <div class="photo-grid">
            <div class="photo-frame"><img src="https://scontent.fmnl4-2.fna.fbcdn.net/v/t1.15752-9/626222860_917847201199637_4915565433431787905_n.webp?_nc_cat=101&ccb=1-7&_nc_sid=0024fc&_nc_ohc=eFeW89oGjQ4Q7kNvwGBa8B3&_nc_oc=AdlYoecebXq1vYTyG7WmLoTB21aqM-2l_jiF1dISu6hoJTrC5iIkWIB9x7NpdfTBdCM7bIPg_2UsHX21SmKh5k0I&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fmnl4-2.fna&oh=03_Q7cD4gEZAkO9JyxPe2TGe03iY07rUVWnopmB9r4J8IDhvxqPyg&oe=69A91203.jpg" alt="Kuya Cool"></div>
            <div class="photo-frame"><img src="https://scontent.fmnl4-3.fna.fbcdn.net/v/t1.15752-9/623297512_913589901141926_633375061660797952_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=0024fc&_nc_ohc=s5Pi0iClNBAQ7kNvwHbtfLo&_nc_oc=AdlGTxehFna1Z0lin0NYzJ1PuOofsaj6QUYFRhmn4d2p8iYocPwG0dHgPauYbF05S-c-Jn_ACt1N3nsOovSvXRpm&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fmnl4-3.fna&oh=03_Q7cD4gGy8U_z0yy1alqx3eDX76aYUiDuIGmC-cZbWuMf49SPdA&oe=69A90D75.jpg" alt="Kuya Cute"></div>
        </div>

        <div class="poem-box">
            <strong>For My Best Kuya:</strong><br><br>
            A name that sounds like legend, bold and true,<br>
            Nicholas Llewellyn, there’s no one like you.<br>
            Through every season, the highs and the lows,<br>
            You’re the steady anchor that everyone knows.<br><br>
            More than a brother, a mentor and friend,<br>
            On your kind heart, I can always depend.<br>
            So here’s to you, Kuya, on this day of heart,<br>
            I’m so glad that being in your life is my favorite part.
        </div>

        <button class="button" onclick="showSurprise()">Click for Shoutout!</button>
        <p id="surprise">🏆 Best Kuya Award goes to you! 🏆</p>
    </div>

    <script>
        function showSurprise() {
            document.getElementById('surprise').style.display = 'block';
            alert("Nicholas Llewellyn: Legend. Brother. All-around Great Guy!");
        }
    </script>

</body>
</html>