# loadcell

Connects the following load sensor in given circuit image and for esp 32  

1)connect VCC to 3v3 of ESP32  
2)connect GND to GND of ESP32  
3)connect DT to D4 of ESP32  
4)connect SCK to D2 of ESP32  

![loadcell_circuit](https://user-images.githubusercontent.com/59831591/232223265-1ad66ebe-3be8-4082-bfdd-a4506f218bad.png)



  
 ![calibrate](https://user-images.githubusercontent.com/59831591/232223155-f33f55d7-9811-491d-a7fa-1bdf44aa5048.png)
Follow the directions in the terminal window. It asks you to put a known mass onto the load cells and then enter the weight of that item. This process calibrates your scale.   

I used an phone, which is 113 grams.  

Then it starts outputting the current weight value on the scale.   
