<html>
<head>
<style type="text/css">
#Header{
　width:360px;
　height:80px;
　text-align:center;
　line-height:80px;
　font-size:15px;
　color:#fffaf3;
　font-family:SimHei,Microsoft YaHei;
　background-color:#f9c81e;
}
#body{
　width:360px;
　height:280px;
　text-align:center;
　line-height:280px;
　font-size:15px;
　color:#f9c81e;
　font-family:SimHei,Microsoft YaHei;
　background-color:#fffaf3;
}
#Footer{
　width:360px;
　height:80px;
　text-align:center;
　line-height:80px;
　font-size:15px;
　color:#fffaf3;
　font-family:SimHei,Microsoft YaHei;
　background-color:#f9c81e;
}
.tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: black;
    font-family:SimHei,Microsoft YaHei;
}
.tab button {
    font-family:SimHei,Microsoft YaHei;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
    
}
.tab button:hover {
    background-color:lightblue;
}
.tab button.active {
    background-color: orange;
}
.tabcontent {
    display: none;
    padding: 8px 12px;
    text-shadow: 2px 2px 5px blue;
    background-color:black;
    font-family:SimHei,Microsoft YaHei;
}
</style>
</head>
<body>
<div id="Body"> </div>
<div class="tab">
  <button class="tablinks" onclick="openCity(event, '平假名')">平假名</button>
  <button class="tablinks" onclick="openCity(event, '片假名')">片假名</button>
  <button class="tablinks" onclick="openCity(event, '漢字')">漢字</button>
</div>

<div id="平假名" class="tabcontent">
  <h3>平假名:用於一般書寫和印刷;模仿漢字的草書演變而來的。</h3>
  
</div>

<div id="片假名" class="tabcontent">
  <h3>片假名:用於標記外來語及特殊詞彙；模仿漢字的楷書、擷取一部分寫成</h3>
   
</div>

<div id="漢字" class="tabcontent">
  <h3>漢字使用上約五千字，交談、閱讀無礙至少需熟稔兩千字</h3>

</div>

<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}
</script>
     
</body>
