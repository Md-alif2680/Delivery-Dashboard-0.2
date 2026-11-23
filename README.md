<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#101f3d">
<link rel="manifest" href="manifest.webmanifest">
<title>KaP Dashboard</title>
<style>
body {
background:#101f3d;
color:white;
font-family:Arial;
text-align:center;
padding-top:80px;
}
h1 {font-size:45px;}
button {
background:#e52c3b;
color:white;
padding:15px 30px;
border:0;
border-radius:12px;
font-size:18px;
}
</style>
</head>
<body>
<h1>KaP</h1>
<p>Khilkhet Agent Performance</p>
<a href="https://claude.ai/artifact/W8GZC4BYpT4MdAu4qxnCrp">
<button>Open Dashboard</button>
</a>
<script>
if ('serviceWorker' in navigator) {
navigator.serviceWorker.register('sw.js');
}
</script>
</body>
</html>
