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
<img width="748" alt="image" src="https://user-images.githubusercontent.com/99991955/224513690-0afd1c91-ab0e-4aa4-a056-7c9186e62585.png">

