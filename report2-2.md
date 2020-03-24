PFont f;

void setup(){

size(1500,300); 

f=createFont("굴림",128);

textFont(f);

}

int i,a=1,dir=1;     

void draw(){

fill(200); 

background(170,0,170); 

text("안동대 컴공 사랑합니다",70,i); 

if(i>300) dir=-1; 

if(i<0) dir=1;

i=i+dir*a;

}

void keyPressed(){

a=key-'0';

}
