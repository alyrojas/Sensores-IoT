**Alyne Elizabeth Rojas Gloria**

# BUZZER

## CÓDIGO
```
int buzzerPin = 26; // ajusta este número al pin que estás usando
int tiempo = 500; // ajusta este número al tiempo de duración del sonido

void setup() {
  pinMode(buzzerPin, OUTPUT); // establece el pin como salida
}

void loop() {
  digitalWrite(buzzerPin, HIGH); // enciende el buzzer
  delay(tiempo); // espera el tiempo establecido
  digitalWrite(buzzerPin, LOW); // apaga el buzzer
  delay(tiempo); // espera el tiempo establecido antes de empezar de nuevo
}
```
## DIAGRAMA
<img width="634" alt="image" src="https://user-images.githubusercontent.com/99991955/224514649-26825606-704a-405f-b2a1-344d24cf42dd.png">
