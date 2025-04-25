```cpp

# 🎨 RGB LED Color Mixer using Arduino UNO

This Arduino project controls a common cathode RGB LED to display multiple colors using PWM. The project cycles through various colors like Red, Green, Blue, Raspberry, Cyan, Magenta, Yellow, and White.

## 🛠 Hardware Required
- Arduino UNO
- Common Cathode RGB LED
- Resistors
- Jumper wires
- Breadboard

## ⚡ Circuit Connections

| RGB LED Pin | Arduino Pin | Notes         |
|-------------|-------------|---------------|
| Red         | 11          | PWM Pin       |
| Green       | 10          | PWM Pin       |
| Blue        | 9           | PWM Pin       |
| Cathode     | GND         | Common Ground |

> Make sure the RGB LED is **common cathode**.

## 💻 Code Description

The code uses `analogWrite()` to vary intensity for each color channel. A function `RGB_color()` is created for cleaner, reusable color setting.

## ▶️ Try It on Tinkercad

[🔗 Simulate on Tinkercad](https://www.tinkercad.com/things/your-link-here)

(Replace with your actual Tinkercad share link)

## 📸 Circuit Diagram

![RGB LED Breadboard Setup](circuit_diagram.png)

[🔗 Simulate on Tinkercad](https://www.tinkercad.com/things/3dJAlvhkZQA-dazzling-borwo/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=Tddfcbq-BFWy1ivwieM4JFLHwgVlrlHjAzw7RzKSiGU)
