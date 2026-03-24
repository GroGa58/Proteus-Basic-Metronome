# 555 Timer Based Audio Signal Generator

This project is a simple audio signal generator circuit built using the **NE555 timer IC**. The circuit generates a square wave with an adjustable frequency, which is then amplified by an NPN transistor to drive a speaker and produce sound.

## 🔧 Features

* Astable (oscillator) operation using 555 timer
* Adjustable frequency via potentiometer (RV2)
* Speaker driving with NPN transistor (BC237)
* Simple and low-cost design
* Compatible with Proteus simulation

## ⚙️ Working Principle

* U1 (555 timer) operates in astable mode together with R1, R2, RV2, and C1, continuously generating a square wave signal.
* The output frequency can be adjusted using the RV2 potentiometer.
* The output signal (pin 3) is fed to the base of Q1 (BC237) through RV1.
* The transistor amplifies the signal and drives the speaker, converting the electrical signal into sound.
* C3 acts as a decoupling capacitor to filter noise on the power supply line.

## 🧩 Components Used

* NE555 Timer IC
* BC237 NPN Transistor
* Speaker
* Resistors (e.g., 22kΩ)
* Potentiometers (100kΩ)
* Capacitors (10µF, 0.01µF, 100µF)

## 🎯 Applications

* Simple buzzer/audio tone generator circuits
* Educational electronics projects
* Frequency control experiments

## 📌 Notes

* The frequency range depends on the selected RC values.
* For louder output, an additional amplifier stage can be added.
* A buzzer can be used instead of a speaker.

---

This project is designed to be simple, understandable, and easily extendable for anyone with basic electronics knowledge.
