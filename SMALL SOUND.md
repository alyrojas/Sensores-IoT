**Alyne Elizabeth Rojas Gloria**

# SMALL SOUND

## CÓDIGO
```
const int pinLED = 25;
const int pinMicrophone = 26;

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
<img width="748" alt="image" src="https://user-images.githubusercontent.com/99991955/224513721-0d3bab27-b7a8-41ab-a0a2-dc3cdb11fe47.png">

