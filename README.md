🚦 Traffic Light Simulator

A simple and interactive traffic light simulation built with HTML, CSS and JavaScript.
Each time the function runs, the signal switches between Red → Yellow → Green, just like a real traffic light. This project is great for practicing DOM manipulation and basic logic in JavaScript.

⭐ Features

1. Lights switch one at a time
2. Smooth cycle between all three signals
3. Easy-to-understand JavaScript logic
4. Beginner-friendly project structure

📌 How It Works
The project uses a variable (lightIndex) to track which light should be active.
0 = Red
1 = Yellow
2 = Green

Every time changeLight() is called:
1. It updates the background color of the correct light.
2. It resets the other two lights to “off”.
3. It moves to the next light using
 lightIndex = (lightIndex + 1) % 3;

This creates an infinite loop of traffic light changes.

🛠️ Technologies Used
1. HTML for layout
2. CSS for styling the lights
3. JavaScript for behavior and logic
