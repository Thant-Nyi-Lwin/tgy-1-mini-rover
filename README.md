# tgy-1-mini-rover
TGY-1 (Taunggyi-1) is a fully 3D-printed mini rover featuring a 3-DOF robotic arm and ESP32-based web control.

## Overview
The TGY-1 rover is designed as a small robotic rover capable of mobility and simple object manipulation. It is intended as a **beginner-friendly rover** for learning how a rocker-bogie suspension system and a robotic arm function. Although it is not perfect, it is fully functional.

All major structural components are designed in **OnShape** and can be fully 3D printed on a **Bambu Lab P1S** 3D printer using PLA filament, allowing the design to be easily modified, reproduced, and improved. 

## Background
Taunggyi is a city located on the Shan mountain range in eastern Myanmar, and it is also my hometown. 

The project began during Reading Week of Winter 2026 when I found myself struggling with insomnia. For several nights, I worked on the CAD design from around 3 a.m. until sunrise. While working on the rover, I listened to old Burmese songs that I used to hear growing up, which made me feel homesick. Because of that, I decided to name the rover after my hometown.

Since the name _Taunggyi_ literally translates to "Big Mountain", I thought it would be an ironic yet fitting name for this mini rover. 

## Features
- Fully 3D-printed chassis and arm
- Beginner-friendly rocker-bogie suspension
- 3-DOF robotic arm for simple manipulation
- ESP32 Wi-Fi control
- Browser-based web interface
- Modular and easy-to-modify design

## Hardware
| Component | Qty | Description |
|:----------:|:----------:|:----------|
| [Esp32](https://www.amazon.ca/ESP-WROOM-32-NodeMCU-Bluetooth-Development-Microcontroller/dp/B0CHBMFJBQ/ref=asc_df_B0CHBMFJBQ?mcid=56f0e01e9a3a3b33a2be90f7f3545453&tag=googleshopc0c-20&linkCode=df0&hvadid=706724917350&hvpos=&hvnetw=g&hvrand=1725666767088898801&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9197976&hvtargid=pla-2296980982282&hvocijid=1725666767088898801-B0CHBMFJBQ-&hvexpln=0&gad_source=1&th=1)   | 1 | Microcontroller for the rover control |
| [SG90 Servo](https://www.canadarobotix.com/products/1713?srsltid=AfmBOorv0HvVQ5HlR4PF1jHSk7Agmu67IOxEqFserwWhusFoXC2SeWKv)  | 1 | Servo used for the robotic gripper |
| [MG996r Servo](https://www.canadarobotix.com/products/3054)  | 3 | Servos for 3 DOF arm |
| [Yellow DC Motor](https://www.aliexpress.com/p/tesla-landing/index.html?scenario=c_ppc_item_bridge&productId=1005009115999594&_immersiveMode=true&withMainCard=true&src=google&aff_platform=true&isdl=yhttps://www.aliexpress.com/p/tesla-landing/index.html?scenario=c_ppc_item_bridge&productId=1005009115999594&_immersiveMode=true&withMainCard=true&src=google&aff_platform=true&isdl=y&src=google&albch=shopping&acnt=631-313-3945&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&&albagn=888888&&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005009115999594&ds_e_product_merchant_id=5695572279&ds_e_product_country=CA&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=19366866438&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=17337458112&gbraid=0AAAAACbpRIn_6pzJT3tHM2r3fpDU2_GvM&gclid=Cj0KCQjwsdnNBhC4ARIsAA_3hei0Dd3-C01D6Ly3NOqQB_-HnonVBkMyvLFdTmz5FaZrGxDZDc7fbJYaAr7kEALw_wcB)  | 6 | Used for rover mobility |
| [L298N Motor Driver](https://www.amazon.ca/H-Bridge-Controller-Stepper-Control-Stepping/dp/B07PNL3JQ3/ref=asc_df_B07PNL3JQ3?mcid=38938a0451a9304da1b0f839e339f59a&tag=googleshopc0c-20&linkCode=df0&hvadid=706827341039&hvpos=&hvnetw=g&hvrand=8792856488059416463&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9197976&hvtargid=pla-2376431793528&psc=1&hvocijid=8792856488059416463-B07PNL3JQ3-&hvexpln=0&gad_source=1)  | 1 | Motor driver module for controlling rover wheels |
| [LiPo Battery](https://www.harbormodels.com/dtxc1864.html?srsltid=AfmBOopRTBGlH-ueqhaTnk2plIBSDmMFhWOAvG3XnHK4yWKBqWgGN2ZM)  | 1 | Battery pack that powers the whole rover |






