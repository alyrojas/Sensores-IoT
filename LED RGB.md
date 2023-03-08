**Alyne Elizabeth Rojas Gloria**
# LED RGB

## CÓDIGO
```
int redPin = 27; // Pin para controlar el color rojo
int greenPin = 26; // Pin para controlar el color verde
int bluePin = 25; // Pin para controlar el color azul

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
<img width="636" alt="image" src="https://user-images.githubusercontent.com/99991955/223616844-63b89afc-ebbb-43a4-87f9-b4d9f861792f.png">
