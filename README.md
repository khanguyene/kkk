<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tour Du Lịch</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="icon" type="image/x-icon" href=" C:\Users\Public\OneDrive\Documents\HTML\Tour du lịch\Logo\a-travel-themed-logo.ico">
   
</head>
<style> 
body{
background-color: white;
margin: 0;
padding: 0;
}
/*Thanh điều hướng ngang*/
ul{
    list-style: none;
    padding: 0;
    margin:0;
     overflow: hidden;
  background-color: #0a99cd;
  justify-content: center;
   display: flex;
}

ul li{
    margin:0;
}
ul li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
/*Hiệu ứng khi di chuyển chuột vào*/
ul li a:hover{
    background-color: rgb(6, 79, 138);
}
/*Ảnh nền trang web*/
img {
  
  height: 100%;
  width: auto;
  display:block;
}
.contaiter img{
  text-align: center;
}
/*Câu sologan*/
h1{
    text-align: center;
    color: rgb(28, 171, 223);
}
nav-bar{
    display: flex;
  align-items: center;
  background-color: #2f13d3;
  padding: 10px 20px;

}
h2{
  color: rgb(28, 171, 223);
  font-size: 30px;
}
p{
   font-size: 25px;
}
/* Chỉnh sữa Menu ẩn,menu con*/
ul li ul.dropdown {
  display: none;
  position: absolute;
  background-color: #0a99cd;
  min-width: 160px;
  z-index: 1;
  flex-direction: column;
}

/* Hiển thị menu con khi di chuột vào  */
ul li:hover ul.dropdown {
  display: block;
}

/* Kiểu hiểu thị  menu con */
ul li ul.dropdown li a {
  padding: 12px 16px;
  text-align: left;
  color: white;
}
/*Hiệu ứng chuột khi di chuột vào*/
ul li ul.dropdown li a:hover {
  background-color: rgb(21, 85, 168);
}
  


</style>

<body>
   <!-- Đầu tang web -->
    <header>
     
        
          <ul>
            <li><a href="##"> Trang chủ</a></li>

            <li> 
              <a href="####"> Tour Trong Nước</a>
           <ul class="dropdown"> 
               <li><a href="#">Du Lịch Hội An</a></li>
               <li><a href="#">Du Lịch Vịnh Hạ Long</a></li>
               <li><a href="#">Du Lịch Đà Lạt</a></li>
               <li><a href="#">Du Lịch Đà Nẵng</a></li>
               <li><a href="#">Du Lịch TP HCM</a></li>
               <li><a href="#">Du Lịch Tây Nguyên</a></li>
               <li><a href="#">Du Lịch Hà Nội</a></li>
               <li><a href="#">Du Lịch Lai Châu</a></li>
               <li><a href="#">Du Lịch SaPa</a></li>
               <li><a href="#">Du Lịch Tây Bắc</a></li>
               <li><a href="#">Du Lịch Điện Biên</a></li>
          </ul>
          </li>
            <li>
              <a href="###">Tour Trung Quốc</a>
               <ul class="dropdown">
                <li><a href="#"> Du Lịch Thượng Hải</a></li>
                <li><a href="#">Tu Lịch Vạn Lý TRường Thành</a></li>
                <li><a href="#">Du Lịch Hàng Châu</a></li>
                <li><a href="#">Du Lịch Thanh Đảo</a></li>
                <li><a href="#">Du Lịch Quế Lâm</a></li>
                <li><a href="#">Du Lịch Tân Cương</a></li>
                <li><a href="#">Du Lịch Thâm Quyến</a></li>



               </ul>
            </li>
            <li>
              <a href="###">Tour Mùa Hè</a>
              <ul class="dropdown">
              <li><a href="#">Du Lịch Mộc Châu</a></li>
              <li><a href="#">Du Lịch Biển Quảng Ninh</a></li>
                <li><a href="#">Du Lịch Biển Nha Trang</a></li>
                <li><a href="#">Du Lịch Nghệ An</a></li>
                <li><a href="#">Du Lịch Phú Quốc</a></li>
                <li><a href="#">Du Lịch Phú Yên</a></li>
                <li><a href="#">Du Lịch Quy Nhơn</a></li>
                <li><a href="#">Du Lịch Phan Thiết</a></li>

              </ul>
            </li>
            <li>
              <a href="####">Tour Mùa Đông</a>
              <ul class="dropdown"> 
                <li><a href="#"> Du Lịch Hàn Quốc</a> </a></li>
                <li><a href="#"> Du Lịch Nhật Bản</a> </li>
                <li><a href="#"> Du Lịch Đài Loan</a> </li>
                <li><a href="#"> Du Lịch Thái Lan</a> </li>
                <li><a href="#"> Du Lịch Singapore</a> </li>
                <li><a href="#"> Du Lịch Malaysia</a> </li>
                <li><a href="#">Du Lịch canada</a></li>

              </ul>
            </li>
           
          </ul>
          <h1><b>Hãy đến với chúng tôi TraVel City,nơi sẽ đưa bạn đi khắp thế giới</b> </h1>
        
    </header>
    <!-- Ảnh nền trang web -->
    <div class="container">   
 <img src="https://i.ibb.co/GfGgfqzZ/Screenshot-2025-10-27-113829.png" alt="ảnh" >

 </div>
     <h2>   <u>  khám Phá </u> Travel city</h2>
     <p>Hãy tận hưởng trải nghiệm du lịch chuyên nghiệp, </p>
     <p>mang lại cho bạn những khoảnh khắc tuyệt vời và nâng tầm cuộc sống. </p>
     <p> Chúng tôi cam kết mang đến những chuyến đi đáng nhớ, giúp bạn khám phá thế giới theo cách hoàn hảo nhất.</p>


  </div>




</body>



</html>
