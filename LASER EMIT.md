**Alyne Elizabeth Rojas Gloria**

# LASER EMIT

## CÓDIGO
```
int laserPin = 33;
int sensor = 25; //A0
int lectura;

void setup() {
  pinMode(laserPin, OUTPUT);
  Serial.begin(9600);
  digitalWrite(laserPin, HIGH);
}

void loop() {
  lectura = analogRead(sensor);
  Serial.println(lectura);
  if(lectura < 100){
    Serial.println("Alarma");
  }
}
```
## DIAGRAMA
<img width="631" alt="image" src="https://user-images.githubusercontent.com/99991955/224515758-b0eab527-68de-4056-9c9f-521456e427e7.png">
