# IoT Air Pollution Monitor
An Air Pollution Monitor that uses the API, Adafruit IO, in order to store air quality data and other things about the air. This monitor uses CircuitPython to track air quality with the sensor.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Isaac H. | BASIS Independent Silicon Valley | Electrical Engineering | Incoming Sophmore

![Headshot](Isaac1.png)
  
<!-- # Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE -->

# Second Milestone

<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

## Summary
For my second milestone, I got my IoT Air Pollution Monitor connected to Adafruit IO. Thanks to this, I now know that the device is capable of sending data to Adafruit IO. I used a feed called test to try testing if the device could send data to the Adafruit IO website. For some reason, it would randomly disconnect at times, but it clearly works.

## Challenges
At first, the device would not connect to the internet. Turns out, the code from the guide did not work properly. I had to alter it a bit before it would connect to the internet, I had to go find the libraries several times. Some of the code was wrong as it used the wrong pins, so I had to alter that and check the instructions for where all the pins were at. It was only then when I finally got the problem fixed.

## Next Steps
Since I know I can connect the device to Adafruit IO, I will try and complete this project and get all the sensors working.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/CwujE-ylHDU?si=MmB4RtnLt_hvgHlD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary
My main project was an IoT Air Pollution Monitor, it uses several components to track data about the air. The BME280 tracks temperature and humidity, while the PM2.5 AQI sensor tracks the air quality. The Adafruit Feather M4 express processes all this data and sends it to the Adafruit FeatherWing AirLift to send data to the Adafruit IO. And the breadboard adapter allows the PM2.5 AQI sensor to send data to the Feather M4 Express. All these components would not work together without the FeatherWing Doubler, as it connects the Feather M4 Express to the FeatherWing AirLift, and the two Sensors to the Feather M4 Express.

## Progress and Challenges
So far, I've assembled all the parts together and set up a dashboard on the Adafruit IO website when data gets sent there. The only challenged I faced was soldering, as some of the pins were very long, which made the soldering more difficult. When trying to solder the adapter to the FeatherWing Doubler, it had solder in all of it's ports, so I had to try and get all the solder out. I made many mistakes on the FeatherWing Doubler, but I ended up fixing it with the solder wick and solder sucker.

## Plans
Since the assembly is complete, the next step for me will be connecting the Air Pollution Monitor to the internet. 

# Starter Project: Calculator

<iframe width="560" height="315" src="https://www.youtube.com/embed/WKYSBbCFJjI?si=-xpv9teLWwa9nqml" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary
This starter project was a calculator, it contains a battery and uses two four digit digital tube display. All the math is done by the controller and the buttons input numbers into the controller. I chose this because I wanted to learn how calculators work, and because it is an everyday item.

## Challenges
Overall, this starter project did not have many challenges, but because some of the steps were done in the wrong order, the controller socket was misaligned. I had to bend the pins of the controller in order to fit it in because the socket was misaligned.

## What's Next
My next project will be the IoT Air Quality Monitor, it uses a BME280 and PM2.5 Sensor to track air quality and things related to air quality. The device uses a AirLift FeatherWing WiFi Co-Processor to connect to the WiFi and the Adafruit Feather M4 Express to process the data.

<!-- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```-->

# Bill of Materials
<!-- Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Adafruit Feather M4 Express | Microcontroller for the device | $22.95 | <a href="https://www.adafruit.com/product/3857"> Link </a> |
| Adafruit AirLift FeatherWing - ESP32 WiFi CoProcessor | Connects the device to the wifi | $12.95 | <a href="https://www.adafruit.com/product/4264"> Link </a> |
| PM2.5 Air Quality Sensor and Breadboard Adapter Kit | Air quality sensor and a breadboard to connect everything together | $39.95 | <a href="https://www.adafruit.com/product/3686"> Link </a> |
| Adafruit BME280 I2C or SPI Temperature Humidity Pressure Sensor | Temperature and humidity sensor | $14.95 | <a href="https://www.adafruit.com/product/2652"> Link </a> |
| FeatherWing Doubler | Used to add FeatherWing Boards together | $7.50 | <a href="https://www.adafruit.com/product/2890"> Link </a> |
| Silicone Cover Stranded-Core Ribbon Cable - 4 Wires 1 Meter Long - 30 AWG Black | Cables that are used to connect devices together | $1.95 | <a href="https://www.adafruit.com/product/3889"> Link </a> |
| 5V 2A Switching Power Supply w/ USB-A Connector | Used along with the USB-A/Micro Cable to charge the device | Varies | N/A |
| USB A/Micro Cable | Used along with the USB-A/Micro Cable to charge the device | Varies | N/A |

<!-- # Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. -->
