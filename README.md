# Railway-crossing-safety-system
Engineering Method Assignment
Railway Level Crossing Safety System Design
Course: Introduction to Computer Engineering 
Student ID: U3287309

Part 1: Engineering Method
Step 1 – Exploring the Problem
Restatement in my own words:
The problem is to build a safety system for a train crossing that moves the gates automatically. The gates must close when a train is coming or if a car is on the tracks. The gates should only open when it is completely safe for everyone.
Inputs:
•	Train sensor (shows if a train is coming or going)
•	Car sensor (shows if a car is on the track)
•	Gate sensor (shows if gate is up or down)
•	Manual button (allows manual control if needed)
Outputs:
•	Gate position (up or down)
•	Warning lights (on or off)
•	Alarm sound (on or off)
Constraints:
•	Technical: Sensors must work reliably and not fail
•	Money: Must be affordable for many locations
•	Social: Must keep people and cars safe
•	Weather: Must work in rain, snow, fog, etc.
•	Legal: Must follow all safety regulations
Stakeholders:
•	Train passengers
•	Car drivers
•	Train workers
•	Nearby residents
•	Government officials
Step 2 – Exploring Alternatives
Option 1:
Use two sensors (one for trains, one for cars). The gate lowers when a train is detected. If a car is on the track and a train is near, the gate stays closed until the car leaves.
Option 2:
Use a system where trains have priority. If a train is coming, the gate lowers regardless. Extra loud alarms warn cars stuck on the tracks.
Real-World Example:
Most train crossings use track circuits and sensors. Track circuits detect trains on the track, triggering signals and lowering barriers automatically. Sensors check for cars or objects on the tracks. In Australia, the ARTC (Australian Rail Track Corporation) uses automated crossing gates with flashing lights, alarms, and barriers. These systems prioritize trains, which cannot stop quickly, to ensure safety and prevent accidents with cars.
Steps 3 & 4 – Evaluation and Decision
•	Simple: Uses only two main sensors
•	Safe: Ensures the gate stays closed if a car is on the tracks
•	Reliable: Simple logic reduces false alarms
Steps 5 & 6 – Planning and Implementation
 How it works step by step:
1.	Turn system ON
2.	Check if a train is coming
3.	If YES → Lower gates, turn on lights and alarm
4.	While gates are down:
•	Check if any car is on the track
•	If YES → Keep gates closed
•	If NO and train has passed → Raise gates, turn off lights and alarm
5.	Repeat the process.
Flowchart
 

Things to make it better:
•	Add louder alarms if a car is detected when a train is very close
•	Add a backup battery to work during power outages
