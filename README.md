# utsdamas
portofolio dan contak dengan css dan html

Nama	: Damas Mahardi
Kelas	: Ti.16.b3
Nim	: 311610440

Layout Portopolio

mahardi.png


Layout Contact
















file portopolio.html


<!DOCTYPE html>
<html lang="en">
<head>
	<title>profile</title>
<!-- Google Fonts -->
<link href="http://fonts.googleapis.com/css?
family=Open+Sans:300italic,400italic,400,700,600"rel="stylesheet" type="te
xt/css">
<link href="http://fonts.googleapis.com/css?
family=Open+Sans+Condensed:300,300italic,700" rel="stylesheet"type="text/c
ss">
<link href="warna.css" type="text/css" rel="stylesheet" />


</head>
<body>
	<div id="container">
		<header>
		<h1>Biodata Personal</h1>
		</header>
		<nav>
			<ul>
				<li class="active"><a href="portofolio.html" title="potofolio">Portofolio</a></li>
				<li><a href="contact.html" title="contact">Contact</a></li>
			</ul>
		</nav>
		
	</div>
<div><br>
	<div>
		<img src="Mahardi.jpg">
	</div><br>
	<table border="0">
		<tr>
 <td><b>Biodata</b></td>
 </tr>
 <tr>
 
 <td>Nama Lengkap</td>
 <td>:</td>
 <td>Damas Mahardi</td>
 </tr>
 <tr>
 <td>Alamat</td>
 <td>:</td>
 <td>Griya Mutiara Asri Cb 4 No. 18</td>
 </tr>
 <tr>
 <td>TTl Lahir</td>
 <td>:</td>
 <td>12 Mei 1992</td>
 </tr>
 <tr>
 <td>Jenis Kelamin</td>
 <td>:</td>
 <td>Laki-Laki</td>
 </tr>
 <tr>
 <td>Agama</td>
 <td>:</td>
 <td>Islam</td>
 </tr>
</table>
	<footer>
		<p>&copy; 2018 - STT Pelita Bangsa Bekasi</p>
	</footer>
</div>

</body>
</html>





























file contact.html

<!DOCTYPE html>
<html>
<head>
	<title>contact</title>
	<!-- Google Fonts -->
<link href="http://fonts.googleapis.com/css?
family=Open+Sans:300italic,400italic,400,700,600"rel="stylesheet" type="te
xt/css">
<link href="http://fonts.googleapis.com/css?
family=Open+Sans+Condensed:300,300italic,700" rel="stylesheet"type="text/c
ss">
<link href="warna.css" type="text/css" rel="stylesheet" />
</head>
<body>
	<div>
		<header>
			<h1>Informasi Contact</h1>
		</header>
		<nav>
			<ul>
				<li class="active"><a href="contact.html" title="contact">contact</a></li>
				<li><a href="portofolio.html" title="portofolio">portopolio</a></li>
			</ul>

		</nav>


	</div>

<div>
	
</div><br>

<table border="0">
	<tr>
 <td><b>Kontak</b></td>
 </tr>
 <tr>
 <td>Nama</td>
 <td>:</td>
 <td>Damas Mahardi</td>
 </tr>
 <tr>
 <td>Nomor Telephon</td>
 <td>:</td>
 <td>082126994964</td>
 </tr>
 <tr>
 <td>E-mail</td>
 <td>:</td>
 <td><a href="https://www.google.com/gmail/">damasmahardi234@gmail.com</a></td>
 </tr>
 <tr>
 <td>Git Hub</td>
 <td>:</td>
 <td><a href="https://github.com/DamasMahardi">DamasMahardi</a></td>
 </tr>
</table>
<footer>
		<p>&copy; 2018 - STT Pelita Bangsa Bekasi</p>
	</footer>
</body>
</html>






































file warna.css


* {

     margin:0;
     padding:0;

     }


     body {

     line-height:1;

     font-size:100%;

    font-family:'Open Sans', sans-serif;

     color:#213184;

 }



    #container {

     width:980px;

     margin:0 auto;

    box-shadow:0 0 1em #a1a6c0;

     }
/*header */
header{

    padding: 20px;
}
header h1{
    margin: 20px 10px;
    color: #a6bdb3;
    text-align: center;
}
/*navigation*/
nav{
    display: block;
    background-color: #2e5a60;
}

nav ul{
    list-style-type: none;
}
nav ul li{

    float: left;
}
nav li a{
padding: 15px 30px;
    display: block;
    color: #fff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
}
nav .active a,
nav li:hover a {
    background-color: #346daa;
}
nav:after, nav:before{
    content:'';
    display:table;
}
nav:after{
    clear: both;
}
/* footer */
footer {
clear:both;
background-color:#364547;
padding:20px;
color:#eee;

}
/* table */
table{
 width: 1500px;
 height: 200px;
    
}

}
td,{
    width: 600px;
    background-color: blue;
}
/* gambar */
img{
    width: 300px;
    height: 300px;
    float: left;

}

