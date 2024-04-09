
const Engine = Matter.Engine;
const World = Matter.World;
const Bodies = Matter.Bodies;
const Body = Matter.Body;

function preload()
{


	rotator1 =  (rotate.x , rotate.y, height.h, width.j);
	rotater2 =  (rotate.x , rotate.y, height.h, width.j);
	rotater3 = (rotate.x , rotate.y, height.h, width.j);



Matter.Body.rotate(rotater1,angle1)
Push();
ranslate(rotater1.position.xotater1.position.y);
onpopstate(angle1);
rect(0,0,150,20);
Pop();
angle1 +=0.2
}

function setup() {
	createCanvas(800, 700);

	update();
	Engine.update(engine);

	engine = Engine.create();
	world = engine.world;

	//Crie os Corpos aqui.

	var plane_options={
		isStatic: true
	}

	fill ();
	rectmode();
	ellipsemode();

	var particle_options = {
		restituition:0.4,
		friction:0.02
	}

	rotator1 = Bodies.rectangle(250,200150,20, rotator_options);
	World.add(world,rotator1);


	Engine.run(engine);
  
}


function draw() {
  rectMode(CENTER);
  background(0);
  elipse();
  drawSprites();
 
}



