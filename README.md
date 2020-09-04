# ArdunioDigitalAlarmClock
Build a digital alarm clock using an Arduino microcontroller. The clock will have different functionalities implemented in it, like showing the temperature, switching between 12H and 24H modes, setting up the values for current time and alarm time, etc. via the use of buttons.

Button 1: Adjusting the time. When Button 1 is pressed for 3 seconds, it asks for the current time(minute)
Button 2: Pressing button 2 for 3 seconds activates the alarm. If it is pressed again for 3 seconds, it deactivates the alarm.
Button 3: When it is pressed for 3 seconds, it changes the temperature to Fahrenheit. Then when it is pressed for 3 seconds, it changes the temperature back to Celsius.
Button 4: When it is pressed once (1 second) it changes the time mode from 12H to 24H or the reverse.

Scenarios:

Setting The Alarm:
1. Press B2 for 3 seconds to turn alarm ON.
2. Press button 4 for 1 second to snooze it.

Setting the time and alarm time:
1. Press B1 for 3 seconds to adjust minutes.
2. The minute can be changed. Press B2 to increase, press B3 to decrease the minutes.
3. Click B4 for 1 second to change hour.
4. Now the hour can be changed. Press B2 to increase, press B3 to decrease the hour.
5. Click B4 for 1 second to adjust the alarm time.
6. Adjusting the alarm’s minutes.
7. Click B4
8. Adjusting the alarm’s hour.
9. Click B4 to finish adjusting the clock time and alarm time.

Changing the temperature mode:
1. Press B3 to change the mode from Celsius to Fahrenheit.
2. Press B3 again to change the mode back to Celsius.

Changing the time mode:
1. After setting the clock time click B4 for 1 second. It will change it to AM/PM format.
2. Clicking B4 for a second will change the format back to 24 hour format.
