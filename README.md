# 1-de-febrero
Actividad 1 encendido y apagado de 3 leds.

int red=4;
int green=5;
int blue=3;

void setup() {
pinMode(red,OUTPUT);
pinMode(green,OUTPUT);
pinMode(blue,OUTPUT);
}

void loop() {
digitalWrite(red,HIGH);
delay(500);
digitalWrite(red,LOW);
delay (500);
digitalWrite(green,HIGH);
delay (500);
digitalWrite(green,LOW);
delay (500);
digitalWrite(blue,HIGH);
delay (500);
digitalWrite(blue,LOW);
delay (500);
}
