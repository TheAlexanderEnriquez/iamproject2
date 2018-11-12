# iamproject2
Disctration Free game (processing Code)
//project 2 stuff

int circleOneX, circleOneY;//Circle One Pos
int circleTwoX, circleTwoY;//Circle Two Pos
int circleThreeX, circleThreeY;//Circle Three Pos
int circleFourX, circleFourY;//Circle Four Pos
int circleFiveX, circleFiveY;//Circle Five Pos
int circleSixX, circleSixY;//Circle Six Pos
int circleSevenX, circleSevenY;//Circle Seven Pos
int circleEightX, circleEightY;//Circle Eight Pos
int circleNineX, circleNineY;//Circle Nine Pos



void setup(){
 size(375,812);
 background(255);
 circleOne = color(255);
}

void draw(){
  //LINE ONE
 stroke(195);
 fill(255,0,0);
 ellipse(width/2/2.5, height/2/2, 100,100);//button 1
 ellipse(width/2, height/2/2, 100,100);//button 2
 ellipse(width/1.25, height/2/2, 100,100);//button 3
 //LINE TWO
 ellipse(width/2/2.5, height/2, 100,100);//button 4
 ellipse(width/2, height/2, 100,100);//button 5
 ellipse(width/1.25, height/2, 100,100);//button 6
 //LINE THREE
 ellipse(width/2/2.5, height/1.3, 100,100);//button 7
 ellipse(width/2, height/1.3, 100,100);//button 8
 ellipse(width/1.25, height/1.3, 100,100);//button 9
}
