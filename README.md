# Solar-Powered Smart Alarm Speaker with DeepSeek AI

![Project Banner](https://via.placeholder.com/800x400?text=Smart+Alarm+Speaker+with+DeepSeek+AI) *(Replace with actual project image)*

A solar-powered smart speaker featuring voice interaction, programmable alarms, and DeepSeek AI integration. Designed for energy-efficient operation with WiFi connectivity.

## ✨ Features
- 🎙️ **Voice Control**: Wake word detection & natural language queries
- ⏰ **Smart Alarms**: Customizable alarms with AI-generated wake-up messages
- ☀️ **Solar Powered**: 10W panel + battery backup (24h+ operation)
- 🤖 **DeepSeek AI**: Intelligent responses via API integration
- 📶 **WiFi/Offline Modes**: Works without internet (basic functions)

## 📦 Hardware Components
| Component               | Quantity | Notes                          |
|-------------------------|----------|--------------------------------|
| Raspberry Pi 4/5        | 1        | Main processor                 |
| 10W Solar Panel         | 1        | With charge controller         |
| 3.7V LiPo Battery       | 1        | 2000mAh+ capacity              |
| PAM8403 Audio Amplifier | 1        | 3W-5W speaker output           |
| INMP441 Microphone      | 1        | I2S interface for clean audio  |
| DS3231 RTC              | 1        | Accurate timekeeping           |

## 🛠️ Setup Instructions

### 1. Hardware Assembly
```bash
# Wiring diagram available in /docs/wiring.png
Solar Panel → TP4056 → Battery → 5V Regulator → Raspberry Pi
Microphone → I2S pins | Amplifier → GPIO/PWM → Speaker
