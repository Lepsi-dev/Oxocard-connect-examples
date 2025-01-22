# Oxocard connect examples
Collection of examples with oxocard connect.

## Connect to GY-521 Gyroscope sensor with breadboard card
[Simple example](https://github.com/Lepsi-dev/Oxocard-connect-examples/tree/main/Gyroskop) how to read the data from GY-521 via i2c protocol and how to handle the angle values

<p align="center">
  <img src="https://github.com/Lepsi-dev/Oxocard-connect-examples/blob/main/Gyroskop/Oxocard-Gyroscope_small.jpg">
</p>

## Connect to AHT20 temperature & humidity sensor with breadboard card
Simple example how to read the data from AHT20 via i2c protocol and show results on screen

<p align="center">
  <img src="https://github.com/Lepsi-dev/Oxocard-connect-examples/blob/main/AHT20%20Temperature%20and%20Humidity/oxocard-aht20_small.jpg">
</p>

## Connect to BMP280 pressure & temperature sensor with breadboard card
Simple example that shows pressure and temperature on the internal screen. When you check the code, you will see that read the raw data is very easy but to calculate and calibrate the values is hard work. I tried out with an algorithm based on operations with float values and with an algorithm that shifts the bit to left and right up to 33 bits what's inpossible with 32bit long datatype in NanoPy. So I created my own shift-bit-operations working with float values. This algorithm get better results in my opinion - you can try both or find the failure in the floating algorith (let me know)

<p align="center">
  <img src="https://github.com/Lepsi-dev/Oxocard-connect-examples/blob/main/BMP280%20Pressure%20and%20Temperature/HowToWireBMP280_small.jpg">
</p>
