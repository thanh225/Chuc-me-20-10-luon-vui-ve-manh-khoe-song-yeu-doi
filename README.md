<style type="text/css">
.hovergallery img{
-webkit-transform:scale(0.8); /*Webkit: Scale down image to 0.8x original size*/
-moz-transform:scale(0.8); /*Mozilla scale version*/
-o-transform:scale(0.8); /*Opera scale version*/
-webkit-transition-duration: 0.5s; /*Webkit: Animation duration*/
-moz-transition-duration: 0.5s; /*Mozilla duration version*/
-o-transition-duration: 0.5s; /*Opera duration version*/
opacity: 0.7; /*initial opacity of images*/
margin: 0 10px 5px 0; /*margin between images*/
}
.hovergallery img:hover{
-webkit-transform:scale(1.1); /*Webkit: Scale up image to 1.2x original size*/
-moz-transform:scale(1.1); /*Mozilla scale version*/
-o-transform:scale(1.1); /*Opera scale version*/
box-shadow:0px 0px 30px gray; /*CSS3 shadow: 30px blurred shadow all around image*/
-webkit-box-shadow:0px 0px 30px gray; /*Safari shadow version*/
-moz-box-shadow:0px 0px 30px gray; /*Mozilla shadow version*/
opacity: 1;
}
</style>

<body style="background-image:url(img/backgr.jpg)">
<center>
        <audio id="time" src="audio/Huyen-Thoai-Me-Dam-Vinh-Hung.mp3" controls autoplay="autoplay">
            <source src="audio-file.ogg" type="audio/ogg" />
            <source src="audio-file.mp3" type="audio/mpeg" />
        </audio>
</center>

<marquee id="marq" scrollamount="3" loop="50" scrolldelay="0" class="hovergallery">
    <img src="img/h1.jpg" width="300" height="300"/> 
    <img src="img/lc1.jpg" width="300" height="300"/> 
    
    <img src="img/h2.jpg" width="300" height="300"/> 
    <img src="img/lc2.jpg" width="300" height="300"/> 
    
    <img src="img/h3.jpg" width="300" height="300"/> 
    <img src="img/lc3.jpg" width="300" height="300"/> 
    
    <img src="img/h4.jpg" width="300" height="300"/> 
    <img src="img/lc4.jpg" width="300" height="300"/> 
    
    <img src="img/h5.jpg" width="300" height="300"/> 
    <img src="img/lc5.jpg" width="300" height="300"/> 
    
    <img src="img/h6.jpg" width="300" height="300"/> 
    <img src="img/lc6.jpg" width="300" height="300"/> 
    
    <img src="img/h7.jpg" width="300" height="300"/> 
    <img src="img/lc7.jpg" width="300" height="300"/> 
    
    <img src="img/h9.jpg" width="300" height="300"/> 
    <img src="img/lc9.jpg" width="300" height="300"/> 
    
    <img src="img/h10.jpg" width="300" height="300"/> 
    <img src="img/lc10.jpg" width="300" height="300"/> 
    
    <img src="img/lc8.jpg" width="300" height="300"/> 
    
</marquee>

