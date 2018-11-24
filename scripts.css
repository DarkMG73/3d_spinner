$( document).ready(function() {


var rotX;
var rotY;
var rotZ;
var rotTurn;


function initValues() {
  
  rotX = '-15';
  rotY = '-15';
  rotZ = '0';
  rotTurn = 15;
  rotateIt();
}
initValues();


function rotateIt() {
  
  jQuery('#master-parent').css('transform', 'rotateX(' + rotX + 'deg) rotateY(' + rotY + 'deg) rotateZ(' + rotZ + 'deg) ');
  
}


jQuery('#reset-btn').click(function(){
   
  initValues();
});


jQuery('#rotate-down-btn').click(function(){

  rotX = rotX - rotTurn;
  
  rotateIt();
});


jQuery('#rotate-up-btn').click(function(){
  
  rotX = (+rotX) + (+rotTurn); 
  
  rotateIt();
});


jQuery('#rotate-left-btn').click(function(){

  rotY = (+rotY) + (+rotTurn);
   
  rotateIt();
});
  

jQuery('#rotate-right-btn').click(function(){

  rotY = rotY - rotTurn;

  rotateIt();
});
 

jQuery('#rotate-zup-btn').click(function(){

  rotZ = (+rotZ) + (+rotTurn);

  rotateIt();
});


jQuery('#rotate-zdwn-btn').click(function(){

  rotZ = rotZ - rotTurn;

  rotateIt();
});


}); // END document.ready
