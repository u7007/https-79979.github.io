<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>高雄油漆專業服務 - 洪重發油漆工程</title>
    <style>
        body { font-family: Arial, sans-serif; background: #f4f4f4; margin: 0; padding: 0; }
        .container { max-width: 800px; margin: 40px auto; background: #fff; padding: 20px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
        h1 { margin-bottom: 10px; }
        p { line-height: 1.6; color: #333; }
        select { padding: 8px; font-size: 16px; }
        .info { margin-top: 20px; }
        img { display: block; max-width: 100%; height: auto; margin: 10px auto; }
        .contact { margin-top: 30px; font-weight: bold; color: #555; }
        .services { margin-top: 40px; }
        .services h2 { margin-bottom: 10px; }
        .services ul { list-style: disc inside; color: #333; }
        footer { text-align: center; padding: 10px; font-size: 14px; color: #777; }
    </style>
</head>
<body>
    <div class="container">
        <h1>高雄油漆洪重發油漆工程</h1>
        <p>歡迎使用我們的線上服務展示平台，選擇您想要了解的技術或服務類型，立即查看詳細說明與範例圖片。</p>
        
        <label for="techSelect"><strong>請選擇項目：</strong></label>
        <select id="techSelect">
            <option value="">-- 室內外油漆粉刷專業服務 --</option>
            <option value="html">室內油漆</option>
            <option value="css">外牆油漆</option>
            <option value="js">防水塗裝</option>
        </select>
        
        <div class="info" id="info"><p>請選擇一項服務來查看詳細內容。</p></div>
        <img id="techImage" src="" alt="" style="display: none;">
        
        <div class="services">
            <h2>我們的主要服務項目</h2>
            <ul>
                <li>室內牆面粉刷：客廳、臥室、廚房、浴室</li>
                <li>外牆彈性漆：耐候抗裂、防水防霉</li>
                <li>頂樓與陽台防水塗裝：PU、防水劑、滲透型塗料</li>
                <li>木作與鐵件噴漆：門窗、家具、欄杆等</li>
                <li>特殊裝飾漆：藝術漆、清水模效果漆</li>
            </ul>
        </div>
        
        <div class="contact">聯絡方式：高雄油漆 洪重發油漆工程 | 0915189498</div>
    </div>
    
    <script>
        document.getElementById('techSelect').addEventListener('change', function() {
            var infoDiv = document.getElementById('info');
            var image = document.getElementById('techImage');
            var value = this.value;
            
            var data = {
                html: {
                    text: '室內油漆：採用環保低VOC乳膠漆，適合客廳、臥室、廚房與浴室，色彩多樣，無異味。',
                    img: 'https://via.placeholder.com/600x300?text=室內油漆'
                },
                css: {
                    text: '外牆油漆：使用彈性防水塗料，有效防止裂縫與漏水，延長建築使用壽命。',
                    img: 'https://via.placeholder.com/600x300?text=外牆油漆'
                },
                js: {
                    text: '防水塗裝：頂樓、陽台及地下室專業防水，採用PU、防水滲透劑等多種配方。',
                    img: 'https://via.placeholder.com/600x300?text=防水塗裝'
                }
            };
            
            if (data[value]) {
                infoDiv.innerHTML = '<p>' + data[value].text + '</p>';
                image.src = data[value].img;
                image.style.display = 'block';
            } else {
                infoDiv.innerHTML = '<p>請選擇一項服務來查看詳細內容。</p>';
                image.style.display = 'none';
            }
        });
    </script>
    <footer>© 2025 高雄油漆 洪重發油漆工程 All Rights Reserved.</footer>
</body>
</html># https-79979.github.io
website
### 高雄油漆0915189498
室內油漆
外牆油漆
漆工承包
木工油漆
防水牆面
噴漆服務
牆面翻新
室內裝潢
油漆施工
外牆粉刷
