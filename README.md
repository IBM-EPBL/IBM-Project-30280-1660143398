# IBM-Project-30280-1660143398
Industry-specific intelligent fire management system
1. If the temperature exceeds the maximum of the aforementioned "desired" range, then the LCD displays that the temperature is higher and informs the FAN to turn on.
   Then the FAN starts its rotation/vibration, and after a while the temperature gets lowered falling in the range, then the LCD commands the FAN to turn off.

2. Whenever the sensor's temperature reading goes down below the possible minimum temperature in the range, 
   the LCD notifies that the temperature is LOWER and tells the heater to be turned on, and after the temperature is in the range, it displays that temperature is OK and orders the heater to be switched off.

3. The last condition is whenever the temperature is within the desired range, the LCD tells that the temperature is normal.
   Thus, it asks to turn off everything. This condition can, for instance, be observed if you run the code and the slider's position remains unchanged.
   That tells one that the default slider position is within the desired room temperature range (i.e. the default is 24.78 degree C).
