# Smart-Cart-with-Automatic-Billing-and-Anti-theft


 Hardware devices: ESP-32,Weight Sensor,Step-down transformer,RFID reader,RFID tags, HX711,LCD Display, Connecting wires. 
 -> Softwares : Arduino IDE, Windows 11 Operating system.
 -> For the initial stage of our project, we built a circuit which consists of the micro-controller, ESP-32, along with LED, weight sensor,RFID reader and tags.
 -> Later, we represented each RFID tag with a unique product.
 -> We then added the weight of those products in the code.
 -> After that we dumped the code into the microcontroller to test our physical model.
 -> In the last stage we were able to calculate the amount of weight placed on the weight sensor with actual weight of the product. If both the weights match then it redirects to payment through telegram app. If the weight in the cart is more than the scanned weight then it displays theft detected in telegram app as well as on LCD.

-> Working: Our project's working depends on two things:

1.Weight
This model checks the weight of the product scanned by the user with actual weight of the product. If the weight matched with actual weight then it redirects to online payment. If weight in the cart is more than the scanned weight, It displays "THEFT DETECTED" further which the user cannot proceed until its cleared. If the weight in the cart is less then the scanned weight then it displays "SCAN YOUR PRODUCT".
2. Telegram Application 
If the weight of the products (actual and scanned product) matches then the user can pay through telegram application. If theft is detected, it is displayed on telegram application and on LCD display after which the user cannot proceed further.
