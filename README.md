<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teknoloji Detoksu ve Hava Durumu</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 50px;
        }
        .container {
            max-width: 600px;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
        }
        h1 { color: #2c3e50; }
        p { line-height: 1.6; }
        .widget-container {
            margin-top: 20px;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            overflow: hidden;
            display: inline-block;
        }
        .info-box {
            margin-top: 20px;
            font-style: italic;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Başını Ekrandan Kaldır! 🌿</h1>
        <p>Teknoloji bağımlılığına son vermek için ilk adımı at. Bugün dışarıda harika bir hava olabilir. İşte senin için canlı hava durumu tahmini:</p>

        <div class="widget-container">
            <iframe 
                src="https://www.meteoblue.com/en/weather/widget/daily/istanbul_turkey_745044?geoloc=fixed&days=4&tempunit=CELSIUS&windunit=KILOMETER_PER_HOUR&precipunit=MILLIMETER&coloured=coloured&pictoicon=1&patch=1&display_sun=1&display_vivi=1&display_wind=1&display_highlow=1&display_precip=1&f_temperature=1&f_feelslike=1&f_windspeed=1&f_windgust=1&f_winddirection=1&f_humidity=1&f_precipitation=1&f_precipitationprobability=1&f_spotlight=1&f_sunshine=1&f_uv=1&layout=dark" 
                frameborder="0" 
                scrolling="NO" 
                allowtransparency="true" 
                sandbox="allow-same-origin allow-scripts allow-popups allow-popups-to-escape-sandbox" 
                style="width: 460px; height: 593px">
            </iframe>
        </div>
        <div class="info-box">
            <p>Hava güzel görünüyor, değil mi? Telefonunu burada bırak ve 15 dakikalık bir yürüyüşe çık!</p>
        </div>
    </div>

</body>
</html>
