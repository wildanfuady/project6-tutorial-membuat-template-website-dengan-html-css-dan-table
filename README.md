Tutorial Membuat Template Website Menggunakan HTML, CSS dan Table

Halo, silahkan baca tutorial lengkapnya. Di sini saya menggunakan table sebagai model untuk membangun templatenya. Saya harap, Anda sudah terbiasa menggunakan table ini ya.

Baik, mari kita mulai.

Pertama buat file HTML dan beri nama project6.html dan berikut scriptnya:

<html>
<head>
<title>Project 6 - Rumah Coding</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
<table width="1000" border="1" class="badan_tabel">
    <tr>
      <td colspan="2" class="header"><img src="headerlogo.jpg" class="img"></td>
    </tr>
    <tr>
      <td colspan="2" bgcolor="#5b4a02" class="menu">
         <ul class="list_menu" align="center">
           <li><a href="https://www.saungit.web.id">HOME</a></li>
           <li><a href="https://www.saungit.web.id/p/about.html">ABOUT</a></li>
           <li><a href="#">PAGE1</a></li>
           <li><a href="#">PAGE2</a></li>
           <li><a href="#">PAGE3</a></li>
           <li><a href="#">PAGE4</a></li>
           <li><a href="#">PAGE5</a></li>
           <li><a href="#">PAGE6</a></li>
           <li><a href="#">PAGE7</a></li>
           <li><a href="#">PAGE8</a></li>
           <li><a href="#">PAGE9</a></li>
           <li><a href="#">PAGE10</a></li>
           <li><a href="https://www.saungit.web.id/p/contact.html">CONTACT</a></li>
         </ul>
      </td>
    </tr>
    <tr>
      <td colspan="2" width="800">
        <div class="content">
          <!-- title -->
          <h1>H1 Sample Brown Background</h1>
          <!-- square -->
          <div class="square">
            <div class="square-list">
              <P>SQUARE</P>
            </div>
            <div class="square-list">
              <P>SQUARE</P>
            </div>
            <div class="square-list">
              <P>SQUARE</P>
            </div>
          </div>
          <hr>
          <div class="content-page">
            <h2>H2 - Lorem Ipsum</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque quis dignissim risus. Integer id orci sit amet ex eleifend lobortis. Vivamus vel metus ex. Donec quis justo eros. Praesent ut velit eget dolor posuere scelerisque. Pellentesque facilisis neque non ex rutrum, non mollis felis hendrerit. Nulla nec velit volutpat, ullamcorper nulla a, facilisis nibh. Nulla aliquet nibh in lobortis facilisis. In a nisl id ipsum euismod lobortis. Aliquam tincidunt, purus eget ultrices gravida, risus quam tristique augue, eget rutrum libero tellus non nisl. Curabitur at vulputate ex, id consectetur ante.</p>

            <p>Fusce nulla arcu, sodales sed eleifend at, euismod bibendum eros. Vivamus aliquet, erat in vehicula consequat, nisl lacus hendrerit sem, ac congue felis enim ut ex. Nunc viverra tempus purus sit amet dictum. Etiam tincidunt ut est vel tincidunt. Aliquam a nunc posuere ligula egestas ornare. Nunc sollicitudin nisl eget pellentesque fringilla. Aenean cursus mattis neque vitae tempor. Etiam ac urna eu tellus congue imperdiet. Vestibulum scelerisque tempus est vitae ultricies. Nulla sapien nisl, ornare in fringilla sit amet, convallis quis ipsum.</p>

            <p>Praesent mollis odio vitae odio ultricies iaculis. Praesent lobortis, felis convallis tempor volutpat, massa arcu tempus purus, quis dapibus orci sem in libero. Aliquam at dui non risus venenatis accumsan quis eu ipsum. Donec lorem dolor, pulvinar vel ullamcorper id, finibus in est. Suspendisse potenti. Morbi et nisi nec est lobortis tristique. Maecenas id ipsum vel enim consequat pulvinar. Integer varius dapibus odio eu sodales. Aenean sit amet nunc eget neque vulputate tempor non sed mi.</p>

            <p>Donec sit amet convallis nisi. Proin sed nibh ultrices, sodales mauris ut, tempus ex. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Suspendisse a elit libero. Donec condimentum, justo at tempor facilisis, magna libero auctor turpis, sit amet eleifend libero sem maximus arcu. Suspendisse potenti. Nam et magna malesuada, faucibus nisl eget, euismod lorem. Nam vehicula dictum diam, et laoreet risus bibendum eget. Donec dapibus hendrerit augue, porta finibus leo mollis in.</p>

            <p>Aliquam ac porttitor ligula. Suspendisse dapibus, quam non elementum mattis, nunc est lacinia neque, sit amet molestie tortor nisl in dui. Suspendisse quis tempus purus. Vestibulum eleifend urna quis turpis bibendum rutrum. Curabitur et sodales libero, ut feugiat enim. Sed non augue ut massa congue ornare. Cras aliquet ante eu tristique ornare. Donec non vehicula dui, quis efficitur lacus. Nam pulvinar, lacus a malesuada vulputate, dui erat accumsan neque, ut dignissim libero ipsum quis risus. Vestibulum tempus urna ipsum, a laoreet nibh fringilla id. Sed ac pharetra nibh. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Ut interdum massa sit amet lorem vulputate egestas. Morbi tincidunt elit nibh.</p>

            <hr>
            <p>Publish web adalah cara untuk mempublikasikan web statis ataupun     dinamis yang sudah kita buat agar dapat dilihat oleh user melalui browser. Agar dapat diakses oleh user untuk sebuah website, kita memerlukan domain dan hosting.</p>
            <p>Bagi anda yang belum mengetahui apa itu domain singkat cerita domain adalah sebuah nama alamat yang nantinya akan digunakan user untuk mengakses, melihat atau menampilkan halaman web kita.</p>
            <p>Domain diatur sedemikian rupa sehingga memudahkan kita dalam mengakses sebuah webserver, karena kita tidak perlu lagi menuliskan alamat sebuah webserver dalam bentuk IP address.</p>
            <strong>Berikut cara mempublish website anda:</strong><br>
            <ol>
               <li>Mendapatkan domain</li>
               <li>Setting nama server di domain</li>
               <li>Mendapatkan hosting</li>
               <li>Upload website</li>
               <li>Instal database</li>
               <li>Tes hasil</li>
            </ol>
          </div>
      </div>
      </td>
    </tr>
    <tr>
      <td colspan="2" bgcolor="#E5E5E5" class="footer"><center>Created By <a href="https://www.wildanfuady.com">Wildan Fuady</a> | <a href="https://www.saungit.web.id">Saung IT</a></center></td>
    </tr>
