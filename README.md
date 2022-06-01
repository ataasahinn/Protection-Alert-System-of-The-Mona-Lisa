# Protection Alert System of  Mona Lisa
## The Story of The Mona Lisa
The Mona Lisa is a half-length portrait painting by Italian artist Leonardo da Vinci. Considered an archetypal masterpiece of the Italian Renaissance, it has been described as "the best known, the most visited, the most written about, the most sung about, the most parodied work of art in the world".The painting's novel qualities include the subject's enigmatic expression, the monumentality of the composition, the subtle modelling of forms, and the atmospheric illusionism.

The painting is probably of the Italian noblewoman Lisa Gherardini, the wife of Francesco del Giocondo. It is painted in oil on a white Lombardy poplar panel. Leonardo never gave the painting to the Giocondo family, and later it is believed he left it in his will to his favored apprentice Salaì. It had been believed to have been painted between 1503 and 1506; however, Leonardo may have continued working on it as late as 1517. It was acquired by King Francis I of France and is now the property of the French Republic. It has been on permanent display at the Louvre in Paris since 1797.

**The Mona Lisa is one of the most valuable paintings in the world. It holds the Guinness World Record for the highest known painting insurance valuation in history at US$100 million in 1962 (equivalent to $870 million in 2021).**

> He groaned, "Oh, Mona, as his brush stroked her breast."

And she smiled.

> "Hold that expression, please, dearest," he asked gently.

And she smiled, still.

> "Your hair is so fine; my instruments cannot compare," he said.

Smiling, simply.

> She held her hands clasped to prevent wiggling.

Harder to hold the smile from giggling.

![Mona Lisa](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Mona_Lisa%2C_by_Leonardo_da_Vinci%2C_from_C2RMF_retouched.jpg/270px-Mona_Lisa%2C_by_Leonardo_da_Vinci%2C_from_C2RMF_retouched.jpg)

## The Theft That Made The 'Mona Lisa' A Masterpiece
In 1911 the painting was stolen, causing an immediate media sensation. People flocked to the Louvre to view the empty space where the painting had once hung, the museum’s director of paintings resigned, and the poet Guillaume Apollinaire and artist Pablo Picasso were even arrested as suspects. Two years later an art dealer in Florence alerted local authorities that a man had tried to sell him the painting. Police found the portrait stashed in the false bottom of a trunk belonging to Vincenzo Peruggia, an Italian immigrant who had briefly worked at the Louvre fitting glass on a selection of paintings, including the Mona Lisa. He and possibly two other workers had hidden in a closet overnight, taken the portrait from the wall the morning of August 21, 1911, and run off without suspicion. Peruggia was arrested, tried, and imprisoned, while the Mona Lisa took a tour of Italy before making its triumphant return to France.

During World War II the Mona Lisa, singled out as the most-endangered artwork in the Louvre, was evacuated to various locations in France’s countryside, returning to the museum in 1945 after peace had been declared. It later traveled to the United States in 1963, drawing about 40,000 people per day during its six-week stay at the Metropolitan Museum of Art in New York City and at the National Gallery of Art in Washington, D.C. It also toured to Tokyo and Moscow in 1974.

## How The Alarm System Works?
Visitors to the Louvre in Paris should have a clearer view of Leonardo da Vinci's "Mona Lisa" after the museum installed a new, more transparent form of bullet-proof glass to protect the world's most famous painting. The Mona Lisa has been behind safety glass since the early 1950s, when it was damaged by a visitor who poured acid on it. Since then there have been several other unsuccessful attempts at vandalizing the painting. Vincent Delieuvin, curator of 16th-century Italian art at the museum, told Reuters Television that glass technology has improved significantly in recent years and the painting's previous 15-year old bullet-proof glass no longer gave the best possible viewing experience.

**The sensor that will protect the Mona Lisa will be placed under the glass stand where it is exhibited. The visual distance of the sensor was adjusted according to the distance that visitors could get closest to the Mona Lisa using the SX parameter on the sensor. If any visitor gets closer to the Mona Lisa than the specified distance, they will enter the sensor's visual range and the alarm will start to sound.**

**When the alarm sounds, the danger led on the created interface system will also light up and the security guards will immediately arrive upon the scene to protect the Mona Lisa. When the danger is eliminated, the alarm system will be silenced by using the off button in the created interface system and then reactivated.**

