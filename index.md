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
　text-align:center;
  text-shadow:2px 2px 5px #20B2AA;
　line-height:280px;
  width: 200px;
  height: 400px;
　font-size:15px;
　color:#f9c81e;
　font-family:SimHei,Microsoft YaHei;
　background-color:#fffaf3;
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
table.blueTable {
  border: 4px solid #FEFFFC;
  background-color: #FAFFE7;
  height:1200px;
}
table.blueTable td, table.blueTable th {
  border: 3px solid #F9F9F3;
  padding: 10px 10px;
}
table.blueTable tbody td {
  font-size: 23px;
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
  <h3>平假名:用於一般書寫和印刷;模仿漢字的草書演變而來的。</h3>
<table class="blueTable">
<tbody>
<tr>
<td>cell1_1</td>
<td>cell2_1</td>
<td>cell3_1</td>
<td>cell4_1</td>
<td>cell5_1</td>
<td>cell6_1</td>
<td>cell7_1</td>
<td>cell8_1</td>
<td>cell9_1</td>
<td>cell10_1</td>
<td>cell11_1</td>
<td>cell12_1</td>
</tr>
<tr>
<td>cell1_2</td>
<td>cell2_2</td>
<td>cell3_2</td>
<td>cell4_2</td>
<td>cell5_2</td>
<td>cell6_2</td>
<td>cell7_2</td>
<td>cell8_2</td>
<td>cell9_2</td>
<td>cell10_2</td>
<td>cell11_2</td>
<td>cell12_2</td>
</tr>
<tr>
<td>cell1_3</td>
<td>cell2_3</td>
<td>cell3_3</td>
<td>cell4_3</td>
<td>cell5_3</td>
<td>cell6_3</td>
<td>cell7_3</td>
<td>cell8_3</td>
<td>cell9_3</td>
<td>cell10_3</td>
<td>cell11_3</td>
<td>cell12_3</td>
</tr>
<tr>
<td>cell1_4</td>
<td>cell2_4</td>
<td>cell3_4</td>
<td>cell4_4</td>
<td>cell5_4</td>
<td>cell6_4</td>
<td>cell7_4</td>
<td>cell8_4</td>
<td>cell9_4</td>
<td>cell10_4</td>
<td>cell11_4</td>
<td>cell12_4</td>
</tr>
<tr>
<td>cell1_5</td>
<td>cell2_5</td>
<td>cell3_5</td>
<td>cell4_5</td>
<td>cell5_5</td>
<td>cell6_5</td>
<td>cell7_5</td>
<td>cell8_5</td>
<td>cell9_5</td>
<td>cell10_5</td>
<td>cell11_5</td>
<td>cell12_5</td>
</tr>
<tr>
<td>cell1_6</td>
<td>cell2_6</td>
<td>cell3_6</td>
<td>cell4_6</td>
<td>cell5_6</td>
<td>cell6_6</td>
<td>cell7_6</td>
<td>cell8_6</td>
<td>cell9_6</td>
<td>cell10_6</td>
<td>cell11_6</td>
<td>cell12_6</td>
</tr>
</tbody>
</table> 
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
