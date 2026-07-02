# Smart-Jail-Security-System

This project simulates an automated jail/facility security system that demonstrates practical digital electronics and embedded systems concepts. It integrates logic gate ICs for intelligent lighting control, a motorized gate mechanism for access control, and a multi-condition emergency alert system, all coordinated through an Arduino Uno and monitored via a Python-based interface over Bluetooth.

Features
 * Automated gate mechanism — a DC motor controls facility gate access, with response time under 2 seconds from trigger to full open/close.
 * Intelligent lighting system — built using 5 logic gate types (AND, OR, NOT, NAND, NOR ICs) to control zone-based lighting based on combined sensor/input conditions.
* Emergency alert system — LED indicators and buzzers activate across 4+ distinct trigger conditions (e.g., unauthorized access, gate malfunction, zone breach, manual alarm).
 * Bluetooth + Python monitoring — system status and alerts can be viewed and logged through a Python script communicating with the Arduino over Bluetooth.
   
How It Works
 * Digital logic gate ICs combine multiple binary inputs (e.g., sensor states, manual switches) to determine lighting zone activation, demonstrating real-world application of Boolean logic circuits.
 * The DC motor-driven gate opens/closes based on defined access conditions.
Each of the 4+ emergency conditions is wired to trigger a distinct combination of LED and buzzer output, allowing operators to distinguish alert types at a glance.
 * The Bluetooth module streams system state to a companion Python script, which logs and displays real-time status on a connected computer.
