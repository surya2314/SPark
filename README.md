# S-PARK SYSTEMS

## Smart-Parking Systems Using ESP32 DEV V1

### Authors
Jai Surya S, Anurag Senapati, Shreyas Balihallimath,

## Condensed Abstract

SPARK SYSTEMS, also known as Smart-Parking Systems, is an advanced automated parking solution. Its core function involves real-time detection of parking slot availability, followed by user notifications regarding occupied, pre-booked, and open parking spaces.

## Objectives

Developing an efficient parking management system with the capability to sense parking space availability holds significant promise. Incorporating a reservation system within parking areas can notably alleviate the inconvenience of securing a parking slot. The pursuit of automating the current parking framework underscores the objective of reducing human intervention. A pivotal benefit of this innovation is the mitigation of traffic congestion stemming from vehicles circling parking lanes in search of available spaces.

## Methodology

The S-Park system employs a dual-device framework comprising the **Detection Module** and the **Control System**.

- **Detection Module**: This module consists of an IR (Infrared Radiation) Sensor, an ESP 01 chip, and a battery, collectively tasked with sensing vehicle presence. The IR sensor detects vehicles through infrared radiation, and this data is transmitted wirelessly to the ESP32 Microcontroller via the ESP 01 Module, using WiFi Technology.

- **Control System**: This system integrates essential components such as the ESP32 Microcontroller and an LCD display. It processes information sourced from the ESP 01 module, thereby relaying parking space availability to the LCD Display. This system orchestrates the collaboration among the Detection Modules and manages data transmission and reception, culminating in the accurate representation of ongoing actions on the display.

This modular configuration facilitates the seamless production of multiple Detection Modules, creating a comprehensive network that furnishes the Control System with an exhaustive array of spatial data.

## Constraints

- Requires a constant power supply.
- Obstacles blocking the sensors would register the parking slot as occupied.
- Cars with high ground clearance are not easily detected.

## Implications

Through progressive development efforts, this system can establish an interconnected array of these systems, thereby furnishing a holistic framework encompassing citywide parking information and conditions.

## Recommendations

An app can be developed using which the users can book their slots for a particular amount of time. This will lead to the effective monetization of the existing parking systems.

## Conclusion

In summary, SPARK SYSTEMS, also known as Smart-Parking Systems, represents a significant advancement in automated parking solutions.

## Acknowledgement

Dr. Sudhanya P, Asst. Professor, SRM IST Kattankulathur

## Contact Information

- **Department**: ECE Dept.
- **Institution**: SRM Institute of Science and Technology, Kattankulathur Campus, Chengalpattu Dt., Tamil Nadu - 603 203
- **Phone**: +91 9380545169, +91 6360168050, +91 7842162089
