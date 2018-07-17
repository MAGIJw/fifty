<html>
<head>
<style type="text/css">
#header{
  font-family:SimHei,Microsoft YaHei;
　width:360px;
　height:80px;
　text-align:center;
　line-height:80px;
　font-size:15px;
　color:black;
　background-color:black;
}
#body{
　text-align:center;
　line-height:280px;
  width: 300px;
  height: 300px;
　font-size:15px;
　font-family:SimHei,Microsoft YaHei;
　background-color:black;
}
.tab {
    font-family:SimHei,Microsoft YaHei;
    overflow: hidden;
    border: 2px solid 	#000000;
    background-color: black;
    text-shadow:2px 2px 4px #FFFFFF;
}
.tab button {
    font-family:SimHei,Microsoft YaHei;
    float: left;
    border:#33FFFF;
    outline: none;
    cursor: pointer;
    padding: 12px 14px;
    transition: 0.3s;
    font-size: 17px;
    color:#000000;
  text-shadow:2px 2px 5px #FFFFFF;
}
.tab button:hover {
    background-color:#FFB3FF;
}
.tab button.active {
    background-color:	#FF00FF;
}
.tabcontent {
    display: none;
    padding: 8px 12px;
    text-shadow:2px 2px 5px ;
    background-color:black;
    font-family:SimHei,Microsoft YaHei;
}
table.blueTable {
  border: 4px solid #FEFFFC;
  background-color: #FAFFE7;
  height:600px;
}
table.blueTable td, table.blueTable th {
  border: 3px solid #F9F9F3;
  padding: 10px 10px;
}
table.blueTable tbody td {
  font-size: 26px;
}
table.blueTable td:nth-child(even) {
  background: #D0E4F5;
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
  <h3>平假名:用於一般書寫和印刷;模仿漢字的草書演變而來</h3>
<table class="blueTable">
<tbody>
<tr>
<td></td>
<td>あ行</td>
<td>か行</td>
<td>さ行</td>
<td>た行</td>
<td>な行</td>
<td>は行</td>
<td>ま行</td>
<td>や行</td>
<td>ら行</td>
<td>わ行</td>
<td>鼻音</td>
</tr>
<tr>
<td>あ段</td>
<td>あ　a</td>
<td>か ka</td>
<td>さ sa</td>
<td>た ta</td>
<td>な na</td>
<td>は ha</td>
<td>ま ma</td>
<td>や ya</td>
<td>ら ra</td>
<td>わ wa</td>
<td>ん<br>n</td>
</tr>
<tr>
<td>い段</td>
<td>い<br>i</td>
<td>き ki</td>
<td>し shi</td>
<td>ち chi</td>
<td>に ni</td>
<td>ひ hi</td>
<td>み mi</td>
<td></td>
<td>り<br>ri</td>
<td></td>
<td></td>
</tr>
<tr>
<td>う段</td>
<td>う<br>u</td>
<td>く ku</td>
<td>す su</td>
<td>つ tsu</td>
<td>ぬ nu</td>
<td>ふ fu</td>
<td>む mu</td>
<td>ゆ yu</td>
<td>る ru</td>
<td></td>
<td></td>
</tr>
<tr>
<td>え段</td>
<td>え<br>e</td>
<td>け ke</td>
<td>せ se</td>
<td>て te</td>
<td>ね ne</td>
<td>へ he</td>
<td>め me</td>
<td></td>
<td>れ re</td>
<td></td>
<td></td>
</tr>
<tr>
<td>お段</td>
<td>お　o</td>
<td>こ ko</td>
<td>そ so</td>
<td>と to</td>
<td>の no</td>
<td>ほ ho</td>
<td>も mo</td>
<td>よ yo</td>
<td>ろ ro</td>
<td>を wo</td>
<td></td>
</tr>
</tbody>
</table> 
</div>

<div id="片假名" class="tabcontent">
  <h3>片假名:用於標記外來語及特殊詞彙；模仿漢字的楷書、擷取一部分寫成</h3>
<table class="blueTable">
<tbody>
<tr>
<td></td>
<td>ア行</td>
<td>カ行</td>
<td>サ行</td>
<td>タ行</td>
<td>ナ行</td>
<td>ハ行</td>
<td>マ行</td>
<td>ヤ行</td>
<td>ラ行</td>
<td>ワ行</td>
<td>鼻音</td>
</tr>
<tr>
<td>ア段</td>
<td>ア　a</td>
<td>カ ka</td>
<td>サ sa</td>
<td>タ ta</td>
<td>ナ na</td>
<td>ハ ha</td>
<td>マ ma</td>
<td>ヤ ya</td>
<td>ラ ra</td>
<td>ワ wa</td>
<td>ン n</td>
</tr>
<tr>
<td>イ段</td>
<td>イ　i</td>
<td>キ ki</td>
<td>シ shi</td>
<td>ス chi</td>
<td>ニ ni</td>
<td>ヒ hi</td>
<td>ミ mi</td>
<td></td>
<td>リ ri</td>
<td></td>
<td></td>
</tr>
<tr>
<td>ウ段</td>
<td>ウ u</td>
<td>ク ku</td>
<td>ス su</td>
<td>ツ tsu</td>
<td>メ mu</td>
<td>フ fu</td>
<td>ム mu</td>
<td>ユ yu</td>
<td>ル ru</td>
<td></td>
<td></td>
</tr>
<tr>
<td>エ段</td>
<td>エ  e </td>
<td>ケ ke</td>
<td>セ se</td>
<td>テ te</td>
<td>ネ ne</td>
<td>へ he</td>
<td>メ me</td>
<td></td>
<td>レ re</td>
<td></td>
<td></td>
</tr>
<tr>
<td>オ段</td>
<td>オ　o</td>
<td>コ ko</td>
<td>ソ so</td>
<td>ト to</td>
<td>ノ no</td>
<td>ホ ho</td>
<td>モ mo</td>
<td>ヨ yo</td>
<td>ロ ro</td>
<td>ヲ wo</td>
<td></td>
</tr>
</tbody>
</table> 
</div>
<div id="漢字" class="tabcontent">
  <h3>漢字使用上約五千字，交談、閱讀無礙至少需熟稔兩千字</h3>
  <h1>Coming Soon</h1>
  <table class="blueTable">
<tbody>
 </tbody>
</table> 
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
