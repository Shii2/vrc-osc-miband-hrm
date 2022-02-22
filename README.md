# Mi Band 4/5 OSC heart rate monitor for VRChat
![image](https://i.imgur.com/J6bFJ7u.png)  
By [Vard](https://twitter.com/VardFree)
- Based on Jaapp-'s [miband-5-heart-rate-monitor](https://github.com/Jaapp-/miband-5-heart-rate-monitor)

## What is this?
This app allows you to send OSC messages of your heart rate using Mi Band 4/5 to VRChat.  
Basically it sets the float value of avatar parameter named `Heartrate` to `your heart rate divided by 255`

## Requirements
1. PC on Windows with Bluetooth 4.0 or higher
2. Browser that supports Web Bluetooth API ([Like Chrome](https://google.com/chrome))
3. Xiaomi Mi band 4 or 5

## Usage
1. First and most complicated step is to get auth key for your Mi band. (Visit https://freemyband.com/ for more information)
2. Download [vrc-osc-miband-hrm.zip](https://github.com/vard88508/vrc-osc-miband-hrm/releases), unpack all files and run `vrc-osc-miband-hrm.exe` or if you don't trust me - Download this repository and run it trough node-js
3. Enter your auth key and click Connect
4. Pair your mi band with browser
5. Wait about ~15s and done! Now you sending data about your heart trate to VRChat

## Tips
- Don't forget to turn on OSC in action menu
- RED_SIM's [Simple counter shader](https://patreon.com/posts/62864361) will help you to display your heart rate to VRChat
