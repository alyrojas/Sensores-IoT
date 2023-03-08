**Alyne Elizabeth Rojas Gloria**

# BIG SOUND

## CÓDIGO
```
const int pinLED = 13;
const int pinMicrophone = 9;

void setup ()
{
  pinMode (pinLED, OUTPUT);
  pinMode (pinMicrophone, INPUT);
}
 
void loop ()
{
  bool soundDetected = digitalRead(pinMicrophone);
  if (soundDetected)
  {
    digitalWrite (pinLED, HIGH);
    delay(1000);
  }
  else
  {
    digitalWrite (pinLED, LOW);
    delay(10);
  }
}
```
## DIAGRAMA
