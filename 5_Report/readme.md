
# **Introduction:**

The temperature measurement system is used to measure and control the temperature.It has been implemented by using Atmega32 in a simulation software named SimulIDE using Embedded C.We can install this system in the vehicles to control the temperature in it. Each subsystem within an Electric Vehicle (EV) requires temperature monitoring. On board charger, DC/DC converter and Inverter/motor control require safe and efficient control to protect the power switch (MOSFET/IGBT/SiC). Battery management systems (BMS) also require fine resolution of temperature measurement on cell level. The one component that must be accurate at extreme temperatures in order to protect the system is no doubt the temperature sensor. Accurate temperature information allows the processor to temperature-compensate the system so that the electronic modules can optimize their performance and maximize their reliability no matter the driving conditions. This includes temperature sensing of power switches, power magnetic components, heat sinks, PCB, etc. Temperature data also helps to run cooling system in a controlled manner. The type of input sensor and signal needed may vary depending on the type of controlled process. Typical input sensors include thermocouples and resistive thermal devices (RTD's), and linear inputs such as mV and mA. Typical standardized thermocouple types include J, K, T, R, S, B and L types among others.


# **Research:**

stly used in vehicles to make sure that the equipments used are working efficiently in cold weather.It takes an analog input and generates a temperature accordingly via master slave communication. Today’s modern vehicles are smart! Automobiles today have the ability to prevent front and rear end collisions; they help drivers accelerate and stop safely on wet and icy road conditions; and they deploy a multitude of air bags to keep one safe in the event of an unforeseen accident. They can also park themselves, detect if you have drifted out of your lane and even warn you if driver fatigue is detected. can go on and on about all the new technology that makes cars so smart, but an often overlooked smart system is the vehicle’s climate control. Most vehicles today can let you set the climate controls to automatic. You set your temperature and the system controls and regulates the airflow to maintain that temperature. But unlike your home that typically uses only a single thermostat to control the temperature, cars have numerous components that it uses to keep drivers comfortable.

# Features
- Low Cost.
- Checks if the driver is seated or not.
- Can modify the temperature according to the passenger.
- Robust System.

## Details requirements
### High Level Requirements:
| ID | Description | 
|----| ------------| 
|HLR1  | When the two switches are closed, the first LED glows indicating the actuation of the system and the heater. | 
|HLR2  | Analog input from the temperature sensor | 
|HLR3  | Display. |		

#### Low Level Requirements:

| ID | Description |
|-------|------|
| LLR1 | ADC with Pulse Width Modulation.| 
| LLR2 | Compatible on different Operating Systems. |

 
# **SWOT Analysis:**

**Strength:**

-Temperature modification can be done easily.
-Cost effective.
-Heat generation is fast.

**Weakness:**
- Need dry bags to store the heater.
- Mostly applicable in countries with low temperature.
- Not water proof.

**Opportunities:**

-By implementing both heater and AC.

**Threats:**
- Can't use in high temperature areas.
- High electrical resistance could cause the heater pad in the seat to overheat.

# **4W and 1H:**

**Why:**
To maintain the heat in the vehicles in cold weather.

**What:**
Temperature measurement system to measure,control and generate heat.

**Where:**
Automotive Industry.

**When:**
In vehicles at low temperature areas.

**How:**
By installing the system in vehicles.

