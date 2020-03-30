```
PFont f;
void setup(){
  size(1300,300);
    f=createFont("굴림",128);
    textFont(f);
  }
int i,a=1;
void draw(){
  background(0,0,255);
    text("안동대 컴공 사랑합니다",70,i=i+a); 
    if(i>300) i=0;
  }
void keyPressed(){
  a = key-'0'; 
  }
  ```
