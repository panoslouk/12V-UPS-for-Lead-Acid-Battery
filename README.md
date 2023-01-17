# 12V UPS with low voltage disconnect for lead acid batteries.

![alt text](https://github.com/panoslouk/12V-UPS-for-Lead-Acid-Battery/blob/main/Images/Screenshot_1.png)

The Maxim’s MAX8211 and MAX8212 are CMOS micropower voltage detectors that warn microprocessors (μPs) of power failures. Each contains a comparator, a 1.15V
bandgap reference, and an open-drain n-channel output driver. Two external resistors are used in conjunction with the internal reference to set the trip voltage to the desired level. A hysteresis output is also included, allowing the user to apply positive feedback for noise-free output switching.

The CMOS MAX8211/MAX8212 are plug-in replacements for the bipolar ICL8211/ICL8212 in applications where the maximum supply voltage is less than 16.5V. They offer several performance advantages, including reduced supply current, a more tightly controlled bandgap reference,and more available current from the hysteresis output.

It includes an ESP8266 microcontroller to control 2 relays and INA219 module for monitoring power consumption and battery voltage. Data can be easily sent to your smart home for monitoring and control.

The idea for this PCB came from this site https://www.beyondlogic.org/12v-7ah-sla-low-voltage-disconnect/"
