<!DOCTYPE html>
<html>
	<head>
		<title>DELTA</title>
		<link rel="icon" href="pngwing.com.png" type="image/x-icon" margin-top: 10px>
		<meta name="viewport" content="width=device-width,initial-scale=1.0">
		<meta charset="UTF-8">  
		<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.9.0/p5.min.js"></script>
  		<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.9.0/addons/p5.dom.min.js"></script>
  		<script src="https://unpkg.com/ml5@0.12.2/dist/ml5.min.js" type="text/javascript"></script>
		<style>
		* {
    		margin: 0;
    		padding: 0;
	    	box-sizing: border-box;
		}
		.navbar-logo .logo {
    		width: 200px; /* Kích thước logo */
		}
		.navbar{
			position: fixed;
			padding: 10px;
			background-color: #22092C;
			width: 100%;
			height: 70px;
    			display: flex;
    			justify-content: space-between;
    			align-items: center;
			z-index: 100000;
		}
		.navbar-links a {
    			color: white;
    			text-decoration: none;
    			margin-left: 15px;
			font-family: "Bookman";
    			font-size: 20px;
			justify-content: flex-end;
		}
		.container-wrapper {
			background-color: #ffffff;
			max-width: 45%;
    			margin: 0 auto;
    			padding: 0px;
		}
		.title{
			position: absolute;
			top: 6%;
			left: 50%;
			transform: translate(-50%, -50%);
      			color: darkblue;
			font-family: "Arial";
			font-size: 34px;
		}
    		body {
			background-image: url('https://i.pinimg.com/564x/c0/7a/fe/c07afeb533cb574188d9e4f3aa9b9a56.jpg');
      			background-color: #522258;
			width: 100%;
			height: auto;
			background-size: 25%;
			background-repeat: repeat;
		}
		section{
			padding-top:70px;
			margin-top:-74px;
			.bookman{
			font-family: 'Bookman';
			font-size: 20px;
		}
		caption{
			font-family: 'Lora';
			font-size: 25px;
		}
		th{
			padding: 15px;
			border-spacing: 10px;
		}
		td{
			padding: 5px;
		}
		h2{
			padding-left: 15px;
		}
		p{
			text-indent: 50px;
		}
		#uploadedImage, #webcamImage {
            width: 320px;
            height: auto;
            margin: 10px;
        }
        #webcamContainer {
            display: none; /* Ẩn webcam theo mặc định */
        }
        #imageUpload {
            display: none;
        }
        .custom-file-upload {
            display: inline-block;
            padding: 10px 20px;
            cursor: pointer;
            background-color: #22092C;
            color: white;
            border-radius: 5px;
            font-size: 16px;
            margin-top: 10px;
            margin-left: 20px;
        }
		</style>
	</head>
	<body>
		<header class="navbar">
			<div class="navbar-logo">
				<img src="https://deltahome.com.au/include/images/deltalogo.png" class="logo" >
			</div>
			<div class="navbar-links">
            			<a href="#Giới thiệu dự án"><b>Giới thiệu dự án</b></a>
            			<a href="#Phân công nhiệm vụ"><b>Phân công nhiệm vụ</b></a>
            			<a href="#Sản phẩm dự án"><b>Sản phẩm dự án</b></a>
			</div>
		</header>
		<p><center><img src="https://i.pinimg.com/564x/6a/9f/73/6a9f7369f52cbad18c95933dfe6353c8.jpg" width="45%" height="30%"; style="padding-top: 70px"/></center></p>
		<section id="Giới thiệu dự án">
		<div class="container-wrapper">
			<h2>I.Giới thiệu về dự án DELTA</h2>
			<p class="bookman">DELTA là dự án sử dụng AI của một chương trình tên là Teachable Machine. Mục đích chính của dự án là sử dụng AI đã được training để phân biệt các loại khoáng sản, quặng và kim loại.</p>
			<p class="bookman">DELTA nhắm tới đối tượng chủ yếu là các ngành công nghiệp liên quan đến khai thác, chế biến, sử dụng khoáng sản để phát triển. dự án DELTA là giải pháp tối ưu cũng như tiết kiệm giúp cho việc khai thác, nhận diện các khoáng sản trở nên dễ dàng nhanh chóng.</p>	 
		</div>
		</section>
		<p><center><img src="https://i.pinimg.com/564x/43/ed/65/43ed65024bae81877a2ec6396ccb0d1e.jpg" style="width:45%; height:30%"/></center></p>
		<section id="Phân công nhiệm vụ">
		<div class="container-wrapper">
			<h2>II.Bảng phân công nhiệm vụ</h2>
			<p class="bookman">Nhằm mục đích thuận tiện trong quá trình hoàn thành và phát triển dự án, nhóm chúng tôi đã làm một bảng phân công nhiệm vụ như sau:</p>
			<br><br>
			<table border="1"; style="margin: 0 auto; border-collapse: collapse">
				<caption>PHÂN CÔNG NHIỆM VỤ</caption>
					<tr style="height:30px"><th>STT</th><th>Họ và tên</th><th>Nhiệm vụ</th><th>Mức độ hoàn thành</th>
					<tr><td><center>1</center></td><td>Võ Vi An</td><td>Sưu tầm hình ảnh</td><td><center>100%</center></td>
					<tr><td><center>2</center></td><td>Nguyễn Khiếu An Khương</td><td>Sưu tầm hình ảnh</td><td><center>100%</center></td>
					<tr><td><center>3</center></td><td>Nguyễn Quốc Anh Minh</td><td><dl><dd>Sưu tầm hình ảnh</dd><dd>Lập trình</dd><dd>Training model AI</dd></dl></td><td><center>100%</center></td>
					<tr><td><center>4</center></td><td>Lê Phạm Phương Nghi</td><td>Sưu tầm hình ảnh</td><td><center>100%</center></td>
					<tr><td><center>5</center></td><td>Lê Quang Thuận</td><td>Sưu tầm hình ảnh</td><td><center>100%</center></td>
					<tr><td><center>6</center></td><td>Hà Văn Tín</td><td>Sưu tầm hình ảnh</td><td><center>100%</center></td>
			</table>
			<br>
		</div>
		</section>
		<p><center><img src="https://i.pinimg.com/736x/b7/c9/76/b7c976ac66bebc420c5e8a8ecbf801c5.jpg" style="width:45%; height:30%"/></center></p>
		<section id="Sản phẩm dự án">
		<div class="container-wrapper">
			<h2>III.Sản phẩm dự án</h2>
          <center><label for="imageUpload" class="custom-file-upload">Tải lên hình ảnh</label><label id="switchToWebcamButton" class="custom-file-upload">Sử dụng Webcam</label> <!-- Sửa đổi nút ở đây --></center>
    <div id="uploadContainer">
        <input type="file" id="imageUpload" accept="image/*">
      <center><img id="uploadedImage"></center>   
    </div>

    <!-- Phần webcam -->
    <div id="webcamContainer">
        <video id="webcam" width="320" height="240" autoplay></video>
        <canvas id="webcamCanvas" width="320" height="240"></canvas>
        <center><button id="switchToUploadButton" class="custom-file-upload">Trở về Tải lên Hình ảnh</button></center>
    </div>
    
    <p id="label"></p>

       <script src="sketch.js"></script>
		</div>
		</section>	
	</body>
</html>
