<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        * {
            box-sizing: border-box;
        }
    body {
        margin: 0;
        font-family: 微軟正黑體;
    }
    .container {
        max-width: 1200px;
        margin: auto;
    }
    .navbar_logo {
        width: 50px;
        float: left;
    }
    .navbar_link_all {
        display: table;
        float: left;
        margin-top: 16px; 
    }
    .navbar_link {
        color: #023114;
        padding: 15px;
    }
    .banner {
        width: 100%;
        height: 120vh;
        background-image: url(https://media1.giphy.com/media/xTiTnoHt2NwerFMsCI/200w.webp?cid=790b76115cc08e64746e774232319555);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
    .fuck {
        margin: 15px;
        width: calc(33.33% - (15px*2));
        float: left;
        padding: 10px;
        border: 20px solid rgb(129, 253, 170);
    }
    .fuck_img {
        width: 100%;
        height: 200px;
    }
    .fuck_bg {
        width: 100%;
        height: 200px;
        background-size: contain;
        background-repeat: no-repeat;
        background-position: center;
        background-image: url(https://d279m997dpfwgl.cloudfront.net/wp/2017/08/trumpthumbsweb.jpg);
    }
    .fuck_title {
        color: #666;
        text-align: center;
    }
    .fuck_main {
        font-size: 16px;
    }
    .fuck_link {
        float: right ;
        padding: 15px;
        background-color: #c475b8;
        color: #fff;
        text-decoration: none;
    }
    .clear {
        clear:both;
    }
    .slider_container {
    margin: 30px auto;
    width: 315px;
    height: 300px;
    position: relative;
    border: 10px solid;    
    border-color: rgb(117, 93, 255);
    border-bottom-width: 100px;
    background-color: #7e0b6e;
    box-shadow: rgb(0, 0, 0) 0 0 5px;
    }
    .slider_container div {
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0;
    filter: alpha(opacity=0);
    }
    .slider_container div {
    -webkit-animation: round 25s linear infinite;
            animation: round 25s linear infinite;
}
@-webkit-keyframes round {
    4% {
        opacity: 1;
        filter: alpha(opacity=100);        
    }
    20% {
        opacity: 1;
        filter: alpha(opacity=100);        
    }
    24% {
        opacity: 0;
        filter: alpha(opacity=0);       
    }
}
@keyframes round {
    4% {
        opacity: 1;
        filter: alpha(opacity=100);        
    }
    20% {
        opacity: 1;
        filter: alpha(opacity=100);        
    }
    24% {
        opacity: 0;
        filter: alpha(opacity=0);        
    }
}
.slider_container div:nth-child(5) {
    -webkit-animation-delay: 0s;
            animation-delay: 0s;
}

.slider_container div:nth-child(4) {
    -webkit-animation-delay: 5s;
            animation-delay: 5s;
}

.slider_container div:nth-child(3) {
    -webkit-animation-delay: 10s;
            animation-delay: 10s;
}

.slider_container div:nth-child(2) {
    -webkit-animation-delay: 15s;
            animation-delay: 15s;
}

.slider_container div:nth-child(1) {
    -webkit-animation-delay: 20s;
            animation-delay: 20s;
}
.slider_container span {    
    color: rgb(255, 255, 255);
    background: rgb(85, 62, 87);
    position: absolute;
    left: 0%;
    top: 280px;
    width: 300px;
    height: 100px;
    font-size: 30px;
    text-align: center;
    line-height: 100px;
    -webkit-transform:scaleY(0);
        -ms-transform:scaleY(0);
            transform:scaleY(0);
    -webkit-transition: all 0.5s ease-in-out;
            transition: all 0.5s ease-in-out;
}
.slider_container:hover span {
    width: 100%;
    -webkit-transform:scaleY(1);
        -ms-transform:scaleY(1);
            transform:scaleY(1);
}
.slider_container:hover div {
    -webkit-animation-play-state: paused;
            animation-play-state: paused;
}
.run {
    font-size:20px;
    background: #000;
    color: #f5f5f5;
}
.fuck_text {
    color: rgb(110, 15, 110);
    font-weight: bold;
}
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="container">
            <img class ="navbar_logo" src="https://media3.giphy.com/media/wJNGA01o1Zxp6/200.webp?cid=790b76115cc08dd34d3968646f48cfb9" 
            >
            <div class="navbar_link_all">
                <a class="navbar_link" href="https://zh.wikipedia.org/wiki/%E5%94%90%E7%B4%8D%C2%B7%E5%B7%9D%E6%99%AE">偶像介紹</a>
                <a class="navbar_link" href="https://www.google.com/search?q=trump&source=lnms&tbm=isch&sa=X&ved=0ahUKEwil6LfgmujhAhXIyosBHT8mB1UQ_AUIDigB&biw=1536&bih=722">偶像帥照</a>
            </div>
        </div>
        <div class="clear"></div>
    </nav>
    <div class="banner"></div>
    <div class="container">
        <div class="fuck">
            <div class="fuck_bg"></div>
                    <h1 class="fuck_title">自我介紹</h1>
                    <p class="fuck_main">
                    <h2>彭福麒</h2>
                    <h3>認真、負責、理性、熱誠</h3>
                        --我擅長3D遊戲美術的工作，包括建模、拆解貼圖、動作設計等，還有基本的2D美術繪製與合成。
                    <p>--在校內的專題實務與平時作業上有累積相當的製作經驗，期望自身所學能於職場上應用。</p>
                    --曾任於專題組內的企劃負責，對於專案規劃、內容設計、市場調查有一定的了解，也善於與人溝通來處理各項問題。
                    若能有幸進入貴公司，必定精進自身且維持熱誠學習下去。
                    </p>
        </div>
        <div class="fuck">
            <div class="fuck_bg"></div>
                    <h1 class="fuck_title">所學歷程</h1>
                    <p class="fuck_main">
                        <h2>高中學習歷程</h2>
                        電腦硬體相關應用、Visual Basic程式語言、機器人邏輯程式編譯軟體、數位邏輯等相關資訊。
                    </p>
                    <p>
                        <h2>大學學習歷程</h2>
                        各式多媒體 主要包含: PhotoShop、Illustrator、InDesign、AfterEffects、Premiere、DreamWeaver、3DsMax，還有Unity遊戲引擎與網頁程式設計。
                    </p>
                    <p>
                        <h2>參加競賽</h2>
                        台北海洋科技大學-海洋創客實務3D列印設計競賽
                    </p>
        </div>
        <div class="fuck">
            <div class="fuck_bg"></div>
                <h1 class="fuck_title">作品集相關</h1>
                <p class="fuck_main">
                    <h2>材質研究</h2>
                        <img src="https://i.imgur.com/oaP2US5.jpg" height="232.5">
                        以上的內容針對各種V-ray材質設定去做研究，嘗試調出理想的模樣，最後利用V-ray插件渲染出圖片。
                </p>
                    <p>
                        <h2>模型相關</h2>
                        <div class="slider_container">                            
                                <div>
                                    <img src="https://imgur.com/Imv6ouM.jpg"alt="pure css3 slider"  height="222" />
                                    <span class="info">Soldier model</span>
                                </div>
                                <div>
                                    <img src="https://imgur.com/xdFPLSj.jpg"alt="pure css3 slider"  height="222" />
                                    <span class="info">Small boss model</span>
                                </div>
                                <div>
                                    <img src="https://imgur.com/z9wNmLJ.jpg"alt="pure css3 slider"  height="222" />
                                    <span class="info">Protagonist</span>
                                </div>
                                <div>
                                    <img src="https://imgur.com/KQ6Pfoz.jpg"alt="pure css3 slider"  height="222" />
                                    <span class="info">Princess (Trial model)</span>
                                </div>
                                <div>
                                    <img src="https://imgur.com/IG7hjbR.jpg"alt="pure css3 slider"  height="222" />
                                    <span class="info">Pipe organ</span>
                                </div>    
                                <div class="clear"></div>                           
                        </div>
                        <div class="fuck_text">以上包含專題內容所製作的模型，也有參賽用和作業用的。除了參賽用的3D列印模型以外，面數均4000面左右。</div>
                    </p>
        </div>
    </div>
    <div class="clear"></div>    
    <div>
        <marquee class="run" direction="right" height="30" scrollamount="5" behavior="alternate">Welcome~</marquee>
    </div>
    
</body>
</html>
