# 21-2-19 
farenthaittocelcius
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  var tempMtyF=55.4;
tempMtyC = farenhaitToC(tempMtyF);
console.log(tempMtyC);
  
}
 
function farenhaitToC(tempF){
  var tempC;
  	tempC = (5/9)*(tempF-32);
  return tempC
}
