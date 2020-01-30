var x;
var y;
var radius;

function setup() {
  createCanvas(600, 400);
  x = random(width);
  y = random(height);
  radius = 50;
}

function draw() {
  background(255);

  if (dist(mouseX, mouseY, x, y) < radius) {
    if (mouseIsPressed) {
      x = random(width);
      y = random(height);
    }
    fill(255, 200, 255, 200);
  }
  else {
    fill(255, 220, 200, 200);
  }

  ellipse(x, y, radius * 0.5);
  x += random(-1, 2);
  y += random(-1, 2);
}
