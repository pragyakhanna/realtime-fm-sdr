# 📻 Realtime FM SDR

A real-time FM radio receiver built using a Raspberry Pi and an RTL-SDR USB dongle.  
This project lets you listen to FM radio in real time and also extracts RDS (like station names or song info) using C++ and Python.

---

## 🚀 What This Project Does

- 🎧 Plays live FM radio audio through your speakers
- 🧾 Extracts RDS data (station names, song titles, etc.)
- 🧠 Uses custom DSP (Digital Signal Processing) logic — no bloated libraries
- ⚙️ Runs in real time using multithreaded C++ and Python code
- 💡 Built for Raspberry Pi using affordable RTL-SDR hardware

---

## 🧰 Tech Stack

| Part           | Tools & Technologies                         |
|----------------|-----------------------------------------------|
| Hardware       | RTL-SDR USB dongle, Raspberry Pi              |
| Languages      | C++, Python                                   |
| Signal Processing | FM demodulation, Stereo decoding, RDS extraction |
| Runtime        | Multithreading, Real-time buffers             |
| Build Tools    | CMake, g++, Git, Git LFS                      |

---

## 🧠 How It Works!

1. **RTL-SDR** receives raw radio signals from the air  
2. **C++** code decodes the FM signal into clean stereo audio  
3. **Python** handles optional display, processing, or logging  
4. **RDS decoder** pulls out text info like the station ID  
5. Everything is threaded for smooth, real-time performance 🎯

---

