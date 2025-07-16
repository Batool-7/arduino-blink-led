# 💡 Project: Blinking the Built-in LED on Arduino Uno

This is my very first Arduino project. It blinks the built-in LED on pin 13 of the Arduino Uno board — a simple and classic "Hello World" for Arduino beginners.

## 🧰 Components Used
- Arduino Uno board ✅
- No external components required

## 📋 Project Description
The Arduino Uno has a built-in LED connected to digital pin 13. In this project, we write a basic sketch to turn the LED on and off every second using `digitalWrite()` and `delay()`.

This is a great starting point to test if your board and programming environment are working correctly.

## 💻 Arduino Code

```cpp
void setup() {
  pinMode(13, OUTPUT); // Set pin 13 as an output
}

void loop() {
  digitalWrite(13, HIGH); // Turn the LED on
  delay(1000);            // Wait for 1 second
  digitalWrite(13, LOW);  // Turn the LED off
  delay(1000);            // Wait for 1 second
}
