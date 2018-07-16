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
　font-weight:bold;
　background-color:#f9c81e;
}
#body{
　width:360px;
　height:280px;
　text-align:center;
　line-height:280px;
　font-size:15px;
　color:#f9c81e;
　font-weight:bold;
　background-color:#fffaf3;
}
#Footer{
　width:360px;
　height:80px;
　text-align:center;
　line-height:80px;
　font-size:15px;
　color:#fffaf3;
　font-weight:bold;
　background-color:#f9c81e;
}
.tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: #f1f1f1;
}
.tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
}
.tab button:hover {
    background-color: #ddd;
}
.tab button.active {
    background-color: #ccc;
}
.tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
</style>
</head>
<body>
  <div id="Header">五十音</div>
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
  <h3>漢字使用上約五千字，交談、閱讀至少需熟記兩千字</h3>

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
