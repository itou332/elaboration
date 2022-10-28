---
layout: default
title: web絵　第7項/My painting record, paragraph 7.
description: PCで描いた絵をここに記録します。<br>
このサイトはダークモードにしたり、ブラウザーを変えると見え方が少し変わります。<br> 
pc,androidのスペックでも絵が変化します。絵はsvg形式で書かれています。<br>
This is where I record the pictures I draw on my PC.<br>
This site looks a little different if you use dark mode or change your browser.<br>
The picture will also change depending on the specs of your PC or android. The pictures are written in svg format.
lang: ja_JP
---
<hedar>
<h1>7項</h1>
<p>
*献立
-<a href="https://itou332.github.io/top_page/">主項</a>
-<a href="https://itou332.github.io/">1項</a>
-<a href="https://itou332.github.io/itou332a.github.io/">2項</a>
-<a href="https://itou332.github.io/diary">3項</a>
-<a href="https://itou332.github.io/today/">4項</a>
-<a href="https://itou332.github.io/challenge/">5項</a>
-<a href="https://itou332.github.io/nontitle/">6項</a>
-<a href="https://itou332.github.io/elaboration/">7項</a>
-<a href="https://itou332.github.io/analog/">8項</a>
-<a href="https://itou332.github.io/culture/">9項</a>
-<a href="https://itou332.github.io/walk/">10項</a>
-<a href="https://itou332.github.io/pine/">11項</a>
-<a href="https://itou332.github.io/Privacy-policy/">免責事項</a>
-<a href="https://github.com/itou332">my github</a>
-<a href="http://itou33good.starfree.jp/">itou</a>
</p>
</hedar>
<head>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-REM6WSLP19"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-YWDRL1ZXBE');
</script>
<link rel="stylesheet" href="style.css">
<style>BODY,DIV,TABLE,THEAD,TBODY,TFOOT,TR,TH,TD,P { font-family:"Times New Roman"; font-size:x-small ;}svg,script {margin: 0 auto;  /* ボックス中央寄せ */}</style>
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<!-- Created with Inkscape (http://www.inkscape.org/) -->
<!-- Favicon head tag -->
<link rel="icon" type="img/x-icon" href="./favicon.png">
<link rel="apple-touch-icon" href="./images/favicon.png" sizes="180x180">
<link rel="icon" type="image/png" href="./images/favicon.png" sizes="192x192">
<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
<meta charset="utf-8">
<link rel="icon" href="images/favicon.svg" type="image/svg+xml">
<meta name="keywords" content="painting record,svg,SVG,,7項,git,推敲,elaboration">
{% seo %}
<meta name="google-site-verification" content="tQGwmktjW1w-gKuPF7mYbIZdiE9Bw_KZj8tHcro6qo0" />
</head>
<body>
<h3>2022.3/19</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_3_19.svg">

<h3>2022.3/20</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_3_20.svg">


<h3>2022.3/24</h3>

   <canvas id="myCanvas" width="200" height="200"></canvas>
   <script>
   var canvas = document.getElementById('myCanvas');
   var context = canvas.getContext('2d');
   
   
   for(var x=0;x<200;x++)
   {
           for(var y=0;y<200;y++)
           {
                   var i=-15;
                   var cx=-2+x/50;
                   var cy=-2+y/50;
                   var zx=0.06;
                   var zy=0.04; 
                   var z =zx*zy*i                       
   
                   do
                   {
                           var xt=zx*zy;
                           zx=zx*zx-zy*zy+cx;
                           zy=2*xt+cy;
                           i++;
   
                           
                   }
                   while(i<255&&(zx*zx+zy*zy)<4);
   
                   var color=i.toString(30);
                   context.beginPath();
                   context.rect(zx*x*3,(i*y+(z*zy*zy*i))*-2,(z*zy*zy*i)*30,i*i);
                   context.fillStyle ='#'+10+color+color/2;
                   context.fill();
                   
           }
           
   }
   
   </script>


<h3>2022.3/27</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_3_2.svg">


<h3>2022.3/31</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_3_31.svg">


<h3>2022.4/8</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_4_8.svg">


<h3>2022.4/9</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_4_9.svg">


<h3>2022.4/10</h3>
<img src="http://itou33good.starfree.jp/wp-content/uploads/2022/10/2022_4_10.svg">


</body>
<footer>
<p>
*献立
-<a href="https://itou332.github.io/top_page/">主項</a>
-<a href="https://itou332.github.io/">1項</a>
-<a href="https://itou332.github.io/itou332a.github.io/">2項</a>
-<a href="https://itou332.github.io/diary">3項</a>
-<a href="https://itou332.github.io/today/">4項</a>
-<a href="https://itou332.github.io/challenge/">5項</a>
-<a href="https://itou332.github.io/nontitle/">6項</a>
-<a href="https://itou332.github.io/elaboration/">7項</a>
-<a href="https://itou332.github.io/analog/">8項</a>
-<a href="https://itou332.github.io/culture/">9項</a>
-<a href="https://itou332.github.io/walk/">10項</a>
-<a href="https://itou332.github.io/pine/">11項</a>
-<a href="https://itou332.github.io/Privacy-policy/">免責事項</a>
-<a href="https://github.com/itou332">my github</a>
-<a href="http://itou33good.starfree.jp/">itou</a>
</p>
 <svg xmlns="http://www.w3.org/2000/svg" width="200" height="250">
                <text x="0" y="30" transform="rotate(45 40,40)">
                © 2022 itou Inc.
                </text>
              </svg>
            
</footer>