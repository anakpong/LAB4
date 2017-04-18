int p1 = 7; 
int p2 = 8; 
int p3 = 9; 
void setup() { }
void loop() 
{ two(); delay(100); 
one(); delay(100); 
three(); delay(100); 
four(); delay(100); 
five(); delay(100); 
six(); delay(100); } 
void one() {
pinMode(p1, INPUT); 
pinMode(p2, OUTPUT); 
pinMode(p3, OUTPUT); 
digitalWrite(p1, LOW); 
digitalWrite(p2, HIGH); 
digitalWrite(p3, LOW);
} void two() { 
pinMode(p1, INPUT); 
pinMode(p2, OUTPUT); 
pinMode(p3, OUTPUT); 
digitalWrite(p1, LOW); 
digitalWrite(p2, LOW); 
digitalWrite(p3, HIGH); } 
void three() { 
pinMode(p1, OUTPUT); 
pinMode(p2, INPUT); 
pinMode(p3, OUTPUT); 
digitalWrite(p1, LOW); 
digitalWrite(p2, LOW); 
digitalWrite(p3, HIGH); } 
void four() { 
pinMode(p1, OUTPUT); 
pinMode(p2, INPUT); 
pinMode(p3, OUTPUT); 
digitalWrite(p1, HIGH); 
digitalWrite(p2, LOW); 
digitalWrite(p3, LOW); } 
void five() { 
pinMode(p1, OUTPUT); 
pinMode(p2, OUTPUT); 
pinMode(p3, INPUT); 
digitalWrite(p1, HIGH); 
digitalWrite(p2, LOW); 
digitalWrite(p3, LOW); } 
void six() { 
pinMode(p1, OUTPUT); 
pinMode(p2, OUTPUT);
pinMode(p3, INPUT); 
digitalWrite(p1, LOW); 
digitalWrite(p2, HIGH); 
digitalWrite(p3, LOW); }
