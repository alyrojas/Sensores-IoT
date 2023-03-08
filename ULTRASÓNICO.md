**Alyne Elizabeth Rojas Gloria**

# ULTRASÓNICO

## CÓDIGO
```
//Definition od constants

const int trigPin = 26;
const int echoPin = 25;

//Definition sound speed in cm/uS
#define SOUND_SPEED 0.034
#define CM_TO_INCH 0.393701

//Define variables
long duration;
float distanceCm;
float distanceInch;

void setup() {
  Serial.begin(115200);
  Serial.println("Hello, ESP32!");

  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);
}

void loop() {
  //Clears the trigPin
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2);

  //Set the trigPin on HIGH state for 10 microseconds
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);

  //Reads the echoPin, return the sound wave travel time in microseconds
  duration = pulseIn(echoPin, HIGH);

  //Calculate the distance
  distanceCm = duration * SOUND_SPEED/2;

  //Calculate to inches
  distanceInch = distanceCm * CM_TO_INCH;

  //Prints the distance in the Serial Monitor
  Serial.print("Distance (cm): ");
  Serial.println(distanceCm);

  Serial.print("Distance (inch): ");
  Serial.println(distanceInch);
  delay(1000); 
}
```
## DIAGRAMA
<img width="605" alt="image" src="https://user-images.githubusercontent.com/99991955/223622197-222a1858-5a13-4190-9a3b-22408024f6f3.png">

