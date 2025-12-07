<!DOCTYPE html>
<html lang="zh-Hant">  
<head>
    <meta charset="UTF-8">     
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> 遙咖啡 | Haruka Coffee </title>
    <style>
        /* --- 基礎樣式設定 --- */
        body {
            font-family: "Microsoft JhengHei", "Segoe UI", sans-serif; /* 設定字體 */
            margin: 0 auto;
            max-width: 800px; /* 增加最大寬度以容納交錯排版 */
            padding: 20px;    /* 設定內容與邊框距離（內邊距）*/
            line-height: 1.6; /* 設定行高*/
            color: #433b3b;
            background-color: #fdf2e0;
        }

        h1 {
            color: #5d4037;
            border-bottom: 3px solid #bcaaa4; /* 設定底部邊框  */
            padding-bottom: 5px;                /* 設定底部內邊距  */
            margin-top: 30px;                   /* 設定上方外邊距  */
        }

        /* --- 頂部區塊 --- */
        .header-section {
            text-align: left;                   /* 行內對齊 */
            margin-top: 10px;
            margin-bottom: 40px;                /* 設定下方外邊距  */
        }

        .main-logo {
            width: 100%;                        /* 填滿父容器 */
            height: auto;
            margin-bottom: 10px;                
            border-radius: 8px;                 /* 圓化邊框 */
        }

        .coffeetopic-link {
            font-size: 1.2em;                   /* 字體放大比例 */
            color: #76645d;
            text-decoration: none;              /* 不添加文字裝飾線 */
            font-weight: bold;                  /* 去除超連結底線 */
        }

        .topic {
            width: 96%;
            margin: 0 auto;
            color: #5d4037;
        }

        /* --- 列表設定 (保持原樣式) --- */
        ol, ul {
            color: #5d4037;
            padding-left: 20px;
            margin-bottom: 30px;
        }

        /* --- 圖片交錯展示 --- */
        .menu-section {
            margin-top: 40px;
        }
        
        .menu-item-row {
            display: flex;
            align-items: center;                 /* 垂直置中 */
            gap: 40px;                           /* 行 列間間距 */
            margin-bottom: 60px;                 /* 增加間距 */
        }
        
        .menu-item-row img {
            width: 45%;                          /* 圖片佔 45% 寬度 */
            height: 350px;
            object-fit: cover;                   /* 保持比例 填滿超過裁切 */
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);        /* 陰影設定 */
        }
        
        .item-description {
            width: 55%;                          /* 文字佔 55% 寬度 */
            padding: 20px;
            background-color: #feead4;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }

        /* 價格與名稱 */
        .item-description h2 {
            color: #5d4037;
            margin-top: 0;
            margin-bottom: 5px;
            font-size: 1.6em;
        }

        .item-description .price {
            color: #b05c3c; 
            font-weight: bold;
            font-size: 1.2em;
            display: block;
            margin-bottom: 15px;
        }

        /* 處理左右交錯 (奇左，偶右) */
        .menu-item-row:nth-child(even) {
            flex-direction: row-reverse; /* 圖片靠右 */
        }
      
        .images-set  {
            display: flex; 
            justify-content: space-around;
        }   

        .images-set img {
            width: 48%;
            margin-top: 10px;
            margin-bottom: 10px; 
            border-radius: 7px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }   

    </style>
</head>
<body>

    <div class="header-section">
        <img src="images/遙咖啡 門面.jpg" alt="遙咖啡招牌" class="main-logo">
        <a href="https://www.instagram.com/harukacoffee_tw?igsh=M2JkZzE3NWx5ZGZ3" class="coffeetopic-link">遙咖啡 Instagram 🔗<br> </a>
        <a href="https://maps.app.goo.gl/nw6W7ypGhVcsqGdH9" class="coffeetopic-link">地址：433臺中市沙鹿區晉武路35巷30號 <br></a>
        <font class="coffeetopic-link">營業時間（一般來說）：12:00~18:00<br></font>
        <a href="tel:+88604 2632 3630" class="coffeetopic-link">電話：04 2632 3630</a>

    <h1> 店家特色</h1>
    <ol type="1">
        <h3>
        <li>室內有許多書可以供顧客閱覽</li>
        <li>有集點卡制度可以兌換小物品</li>
        <li>傍晚向外看就是黃昏美景</li>
        </h3>
    </ol>
    
    <h1>注意事項</h1>
    <ul type="disc">
        <h3>
        <li>低消一杯飲品</li>
        <li>別跟我搶吃的</li>
        </h3>
    </ul>

    <h1>室內環境</h1>
    <p></p>
            <div class="images-set">
                <img src="images/室內景-遙咖啡.jpg" alt="室內景色" >
                <img src="images/桌子-遙咖啡.jpg" alt="室內景色">  
            </div>
        <div class="topic">
            <h3>身為京都和畫畫愛好者的老闆，室內充滿日式及美術氣息，並且擺放許多書籍可供客人借閱。舒適的光線在午後從簾縫流出，伴著80、90年代的西洋歌曲，讓客人下午可以在這幽靜的環境小憩。位置鄰近公園，也適合遛小孩的父母前往。<br></h3>
        </div>
            </div>

    <h1>招牌餐點與飲品 </h1>
    <div class="menu-section">
        
        <div class="menu-item-row">
            <img src="images/閃電戰-遙咖啡..jpg" alt="閃電戰餐點照片">
            <div class="item-description">
                <h2>閃電戰（鹽奶油捲＋蛋沙拉）</h2>
                <span class="price">價格：NT$ 80</span>
                <p>潛艇般的外型及好吃到讓人以閃電般的速度解決，令兩個抽象人類以閃電戰為此命名。</p>
            </div>
        </div>

        <div class="menu-item-row">
            <img src="images/吐司-遙咖啡.jpg" alt="吐司照片">
            <div class="item-description">
                <h2>厚切吐司</h2>
                <span class="price">價格：NT$ 80</span>
                <p>酥脆的外表加上富有口感的麵包體，淋上蜂蜜和奶油後簡直是人間美味，此物只應天上有！</p>
            </div>
        </div>

        <div class="menu-item-row">
            <img src="images/核桃奶酪-遙咖啡.jpg" alt="核桃奶酪照片">
            <div class="item-description">
                <h2>手作核桃奶酪</h2>
                <span class="price">價格：NT$ 60</span>
                <p>清爽的奶酪與香脆的核桃簡直是彼此的最佳舞伴，每一口濃郁的奶香與堅果相互呼應，幸福感爆棚。</p>
            </div>
        </div>
        
        <div class="menu-item-row">
            <img src="images/蜜桃咖-遙咖啡.jpg" alt="蜜桃咖啡照片">
            <div class="item-description">
                <h2>青森蘋果咖</h2>
                <span class="price">價格：NT$ 150</span>
                <p>當咖啡的醇厚遇上蘋果汁的清甜，碰撞出驚喜的火花。口感層次豐富，適合喜歡嘗試新鮮風味及偏好清爽的客人。</p>
            </div>
        </div>
        
        <div class="menu-item-row">
            <img src="images/抹茶-遙咖啡.jpg" alt="熱抹茶照片">
            <div class="item-description">
                <h2>日本京都抹茶拿鐵</h2>
                <span class="price">價格：NT$ 200~280</span>
                <p>嚴選抹茶不具粉感，入口順滑香醇，茶香餘韻充斥縈繞在口腔，為您獻上最精采的口腔盛宴。</p>
            </div>
        </div>
        
        <div class="menu-item-row">
            <img src="images/冰抹茶-遙咖啡.jpg" alt="冰抹茶照片">
            <div class="item-description">
                <h2>日本京都抹茶拿鐵（冰）</h2>
                <span class="price">價格：NT$ 200~280</span>
                <p>在炎熱的午後，抹茶控的最佳首選。細膩的抹茶泡沫與冰塊交融，即使是冰抹茶也不失美味標準。</p>
            </div>
        </div>

        <div class="menu-item-row">
            <img src="images/咖啡-遙咖啡.jpg" alt="冰咖啡照片">
            <div class="item-description">
                <h2>咖啡拿鐵（冰）</h2>
                <span class="price">價格：NT$ 130</span>
                <p>使用老闆精選的咖啡豆慢速萃取，口感香醇濃郁，可以自己挑選豆子，組合出自己喜好的口味。</p>
            </div>
        </div>
        
        <div class="menu-item-row">
            <img src="images/熱咖啡-遙咖啡.jpg" alt="熱咖啡照片">
            <div class="item-description">
                <h2>咖啡拿鐵</h2>
                <span class="price">價格：NT$ 130</span>
                <p>一杯手沖的熱拿鐵，溫暖您的手心與心靈。濃郁的咖啡香氣與奶香組合，讓客人可在書海中找到一片寧靜之地。</p>
            </div>
        </div>

    </div>

    <h1 style="margin-top: 60px;">黃昏美景</h1>
        <p></p>
            <div class="images-set">
                <img src="images/夕景-遙咖啡.jpg" alt="傍晚夕陽景色1" >
                <img src="images/夕景3-遙咖啡.jpg" alt="傍晚夕陽景色2">
            </div>
            <div class="topic">
            <h3>營業結束時分逼近，可從店內透過窗外欣賞上帝的作品，不同季節在畫布上有不同風格的作品讓人欣賞，為每次旅程劃下完美句點。</h3>
            </div>

</div>

</body>

</html>