![Exhibition Area](https://img.jakpost.net/c/2019/10/09/2019_10_09_80560_1570594311._large.jpg)

## The HC-SR501 | PIR Motion Sensor
The PIR motion detector enables motion detection by analyzing infrared radiation reflected from objects. The detector's design detects changes from 2 seperate IR windows and the amplifier converts this impulse into a high level of logic. The sensor's output can be connected to the digital input of the INP1-4D controller lan. However, it should be noted that the detector's forced low state and high state indicates PIR triggering.

The PIR sensor module can be powered from voltage 4.5V to 20V but, typically 5V is used. Once the module is powered allow the module to calibrate itself for few minutes, 2 minutes is a well settled time. Then observe the output on the output pin. Before we analyse the output we need to know that there are two operating modes in this sensor such as Repeatable(H) and Non- Repeatable(L) and mode. The Repeatable mode is the default mode.

The output of the sensor can be set by shorting any two pins on the left of the module as shown below. You can also notice two orange colour potentiometers that can be used to set the sensitivity and time which will be explained further below.

![sensor's potentiometers](https://components101.com/sites/default/files/inline-images/Using-PIR-Sensor.png)

![sensor's photos](https://components101.com/sites/default/files/inline-images/PIR-Sensor-Image.jpg)

There are two important materials present in the sensor one is the pyroelectric crystal which can detect the heat signatures from a living organism (humans/animals)   and the other is a Fresnel lenses which can widen the range of the sensor. Yes the white colour things is just a lense that is used to widen the range of the sensor, if you remove the lense you can find the Pyroelectric sensor inside it covered inside a protective metal casing as shown above.

## 2D Model of The Sensor
![2D Model of The Sensor](https://components101.com/sites/default/files/inline-images/PIR-sensor-dimensions.png)

## Features
- Wide range on input voltage varying from 4.V to 12V (+5V recommended)
- Output voltage is High/Low (3.3V TTL)
- Can distinguish between object movement and human movement
- Cover distance of about 120° and 7 meters
- Low power consumption of 65mA
- Operating temperature from -20° to +80° Celsius
- Automatic infrared detection (LHI778 probe design) Output goes high when objects enter the sensing range, and automatically returns to low when object leaves
- Optional photosensitive control
- Optional temperature compensation
- Trigger mode jumper
- L: Non-repeatable / delay mode: sensor goes low after the delay, regardless of the presence of the object.
- H: Repeatable: sensor stays high as long as any object is detected during the delay time.
- Wide operating voltage range
- Micro-amp power
- Output high signal: easy to achieve docking with the various types of circuit.
- High sensitivity | high reliability

## Specifications

| Plugin | README |
| ------ | ------ |
| Voltage | 4.8 V - 20 V |
| Current | <50 µA |
| Logic output | 3.3 V / 0 V |
| Delay time | 0.3 s – 200 s, custom up to 10 min |
| Lock time	 | 2.5 s (default) |
| Trigger | repeat : L = disable , H = enable |
| Sensing range | <120 °, within 7 m |
| Temperature | – 15 ~ +70 °C |
| Dimension | 32 x 24 mm, screw-screw 28 mm, M2 Lens diameter: 23 mm|


## Arduino Code of The System

```sh
/*  
    Arduino with PIR motion sensor
*/
 
int buzzer = 10;                // the pin that the buzzer is atteched to
int sensor = 2;              // the pin that the sensor is atteched to
int state = LOW;             // by default, no motion detected
int val = 0;                 // variable to store the sensor status (value)

void setup() {
  pinMode(buzzer, OUTPUT);      // initalize buzzer as an output
  pinMode(sensor, INPUT);    // initialize sensor as an input
  Serial.begin(9600);        // initialize serial
}

void loop(){
  val = digitalRead(sensor);   // read sensor value
  if (val == HIGH) {           // check if the sensor is HIGH
    digitalWrite(buzzer, HIGH);   // turn buzzer ON
    delay(100);                // delay 100 milliseconds 
    
    if (state == LOW) {
      Serial.println("Motion detected!"); 
      state = HIGH;       // update variable state to HIGH
    }
  } 
  else {
      digitalWrite(buzzer, LOW); // turn buzzer OFF
      delay(200);             // delay 200 milliseconds 
      
      if (state == HIGH){
        Serial.println("Motion stopped!");
        state = LOW;       // update variable state to LOW
    }
  }
}
```

## İnterface Design By Labview
![Interface design screenshot](https://user-images.githubusercontent.com/98187548/171472534-de70d222-3ed0-44f0-b765-31797fbf9411.png)

## Block Diagram By Labview
![Block Diagram screenshot](https://user-images.githubusercontent.com/98187548/171472125-d222d073-867a-4b8b-9498-3ecb7467a99f.png)

## The Photo of The Circuit
![WhatsApp Image 2022-06-01 at 21 07 15](https://user-images.githubusercontent.com/98187548/171473078-20188934-9998-40e5-9202-684bdcc97304.jpeg)

