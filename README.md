# Laptop-Battery-Percentage
Shows the laptop battery percentage on the website using JS.

### How to get Laptop Battery Percentage using API :~
- To check the working of API in browser we need to use getBattery method on navigator API
- If the battery API is working then we can check the battery percentage with getBattery() API, this API returns a Promise

### The battery object has the following properties we can use to extract more information about sytem battery :~
  - battery.level : to check the battery level
  - battery.charging : to check if the battery is currently charging or not (true/false)
  - battery.chargingTime : to check the time remaining in full charge of battery
  - battery.dischargingTime : to check the time remaining in battery dead

### To detect changes in all these properties at real time, JS provides some event listeners :~
  - battery.onlevelchange : to detect change in battery level
  - battery.onchargingchange : to detect change in power plug in/out of battery
  - battery.onchargingtimechange : to detect change in battery level
  - battery.onlevelchange : to detect change in battery level
