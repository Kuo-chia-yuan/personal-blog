<html>
<head>
<title>Page Title</title>
<style>
body {
  background-color: maroon;
  text-align: left;
  link: teal;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}
a{
    color: yellow;
    font-family:標楷體;
    text-align: left;
}
</style>
<head>
<body>

<h1>Andy Kuo</h1>
<hr>
<img src="1.jpg" alt="Avatar" style="width:300px" align="center">
<p>NAME : 郭珈源</p>
<p>CONSTELLATION : Taurus</p>
<p>STUDY : 
<ul>
  <li>桃園市振聲國中</li>
  <li>桃園市陽明高中</li>
  <li>新竹市清華大學 (資工23)</li>
</ul>
</p>
<p>INTEREST : 
<ol>
       <li>游泳</li>
       <li>健身</li>
       <li>只要遠離原文書就好</li>
</ol> 
</p>
<p>EMAIL : 17831783andy@gmail.com</p>
<p>PHONE : 0968-679-232</p>
<marquee behavior="alternate"><a href="https://kuo-chia-yuan.github.io/personal-blog/">recursion</a></marquee>

<script language="JavaScript">
function ShowTime(){
　document.getElementById('showbox').innerHTML = new Date();
　setTimeout('ShowTime()',1000);
}
</script>
<body onload="ShowTime()">
<div onclick="ChangeColor('white')" style="background-color: gray; border:3px double; width:150px;height:70px;float:right;">
<div id="showbox"></div>
