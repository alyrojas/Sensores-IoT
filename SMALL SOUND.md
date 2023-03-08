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
<img width="632" alt="image" src="https://user-images.githubusercontent.com/99991955/223803356-4da10cf6-6cb1-44ff-88aa-7d598ea5dbf8.png">