</table>
</body>
</html>

Langkah berikutnya silahkan buat file bernama style.css dan berikut scriptnya:

body{
	margin: 0 auto;
}
.badan_tabel{
 margin: auto;
 border: 1px solid #999999;
 background: #5b4a02;
}
.header{
 background-color: #5b4a02;
 padding: 5px;
 height:100px;
 text-align: center;
}
.img{
	width: 60%;
	height: 80%;
}
.menu{
	text-align: center;
}
.list_menu{
 background-color: #5b4a02;
 margin: 0px;
 width: auto;
 padding: 0px;
}
.list_menu li{
 float:left;
 display:block;
 font-family: "Arial";
 font-weight: 700;
 text-align: center;
 list-style-type: none;
 border-right-width:1px;
 border-right-style:solid;
 border-right-color:#5b4a02;
 padding:10px;
}
.list_menu li:hover{
 background-color: #FFFFFF;
}
.list_menu li a{
 text-decoration: none;
 color: #fff;
}
.list_menu li a:hover{
 font-weight:bold;
 color:#5b4a02;
 background-color: #FFFFFF;
}
table{
 border-collapse:collapse;
}
.content{
	background: #fff;
	width: 800px;
	margin: 0 auto;
	margin-top: 20px;
	margin-bottom: 20px;

}
h1{
	color: #5b4a02;
	text-align: center;
	padding-top: 40px;
	padding-bottom: 40px;
}
.square{
	width: 800px;
	height: 250px;
}
.square-list{
	background: #7e6000;
	width: 200px;
	height: 200px;
	margin-left: 40px;
	margin-right: 20px;
	float: left;
}
.square-list p{
	color: #fff;
	text-align: center;
	font-weight: 700;
	padding-top: 50px;
	font-size: 20pt;
}
hr{
	width: 80%;
	border: 0;
	border-top: 1px dashed #8c8c8c;
	text-align: center;
}
.content-page{
	padding: 20px;
}
.content-page h2{
	color: #7e6000;
}
.content-page p{
	text-align: justify;
}
.footer{
	height: 50px;
	font-family: "Arial";
	font-size: 14pt;
	font-weight: 700;
	color: #333;
}
.footer a{
	text-decoration-line: none;
	color: #333;
}
.footer a:hover{
	color: #5b4a02;
}

Selesai. Happy Coding!
