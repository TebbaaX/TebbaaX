<img align='right' src="https://github-readme-stats.vercel.app/api?username=adnane-x-tebbaa&show_icons=true&theme=dark" width="380">

## Whoami : 
> Hi! My Name is Adnane I'm a CyberSecurity Enthusiast/Reasearcher, Bug Bounty Hunter 
> (Mobile and Web Security),Python Programmer always in Love with Exploit-Dev / Reverse-Eng / SDR Tech and More...This is My Github Enjoy!
<img align='right' src="https://github-readme-stats.vercel.app/api/top-langs/?username=adnane-x-tebbaa" width="395">
<h3>Where to find me : </h3>
<p> <a href="https://twitter.com/TebbaaX" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" /></a> 
</p>
<img src="http://www.astroclaudine.fr/oukaimeden/Data/ImageLastFTP_AllSKY.jpg" width="418px">

**Live view of Okeimden Observatory skycam** - **Live Refreshed every 18_min**
<!DOCTYPE html>
<html>
<head>
<script>
function startTime() {
  var today = new Date();
  var h = today.getHours();
  var m = today.getMinutes();
  var s = today.getSeconds();
  m = checkTime(m);
  s = checkTime(s);
  document.getElementById('txt').innerHTML =
  h + ":" + m + ":" + s;
  var t = setTimeout(startTime, 1000);
}
function checkTime(i) {
  if (i < 10) {i = "0" + i};  // add zero in front of numbers < 10
  return i;
}
</script>
</head>

<body onload="startTime()">

<div id="txt"></div>

</body>
</html>
