**Alyne Elizabeth Rojas Gloria**

# REED SWITCH

## CÓDIGO
```
const int pinSensor = 26;
const int pinLED = 25;

void setup() {
  //configurar pin como entrada con resistencia pull-up interna
  pinMode(pinSensor, INPUT_PULLUP);
  pinMode(pinLED, OUTPUT);
}

void loop() {
  int value = digitalRead(pinSensor);

  if (value == LOW) {
    digitalWrite(pinLED, HIGH);
  } else {
    digitalWrite(pinLED, LOW);
  }

  delay(1000);
}
```
## DIAGRAMA
<img width="655" alt="image" src="https://user-images.githubusercontent.com/99991955/224514117-59047ae7-4947-4047-9116-0011eff29510.png">
