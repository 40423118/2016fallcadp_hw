Title: w10 4連桿Excel超級製圖員
Date: 2016-11-17 
Category: Misc
Tags: I will be HOKAGE!!!!!!!!!
Author:stevenGOODhaha


<!-- PELICAN_END_SUMMARY -->

##Solvedpace平面4連桿模擬kappa:
<img src="./../data/kappa w10.png" width="800" />

用點座標在excel畫圖kappa get:
<img src="./../data/kappa kappa w10.png" width="800" />


<p>繪圖流程, 導入程式庫, 啟動, 然後引用各種模組開始繪圖</p>
<!-- 導入 Brython 標準程式庫 -->

<script type="text/javascript" 
    src="https://cdn.rawgit.com/brython-dev/brython/master/www/src/brython_dist.js">
</script>

<!-- 啟動 Brython -->

<script>
window.onload=function(){
brython(1);
}
</script>

<!-- 以下實際利用  Brython 畫兩條直線 -->

<canvas id="japanflag1" width="600" height="200"></canvas>

<script type="text/python3">
from browser import document as doc
import math
# 準備繪圖畫布
canvas = doc["japanflag1"]
ctx = canvas.getContext("2d")

# 以下可以利用 ctx 物件進行畫圖
# 先畫一條直線
ctx.beginPath()
# 設定線的寬度為 1 個單位
ctx.lineWidth = 1
# 將畫筆移動到 (100, 100) 座標點
ctx.moveTo(100, 100)
# 然後畫直線到 (150, 200) 座標點
ctx.lineTo(150, 200)
# 畫右上左下的斜線
ctx.moveTo(150, 100)
ctx.lineTo(100, 200)
# 設定顏色為藍色, 也可以使用 "rgb(0, 0, 255)" 字串設定顏色值
ctx.strokeStyle = "blue"
# 實際執行畫線
ctx.stroke()
ctx.closePath()
</script>

<!-- 以下實際利用  Brython 畫上下垂直線 -->








This is the end of this week!!!

