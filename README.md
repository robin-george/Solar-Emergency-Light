# Solar-Powered Emergency Light  

This project is a **solar-powered emergency light** that supports both **solar charging** and **USB adapter-based charging**. Initially, a **mobile phone battery** was used for power storage, but it was later **upgraded to two 3400mAh 18650 Li-Ion batteries** for increased capacity. The system also functions as a **power bank**, allowing users to charge USB devices like smartphones and tablets.  

## Features  
- **Dual Charging Mode**:  
- **Solar Charging** using a **solar panel**.  
- **USB Adapter Charging** through a **TP4056 charge controller** and **boost converter**.  
- **Energy Efficient**: Uses **3-Watt LEDs** for bright and reliable lighting.  
- **Battery Upgrade**: Initially used a **mobile phone battery**, now replaced with **two 3400mAh 18650 Li-Ion batteries** for extended runtime.  
- **Power Bank Functionality**: Can charge USB devices such as **smartphones and tablets**.  
- **Automatic Power Switching**: The system automatically switches between power sources.  
- **Overcharge & Discharge Protection**: TP4056 ensures **safe battery charging**.  
- **Charging Status Indication**:  
  - **Red LED** glows when the battery is charging.  
  - **Green LED** glows when the battery is fully charged.  

## Components Used  
- **Solar Panel** (for renewable charging)  
- **TP4056 Charge Controller** (for battery management)  
- **Boost Converter (5V USB Output)** (for regulated power supply)  
- **3W LEDs** (as the primary light source)  
- **Two 3400mAh 18650 Li-Ion Batteries** (for power storage)  
- **USB Adapter** (for alternate charging)  
- **Charging Status LEDs** (Red for charging, Green for full charge)  

## How It Works  
1. **Solar Charging Mode**: The solar panel generates power and charges the battery via the **TP4056 module**.  
2. **USB Adapter Charging**: The TP4056 also supports USB charging via a **5V adapter**, ensuring continuous power availability.  
3. **Boost Converter**: Converts the battery's voltage to **a stable 5V output** for powering the LEDs efficiently.  
4. **Automatic Switching**: The system intelligently switches between **solar and adapter charging** based on availability.  
5. **LED Illumination**: The stored power drives **3W LEDs** for emergency lighting.  
6. **Power Bank Mode**: The system can charge **USB devices like smartphones and tablets** via the **5V USB output**.  
7. **Charging Status Indication**:  
   - **Red LED** glows when the battery is charging.  
   - **Green LED** glows when the battery is fully charged.  

## Applications  
- **Emergency Lighting** during power failures.  
- **Sustainable Solar-Based Lighting** for remote areas.  
- **Portable Lighting Solution** for outdoor and camping use.  
- **Power Bank** for charging **smartphones and tablets** on the go.

## License  
This project is licensed under the **MIT License**. 
