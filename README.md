# Self Watering Strawberry Pot

# Motivation
I love strawberries and I keep having to throw away my strawberries after not finishing them. And I would like to use all those very useful seeds that are just sitting on the outside of each strawberry. Unfortunately, I am always busy being a mom, being a student, being tired. Making taking care of another thing, quite impossible. However, if I have an automated pot I could easily keep my plants alive. Bringing the idea of a self watering strawberry pot to life.

# Features 
* Water pump powered by Relay
* BME280 for temperature, and humidity
* OLED displaying sensor readings

# Work in Progress
*Adding code to publish readings
*Sending reading as notices to phone or email

# Project Details
For one week I designed, printed, coded, and wired a self watering strawberry pot with 3 different levels. The lower level is made for water and holds the pump that will send the water up to the plant. The second level will hold any drainage from the plant getting watered. The top level will hold the plant with the soil sensor and the temperature sensor. The top pot has an inner wall design that will hold all the electronics. Keeping the wires away from soil and moisture. I will be adding a sealant around any edges to help keep the electronic clean. There will be magnets to keep each level relatively attached to each level. As well as access to the inner wall on one side of the pot for electrical access. The inner wiring is left in place with small bread boards that have adhesive on the bottoms. The plastic will be painted over to make a more cohesive pot.

# Code Style
This code is using C++ in Dr. Brian Rashap's format. His style is smooth and easy to read. I like its simplicity and quick use for automation. 

# Preliminary Designs
![design1](https://github.com/user-attachments/assets/d86f9824-75fe-421f-baff-2f91df2b6bd1)
![design4](https://github.com/user-attachments/assets/c8c11871-26a7-44e8-8815-673c8b6a45c3)

# How To Use
To get the pot to water itself a few things have to happen first. Once the device is connected to a power source it will read the soil with the sensor that is inserted into the plant. The OLED will tell you if it needs water. As well as the day and time to include the temperature and humidity. It will check the state of the moisture in the soil and ask for water. After 5 minutes, if the soil is still dry it will pump more water to itself. 
If the soil is moistened enough, the OLED will show refreshed and continue checking the soil moisture every 5 minutes. 

# Work in progress
Currently adding a method to send notifications to let me know the moisture level. And access to view the status of the plant with Adafruit.io
