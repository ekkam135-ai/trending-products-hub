<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Trending Products Hub</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0f172a;
color:white;
}

header{
background:linear-gradient(135deg,#ff6b00,#ff9800);
padding:25px;
text-align:center;
}

header h1{
font-size:32px;
}

header p{
margin-top:10px;
opacity:.9;
}

.search{
padding:20px;
text-align:center;
}

.search input{
width:90%;
max-width:500px;
padding:15px;
border-radius:30px;
border:none;
font-size:16px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
padding:20px;
}

.card{
background:#1e293b;
border-radius:15px;
overflow:hidden;
box-shadow:0 0 15px rgba(0,0,0,.3);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.info{
padding:15px;
}

.price{
font-size:22px;
color:#00ff99;
font-weight:bold;
margin:10px 0;
}

.old{
text-decoration:line-through;
color:#999;
font-size:14px;
}

.rating{
color:gold;
margin:8px 0;
}

button{
width:100%;
padding:12px;
border:none;
background:#ff6b00;
color:white;
font-size:17px;
border-radius:8px;
cursor:pointer;
}

button:hover
