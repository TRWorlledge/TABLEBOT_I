// Phase I TABLEBot Code
 
#include <Servo.h>               // Load "Servo" library
Servo servoLeft;                 // Left drive servo
Servo servoRight;                // Right drive servo

int val6 = 0;            // Set value for IR sensor
int val7 = 0;
int val8 = 0;
int val9 = 0;

int x = 0;            // Variable for counting distance

void setup(){
  Serial.begin(9600);                   // Setup serial monitor for debug
  servoLeft.attach(2);                  // Set left servo to pin 2
  servoRight.attach(3);                 // Set right servo to pin 3
  
  pinMode(6,INPUT);        // Set IP pins for input
  pinMode(7,INPUT);
  pinMode(8,INPUT);
  pinMode(9,INPUT);
}

void loop(){

  val6 = digitalRead(6);
  Serial.println(val6);              // debug value
  if (val6 == 1) {

x = 0;
while (x <100) {
  Stop();
  x++;
}

// x = 0;
// while (x <100) {
//  Reverse();
//‘ x++;
//

distance = 100
Reverse();

x = 0;
while (x <200) {
  Counterclockwise();
  x++;
}
}

  val7 = digitalRead(7);
  Serial.println(val7);             // debug value
  if (val7 == 1) {
    
x = 0;
while (x <100) {
  Stop();
  x++;
}

// x = 0;
// while (x <100) {
//  Reverse();
//  x++;
// }

distance = 100
Reverse();

x = 0;
while (x <100) {
  Clockwise();
  x++;
}
}

  val8 = digitalRead(8);
  Serial.println(val8);              // debug value
  if (val8 == 1) {

x = 0;
while (x <100) {
  Stop();
  x++;
}

x = 0;
while (x <100) {
  Forward();
  x++;
}

x = 0;
while (x <200) {
  Counterclockwise();
  x++;
}
}

  val9 = digitalRead(9);
  Serial.println(val9);             // debug value
  if (val9 == 1) {
    
x = 0;
while (x <100) {
  Stop();
  x++;
}

x = 0;
while (x <100) {
  Forward();
  x++;
}

x = 0;
while (x <100) {
  Clockwise();
  x++;
}
}


{
   Forward();
}
}

void Forward(){
  servoLeft.write(180);
  servoRight.write(0);
  delay(2);
}

void Counterclockwise(){
  servoLeft.write(180);
  servoRight.write(180);
  delay(2);
}

void Clockwise(){
  servoLeft.write(0);
  servoRight.write(0);
  delay(2);
}

void Left(){
  servoLeft.write(90);
  servoRight.write(180);
  delay (2);
}

void Right(){
  servoLeft.write(0);
  servoRight.write(90);
  delay (2);
}

void Stop(){
  servoLeft.write(90);
  servoRight.write(90);
  delay (2);
}

// void Reverse(){
// servoLeft.write(0);
// servoRight.write(180);
// delay(2);
// }

void Reverse() {
x = 0;
while (x < length {
servoLeft.write(0);
servoRight.write(180);
     x++;
}
}
