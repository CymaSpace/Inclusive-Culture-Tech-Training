# Workshop 2: Building LED Tubes

**Objective**: By the end of this session, you will understand how to construct an LED tube, connecting it to the ESP32 microcontroller, and controlling it using the WLED program.

## Materials:

[Bill of Materials Google Spreadsheet
[CymaTube 12v LED Kit Bill of Materials](https://docs.google.com/spreadsheets/d/13lXfaKDpZpO9bKg4p8Jv9w2FjBJL2ZVyVSb-0JvHfJc/edit?usp=sharing)  

### 5V CymaTubes
For a budget-conconsious build, we can use 5V LEDs but you won't be able to power many tubes in series:
1. **[Muzata 6-Pack 3.3ft/1Meter 17x20mm U Shape Spotless Black LED Aluminum Channel System](https://www.amazon.com/Muzata-Aluminum-Channel-System-Diffuser/dp/B08B3TPN9D)**: These are the Aluminum LED Channels with Covers. We will need 8 of these for our project.
2. **USB-C PD Trigger Board Module**: This is a USB C Converter to 12V. We will need 20 of these for our project.
3. **ESP32 WLED pico board**: This is a Sound Reactive LED Board. We will need 18 of these for our project.
4. **[Power Supply (38800mAh Huge Capacity)](https://www.amazon.com/dp/B0BPST8KKZ?psc=1&smid=A6LW2T8RHHN52&ref_=chk_typ_imgToDp)**: A power supply for our project. We will need 20 of these for our project.
5. **[LED Lights (WS2812B Led Lights DC5V WS2812 RGB Led Strip Light Individually Addressable Smart Pixels Magic Light Black White PCB IP30 65 67)](https://www.aliexpress.us/item/2251801850504415.html?spm=a2g0o.order_detail.order_detail_item.2.5303f19c6AHCmr&gatewayAdapt=glo2usa)**: These are the LED lights for our project. We will need 80 of these for our project.
6. **[Additional Component 1](https://www.amazon.com/gp/product/B07T8FL51T/ref=ox_sc_act_title_2?smid=A1OHX1ZYWFEJ99&psc=1)**: We will need 20 of these for our project.
7. **[Additional Component 2](https://www.amazon.com/gp/product/B01DC0KIT2/ref=ox_sc_act_title_1?smid=A35UAT07QG3EC6&psc=1)**: We will need 1 of this for our project.


### 12V CymaTubes
If you want to do longer runs, with more LEDs, recommend building a 12V setup:

1. **[Muzata 6-Pack 3.3ft/1Meter 17x20mm U Shape Spotless Black LED Aluminum Channel System](https://www.amazon.com/Muzata-Aluminum-Channel-System-Diffuser/dp/B08B3TPN9D)**: These are the Aluminum LED Channels with Covers. We will need 4 of these for our project.
2. **USB-C PD Trigger Board Module**: This is a USB C Converter to 12V. We will need one of these for our project.
3. **ESP32 WLED pico board**: This is a Sound Reactive LED Board. We will need one of these for our project.
4. **[BTF-LIGHTING 3 Pin Electrical Connector](https://www.amazon.com/BTF-LIGHTING-Electrical-Connector-Waterproof/dp/B07DPN9MMZ)**: These are Waterproof locking connectors. We will need 4 of these for our project.
5. **[200W USB C Charger, 8-Port Desktop Charging Station](https://www.amazon.com/Charger-Desktop-Charging-Compatible-MacBook/dp/B09J2KHQKY)**: This is a USB C Power Brick to Power LEDs. We will need one of these for our project.
6. **[Deegotech USB C to USB C Cable 10ft,100W Fast Charging Cable](https://www.amazon.com/Deegotech-Charging-Compatible-MacBook-Sumsung/dp/B07XXYMM1H)**: This is a Long USB C Cable for Power Delivery. We will need one of these for our project.

7. **GE60RGB2812BA (DC5V,IP20 Non-waterproof, 60px/m, RGB, customs length 20m/Reel,don't need any connector) The unit price**: These are 12V LED Strips, Commercial Grade Quality from Greeled. We will need 4 of these for our project.
8. **[10 Pieces 5v Regulator Module Mini Voltage Reducer](https://www.amazon.com/Regulator-Module-Voltage-Reducer-Transformer/dp/B085TGYJQF)**: This is a 12v -> 5v converter to prevent 12v going to the ESP32 WLED pico. We will need one of these for our project.

## Agenda

### Introduction (15 minutes)
- Welcome back and brief recap of the previous workshop
- Overview of today's workshop: Building and controlling LED tubes

### Safety Briefing (10 minutes)
- Usage and safety of necessary tools
- Distribution of safety goggles

### LED Tubes Basics (20 minutes)
- Understanding LED tubes
- Electrical principles behind the LED tube

### Hands-On Activity: Building LED Tubes (60 minutes)
- Step-by-step guide on building an LED tube
- Mentors assistance during the activity

### Programming the LED Tubes (30 minutes)
- Programming the ESP32 to control the LED tube
- Creating simple patterns and sequences on the LED tube

### Wrap Up and Questions (15 minutes)
- Recap of what we learned
- Open floor for questions and discussions
- Preview of next workshop: "Introduction to Mapping via Geopix"

