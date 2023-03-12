**Alyne Elizabeth Rojas Gloria**

# PHOTORESISTOR

## CÓDIGO
```
int pin = 25;

#define sensor_pin 14

void setup(){
  pinMode(pin, OUTPUT);
  pinMode(sensor_pin, INPUT);

  Serial.begin(115200);
}

void loop(){
  digitalWrite(pin, digitalRead(sensor_pin));

}
```
## DIAGRAMA
<img width="657" alt="image" src="https://user-images.githubusercontent.com/99991955/224518792-fe46514f-80d9-4bf5-9a3d-66c79f6f7630.png">
