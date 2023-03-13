function setup() {
createCanvas(400, 400);
}

function draw() {
background(255)

fill(245,193,118);
rect(110,75,180,100); // 머리

fill(245,193,118);
rect(160,175,80,80); // 몸통

fill(245,193,118);
quad(160,255, 240,255, 250,285, 150,285); // 하의?

fill(245,193,118);
rect(170,285,25,60); // 다리1

fill(245,193,118);
rect(205,285,25,60); // 다리2

push(0);
fill(245,193,118);
translate(width / 2, height / 2);
rotate(PI/6);
rect(-65,10,25,70); // 팔1
pop(0);

push(0);
fill(245,193,118);
translate(width / 2, height / 2);
rotate(PI/-6);
rect(40,10,25,70); // 팔2
pop(0);

fill(0);
triangle(200,140, 215,155, 185,155); // 입

fill(0);
ellipse(165,115,16); // 눈1

fill(0);
ellipse(235,115,16); // 눈2
}