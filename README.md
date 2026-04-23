# Embedded-traffic-light-simulation_project1
Arduino based traffic light system using LEDs and timing logic to simulate real world traffic flow.
It controls red, yellow, and green LEDs to mimic real world traffic light behavior uding timed sequences.

COMPONENTS USED: Arduino UNO board
                Red, Yellow, AND Green LEDs
                Resistors
                Breadboard
                Jumper wires
                
THE CODE:

int redPin = 3;

int yellowPin = 5;

int greenPin = 6;

void setup() {

  Serial.begin(9600);
  
  pinMode(3, OUTPUT);
  
  pinMode(5, OUTPUT);
  
  pinMode(6, OUTPUT);

}

void loop() {

// Red light

  digitalWrite(3, HIGH);
  
  digitalWrite(5, LOW);
  
  digitalWrite(6, LOW);
  
  delay(2000)
  
// Yellow light

  digitalWrite(3, LOW);
  
  digitalWrite(5, HIGH);
  
  digitalWrite(6, LOW);
  
  delay(2000);
  
// Green light

  digitalWrite(3, LOW);
  
  digitalWrite(5, LOW);
  
  digitalWrite(6, HIGH);
  
  delay(2000);
  
}


WHAT I LEARNED:

1. How to control digital outputs
2. How to impliment timing using delays
3. Basics of circuit design and wiring

FUTURE IMPROVEMENTS

1. Add pedestrian button
2. Add sensors for smart control

CIRCUIT PICTURE
(Coming soon)

DEMO
(Coming soon)
