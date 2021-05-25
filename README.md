# melody2814.github.io
function setup() {
	createCanvas(600,600);
	background(100);
}
	function mousePressed(){
	var r=random(50,200)
	for(i=0;i<10;i++){
	fill(random(255),0,random(255))
ellipse(mouseX+i*5,mouseY,r)
	
	}
	
}
