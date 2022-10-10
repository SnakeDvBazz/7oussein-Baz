<!DOCTYPE html>
<html lang="en">
    <style>
    .preloader {
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  color: #fff;
  background-color: #4684ee;
  font-family: Consolas, Menlo, Monaco, monospace;
  font-weight: bold;
  font-size: 30vh;
  z-index: 1099;
}

.preloader span {
  display: inline-block;
  opacity: 0.8;
  animation: pulse 0.4s alternate infinite ease-in-out;
}
.preloader span:nth-child(odd) {
  animation-delay: 0.4s;
  z-index: 1100;
}

@keyframes pulse {
  to {
    transform: scale(0.8);
    opacity: 0.5;
  }
}

.preloader.hidden {
  animation: fadeOut 1s;
  animation-fill-mode: forwards;
}

@keyframes fadeOut {
  100% {
    opacity: 0;
    visibility: hidden;
  }
}
/* CSS end - For Live Project */


/* Classes for Example Page Content */

.imagen {
  display: inline-block;
  height: auto;
  width: auto;
  margin: 0px;
  padding: 0px;
}
    </style>
    
    <body>
 <!-- Add this div just below the body tag -->
  <div class="preloader">
      <span>{Houssein</span>
      <span>Baz}</span>
  </div>
  
<!--  Page Content start here  -->
<!--  To test it, uncomment the code bellow  --> 
  
<!--   <div class="imagen"><img src="https://images.pexels.com/photos/1070456/pexels-photo-1070456.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260"/></div>
  <div class="imagen"><img src="https://pixabay.com/get/52e2d54b4256af14ea9d857fc32b33791d3bc3e45654794c7d2773dc9e/lighthouse-4208843.jpg"/></div>
  <div class="imagen"><img src="https://pixabay.com/get/55e3d3454d50b114b2d98679c42c30761122dfe0565974417d2678dd/summerfield-336672.jpg"/></div>
  <div class="imagen"><img src="https://pixabay.com/get/54e2d44a4e4fb14cf6da807ec32f3f7a083edbe05b54784d772c7e/baby-22194.jpg"/>
  </div>
    <div class="imagen"><img src="https://pixabay.com/get/54e5d5434b54b114b2d98679c42c30761122dfe056597440712e72d7/flower-field-250016.jpg"/>
  </div>
    <div class="imagen"><img src="https://pixabay.com/get/52e2d4444c5aaf14ea9d857fc32b33791d3bc3e45654794c7c2b7adc92/flower-4217683.jpg"/>
  </div>
    <div class="imagen"><img src="https://pixabay.com/get/54e9d3454f55ae14ea9d857fc32b33791d3bc3e45654794c7c2b7ad19f/underwater-2966572.jpg"/>
  </div>
   <div class="imagen"><img src="https://pixabay.com/get/53e8d4424854b114b2d98679c42c30761122dfe056597440712f72d2/camera-581126.jpg"/>
      <div class="imagen"><img src="https://pixabay.com/get/55e3d3464352b114b2d98679c42c30761122dfe056597440712f78dd/sundress-336590.jpg"/> -->
</body>  

</html>
