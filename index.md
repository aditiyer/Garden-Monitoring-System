﻿# Garden Monitoring System
Hi, my name is Aditi and I picked the garden monitoring system as my project. I was interested in this project because it has important real life applications, and on a bigger scale, could majorly help farmers maintain the health of their crops. This project works by using a soil moisture sensor to sense the amount of moisture in the soil, comparing that to the adequate value of moisture, and turning on a red or green LED depending on the result. It also buzzes to remind you to water your plant!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aditi | Fremont High School | Industrial Design | Incoming Junior

<p align ="center">
<a href="https://ibb.co/W5VkLBw"><img src="https://i.ibb.co/c3Y6j2H/unnamed.jpg" alt="unnamed" border="0">
</p>

# My Project
Here is a photo of my finished project. 

<p align="center">
<a href="https://ibb.co/Ptnw4rZ"><img src="https://i.ibb.co/M94MpgD/image.jpg" alt="image" border="0"></a>
</p>

# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
For my second milestone, I added a buzzer. Now, when the soil is dry, the buzzer beeps repeatedly and the red LED glows. When the soil is sufficiently moist, the buzzer plays a short tune and the green LED glows. I learned how to use the tone() command to make the buzzer beep, which takes in 3 inputs : the pin the buzzer is connected to, the frequency of the note in hertz, and the duration in miliseconds. Taking inspiration from the sound a phone makes when you plug it in to charge, I made my own sound for the wet soil, and for the dry soil, played a repeated B flat. Another change I made was the addition of a 9 volt Energizer battery, because I wanted the device to be portable and not rely on a laptop for power. This week, the sensor was being innacurate but worked most of the time despite that. Next week, I'm going to focus on making something to hide all the parts of the device you don't need to see, like the arduino, breadboard, and battery. 

[![Aditi Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1659643684/video_to_markdown/images/youtube--ewLE1gIv9vw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/ewLE1gIv9vw "Aditi Milestone 2")
# First Milestone

My first milestone was to get familiar with the sensor and to make a basic project that detects if there is enough moisture in the soil. There are two types of soil moisture sensors widely used - capacitive sensors and resistive sensors. Capacitive soil moisture sensors work by sensing the dissolved ions in the moisture. Resistive sensors work by measuring the amount of electricity conducted in the soil (dry soil conducts electricity poorly). I used the capacitive soil moisture sensor v1.2 because it is more accurate than its resisitive counterpart. When the sensor is in dry soil, the red LED glows and the message "Time to water your plant" is printed to the serial monitor. When the sensor is in wet soil, the green LED glows and the message "No need to water" is printed to the serial monitor. The biggest challenge I had with this first milestone was my sensor, because it wasn't giving me reliable values which casued a lot of issues. However, it suddenly started working so my overall project began working so that was relieving. 

[![Aditi Iyer Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1659123103/video_to_markdown/images/youtube--0P7yvY682BA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/0P7yvY682BA "Aditi Iyer Milestone 1"){:target="_blank" rel="noopener"}

# Materials
Below are all the materials required to create this project.

| Item | Amount | Price | Buy here |
| ------------- | ------------- | ------------- | ------------- |
| Arduino UNO REV3  | 1  | $24.49  | https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6  |
| Breadboard  | 1  | $8.75  | https://www.amazon.com/BB830-Solderless-Plug-BreadBoard-tie-Points/dp/B0040Z4QN8  |
| Jumper Wires  | 8  | $0.20 each  | https://www.amazon.com/BOJACK-Solderless-Flexible-Breadboard-Connecting/dp/B08YRPWC8L  |
| Capacitive Soil Moisture Sensor v1.2  | 1  | $6.99 for 3  | https://www.amazon.com/DAOKI-Capacitive-Corrosion-Resistant-Electronic/dp/B085XSQXC5 |
| LEDs  | 2 (1 red, 1 green)  | $6.99 for 100  | https://www.amazon.com/eBoot-Pieces-Emitting-Diodes-Assorted/dp/B06XPV4CSH |
| Resistors  | 2  | $6.93 for 100  | https://www.amazon.com/Projects-100EP514100R-100-Resistors-Pack/dp/B00AVSDYFO |
| Piezo Buzzer | 1  | $7.79 for 10  | https://www.amazon.com/a15091400ux0103-Electronic-Mounting-Passive-Sounder/dp/B018I1WBNQ |
| 9 Volt Energizer Battery | 1  | $7.99 for 2  | https://www.amazon.com/Energizer-2513-Alkaline-Battery-522BP/dp/B079NNB63D |