# transformation-test
<div class="wrapper">
<span id="slide" >MO</span>
<span id="slide2" >NIKA</span>
<span id="slide3" >AL</span>
<span id="slide4" >ISAUSKAITE</span>
</div>
.wrapper {
    position: relative;
    overflow: hidden;
    width: 400px;
    height: 100px; 
}

#slide {
    position: absolute;
    left: 0px;
    width: 100px;
    height: 100px;
    -webkit-animation: slide 2s forwards;
    animation: slide 2s forwards;
    -webkit-animation-delay: 1.5s;
  -moz-animation-delay: 1.5s;
  animation-delay: 1.5s;
}


#slide2 {
    position: absolute;
    left: 30px;
    width: 100px;
    height: 100px;
    -webkit-animation: fadeOut 3s forwards;
    animation: fadeOut 3s forwards;

}
#slide3 {
    position: absolute;
    left: 230px;
    width: 100px;
    height: 100px;
    -webkit-animation: slideRIGHT 2s forwards;
    animation: slideRIGHT 2s forwards;
        -webkit-animation-delay: 1.5s;
  -moz-animation-delay: 1.5s;
  animation-delay: 1.5s;

}

#slide4 {
    position: absolute;
    left: 260px;
    width: 100px;
    height: 100px;
    -webkit-animation: fadeOut 3s forwards;
    animation: fadeOut 3s forwards;


}


@-webkit-keyframes slide {
    50% { left: 0px; }
    100% { left: 100px; }
}

@keyframes slide {
    100% { left: 100px; }
}

@-webkit-keyframes slideRIGHT {
    100% { left: 130px; }
}

@keyframes slideRIGHT {
    100% { left: 130px; }
}

 @-webkit-keyframes fadeOut {
            0% {opacity: 1;}
            100% {opacity: 0;}
         }
         
         @keyframes fadeOut {
            0% {opacity: 1;}
            100% {opacity: 0;}
         }
