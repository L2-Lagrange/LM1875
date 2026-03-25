# LM1875
This repository holds the schematics for my LM1875 bridge tied load bluetooth system design


<img src="Amplifier Prototype Image V001.jpg" width="400">

![Description](Amplifier_Prototype_Image_V001.jpg)





There are a few purposes to this design:

1- Design a portable analog power stage that can be powered by arbitrary random voltage sources. Right now I am using a $20 24V power supply from Amazon. 
Typically I design my own power supplies, but I wanted to design a practical amplifier that works from arbitrary power supplies. 

2- See how usable cheap Amazon bluetooth recievers are when they have an appropriate analog front end. The 35khz 2nd order filter does a great job cleaning it up. It does not sound noisy.

3- Verify that my simple BTL design works properly, which it does








The Bluetooth Reciever: (I could not find an exact datasheet for the chips)
https://www.amazon.com/hiBCTR-Wireless-Bluetooth-Audio-Receiver/dp/B0FDLGMMYC/ref=sr_1_8?crid=3DKBOKZ5XDMWU&dib=eyJ2IjoiMSJ9.Ey14Xp8PL_cvqfbpIiIjYWXxj94B22gQjrskIaN_9OSuE2tGJMzfQthboqY6oWqdde7jTWCNvS-6AUknTg8yUuXWLyL_c_DhKjeonPEYzKRhL-MK9dDgx2vQOOnEjJAUv90je4o2rh_OWNVmx0x8W2F7p0GuOP16jbI43e3XGTrr47DXw8FddJACRp0f509EWAWG0ARj-SYnOMuHhBSyvtDbCzdWQ3-GAMj4ST7qkKs.GRp5Swsv-R3SbGAuJ1w_j-17IZjX5Rpww4GYMX5TGxs&dib_tag=se&keywords=bluetooth+receiver+module&qid=1774471479&sprefix=bluetooth+receiver+modu%2Caps%2C203&sr=8-8
