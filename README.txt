Change History:
01 - Initial check-in, no code yet

Objective:

Implement a digital temperature controller for a mini-fridge that is more precise than the included mechanical controller.  Intended use is for a mini-fridge conversion into a dual-tap kegerator.

Description:

The temp controller will interface to a solid state relay (SSR) to control the compressor motor according to a user-specified setpoint.  The unit will be housed in an enclosure, with display and several buttons for changing the setpoint.

Components
-	Freescale FRDM-KL25Z demo board 
	$12.95 @ http://www.digikey.com/scripts/dksearch/dksus.dll?vendor=0&keywords=FRDM-kl25Z
-	0.84" OLED Display 96×16 Pixel Display
	$19.95 @ https://www.jameco.com/webapp/wcs/stores/servlet/ProductDisplay?storeId=10001&langId=-1&catalogId=10001&pa=2157407&productId=2157407
-	Thermistor for measuring temperature, TBD
- 	Pushbutton switches, TBD
-	Enclosure, TBD
-  	Solid state relay, TBD
-	Power supply, TBD

Basic Requirements:
- Control temperature within +/-5 degrees F of setpoint
- Display current temp 
- Display setpoint temp
- Allow user to change setpoint temp
- Log temp history

Extended Requirements:
- Display temp history
- Warning indication, over and under temps
- Download temp history over USB
- Battery backup for power loss tracking
- Wireless adapter and phone app
- Power monitoring (current and voltage sense)

