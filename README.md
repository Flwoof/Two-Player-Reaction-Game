# Two-Player-Reaction-Game
### This is a simple game that is intended to help train reflexes. The game contains ten rounds and must be played with two players. Once a player earns ten points they have won the game!
_Files from here_ <br/>
  - Coding file titled "Two Player Game Code" <br/>

_Libraries you Need_ <br/>
  - Adafruit SSD1306 by Adafruit (install from Arduino IDE library manager) <br/>
  - Adafruit GFX by Adafruit (install from Arduino IDE library manager) <br/>
  - <Wire.h> (is included in Arduino IDE already) <br/>

_Hardware Needed_ <br/>
  - Arduino Mega <br/>
  - One green, red, yellow, and blue LED, four white LEDS <br/>
  - Ten pushbuttons, 2 caps of each color (blue, green, yellow, red, black) <br/>
  - One 2.2in OLED screen <br/>
  - 1 Passive Buzzer <br/>

## **If you've never installed a library before:**
1. Open Arduino IDE
2. Click "Sketch" (top left of screen)
3. Click "Include Library"
4. Select "Library Manager"
5. Type name of desired library in search bar, **make sure the author name is the same**

**How to Play the Game** <br/>
When you plug the arduino in your OLED will need a minute to load. After a few seconds you should see "P1, P2" written on the OLED screen. <br/>
To start the game, each player needs to hold down on their respective black pushbutton. This should make the word "Ready!" appear next to the respective players name. <br/>
Once both players are holding down their button, a countdown from 3 will begin. Once the screen says START, the round has begun. If you let go <br/>
before a light has turned on after this point your opponent will gain a point! To win the round, wait until one of the four colored LEDS turns on and press the <br/>
corresponding button color before your opponent! An LED can turn on after just 1 or up to 10 seconds, so you'll have to remain alert. <br/>
First player to reach ten points is the winner! <br/>

### _Game Features_ <br/>
- Ten randomized rounds to determine winner of game (random light random time intervals)
- Game resets after a winner is declared <br/>
- Four working LEDS, 10 working pushbuttons <br/>
- Game can tell the difference between an incorrect/correct press/attempt to press early <br/>
- OLED scoreboard displays score and communicates all game events <br/>
- Single round won sequence with lights + sound <br/>
- Victory sequence with lights + sound <br/>
- Press too early animation/sounds <br/>

## Known Issues <br/>
On rare occasion the readying buttons (black buttons) will think you let go if you reduce the amount of pressure you're putting on them. <br/>
To prevent getting a false penalty, press down firmly and keep the amount of pressure you are putting on the button the same while waiting for the round to start. <br/>
  
  
  
