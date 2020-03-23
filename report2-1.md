void setup(){

  size(800,300);
  
  textSize(128);
}

int i,a=1,dir=1;

void draw(){

  fill(200);
  
  background(170,0,170);
  
  text("Graphics",i,200); 
  
  if(i>800) dir=-1;
 
  if(i<0) dir=1;
  
  i=i+dir*a;
  
}

void keyPressed(){

  a=key-'0';
  
}
