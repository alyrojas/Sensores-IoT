**Alyne Elizabeth Rojas Gloria**

# SMD RGB

## CÓDIGO
```
int redPin = 3; // Pin para controlar el color rojo
int greenPin = 5; // Pin para controlar el color verde
int bluePin = 6; // Pin para controlar el color azul

void setup() {
  // Configura los pines como salida
  pinMode(redPin, OUTPUT);
  pinMode(greenPin, OUTPUT);
  pinMode(bluePin, OUTPUT);
}

void loop() {
  // Enciende el LED en rojo
  analogWrite(redPin, 255); // Intensidad máxima de rojo
  analogWrite(greenPin, 0); // Sin intensidad de verde
  analogWrite(bluePin, 0); // Sin intensidad de azul
  delay(1000); // Espera 1 segundo

  // Enciende el LED en verde
  analogWrite(redPin, 0); // Sin intensidad de rojo
  analogWrite(greenPin, 255); // Intensidad máxima de verde
  analogWrite(bluePin, 0); // Sin intensidad de azul
  delay(1000); // Espera 1 segundo

  // Enciende el LED en azul
  analogWrite(redPin, 0); // Sin intensidad de rojo
  analogWrite(greenPin, 0); // Sin intensidad de verde
  analogWrite(bluePin, 255); // Intensidad máxima de azul
  delay(1000); // Espera 1 segundo

  // Enciende el LED en blanco
  analogWrite(redPin, 255); // Intensidad máxima de rojo
  analogWrite(greenPin, 255); // Intensidad máxima de verde
  analogWrite(bluePin, 255); // Intensidad máxima de azul
  delay(1000); // Espera 1 segundo
}
```
## DIAGRAMA
<img width="614" alt="image" src="https://user-images.githubusercontent.com/99991955/223618791-43e42ab3-b205-41a6-a0b1-4e8d2548104a.png">


