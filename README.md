# Proteus
//Define the analog pin
const int potPin = 12;
//GPI012 is input only

void 
setup() {
  Serial.begin(115200);

}

void loop() {
  int potValue = analogRead(potPin);
  
  Serial.print("Potentiometer Value: ");
  Serial.println(potValue);

  delay(200);

}
