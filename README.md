# Starbie
A tiny motion-controlled digital pet.

I chose this project, a digital "pet," because I am participating in Halflife, a Hackclub program to design and build hardware. For this week's project, they provided a guide for beginners, which was the Starbie project. Since I am a beginner, I decided to make it. I also thought it would be a cool idea to have one of these. At the end of the program, I hopefully will win a 3D printer based on my time spent on projects each week.


These are the schematics:
<img width="512" height="328" alt="image" src="https://github.com/user-attachments/assets/5eae6cbf-72a1-4ec1-a550-bf0bfdfe08fc" />


This is the PCB:
<img width="364" height="331" alt="Screenshot 2026-10-21 180103" src="https://github.com/user-attachments/assets/aa1bf821-ed33-4c8f-ab32-007f89c568c0" />

This is the render: (It doesn't show most of the parts)
<img width="513" height="392" alt="image" src="https://github.com/user-attachments/assets/dca0caac-876a-4414-a3c0-a9743e753c34" />

For the firmware, you will need to get Arduino IDE. You can see the steps in the Firmware Readme. It should look like this once your done.
<img width="1257" height="866" alt="image" src="https://github.com/user-attachments/assets/f846c9b5-c693-4a89-9e34-40a9fdcbbb79" />

This is the BOM for this project. (Prices may vary due to some deals)

| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [XIAO ESP32 C3](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) | wireless connection and sensor integration | 1 | $4.99 | $4.99 | [seeed studio](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) |
| [0.96 inch OLED display module](https://www.amazon.com/dp/B0GBWXTR1Z?th=1) | to display the digital pet | 1 | $4.99 | $4.99 | [DORHEA](https://www.amazon.com/dp/B0GBWXTR1Z?th=1) |
| [DHT11](https://www.aliexpress.us/item/2251832787793025.html) | temperature and humidity sensor | 1 | $1.09 | $1.09 | [ModuleLive Store](https://www.aliexpress.us/item/2251832787793025.html) |
| [10 pack MX Switches](https://www.aliexpress.us/item/3256808168871633.html) | the switches | 1 | $1.09 | $1.09 | [MMD Ainy Store](https://www.aliexpress.us/item/3256808168871633.html) |
| [2 Pcs YMDK Blank DSA 1u Keycap Homing Keys PBT For MX Switches](https://www.aliexpress.us/item/3256808372278605.html) | caps for the MX switches | 1 | $1.09 | $1.09 | [YMDK](https://www.aliexpress.us/item/3256808372278605.html) |
| [MPU-6050](https://www.aliexpress.us/item/3256812142444479.html) | accelerometer and gyroscope | 1 | $1.09 | $1.09 | [DIY Electronics Module 999 Store](https://www.aliexpress.us/item/3256812142444479.html) |
| [California JOS 10K Ohm Carbon Film Single Fixed Resistor](https://www.amazon.com/California-JOS-Carbon-Resistor-Tolerance/dp/B0BR68QQPF/?th=1) | 10kOhm resistor | 1 | $3.99 | $3.99 | [California JOS](https://www.amazon.com/California-JOS-Carbon-Resistor-Tolerance/dp/B0BR68QQPF/?th=1) |
| [PCB](https://jlcpcb.com) | the PCB itself | 1 | $4.00 | $4.00 | [JLCPCB](https://jlcpcb.com) |
| **Parts subtotal** | — | — | — | **$22.33** | — |
| **Tax & shipping** | — | — | — | **$7.19** | — |
| **Total** | — | — | — | **$29.52** | — |
