html><head><style type="text/css" id="dcoder_stylesheet">/* Css reset */  
 * {  
   margin: 0;  
   padding: 0;  
   box-sizing: border-box;  
 }  
 /* centering the insta logo */  
 body {  
   display: flex;  
   justify-content: center;  
   align-items: center;  
   width: 100vw;  
   height: 100vh;  
   overflow: hidden;  
 }
/* main box of insta */  
 .insta {  
   width: 150px;  
   height: 150px;  
   background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285aeb 90%);  
   border-radius: 35px;  
   display: grid;  
   place-items: center;  
 }  
 /* innerbox in insta box */  
 .innerbox {  
   width: 120px;  
   height: 120px;  
   border: 10px solid #fff;  
   border-radius: 32px;  
   display: grid;  
   place-items: center;  
   position: relative;  
 } 
 /* center circle of insta */  
 .innerbox::before {  
   content: '';  
   width: 45px;  
   height: 45px;  
   border: 10px solid #fff;  
   border-radius: 50%;  
   background: transparent;  
   position: absolute;  
 }  
 /* top right circle of insta */  
 .innerbox::after {  
   content: '';  
   width: 10px;  
   height: 10px;  
   border: 2px solid #fff;  
   border-radius: 50%;  
   background: #fff;  
   position: absolute;  
   top: 8px;  
   right: 10px;  
 } 

</style></head><body><div class="insta">  
     <div class="innerbox">  
     </div>  
   </div>  </body></html>
