Railway Crossing Safety System - Algorithm (Plain English)

1. System starts (ON).
2. Continuously monitor sensors.
3. IF train is approaching:
       - Lower gates.
       - Turn ON warning lights and alarm.
4. WHILE gates are down:
       - Check if a vehicle is on the track.
       - IF a vehicle is detected:
            - Keep gates CLOSED.
       - ELSE IF no vehicle is detected AND train has passed:
            - Raise gates.
            - Turn OFF warning lights and alarm.
5. Loop back to step 2 and repeat continuously.

This logic ensures that gates remain closed whenever a train is near or a vehicle is stuck on the tracks, and only reopen when it is completely safe.
