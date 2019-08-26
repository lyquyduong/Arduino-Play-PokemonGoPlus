#  Arduino Play Pokemon Go Plus
Spinning Pokestops and Catching Pokémon without Manually !

**Pokemon Go Plus Enhanced Solution**<br>
Let Pokemon Go Plus become Pokeball Plus, or even batter in catching Pokémon.

## Circuit Design /  PCB Simulatiion
Circuit
![ScreenShot](https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_circuit.png)
For Arduino Nano R3
![ScreenShot](https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_pcbf.png)
For Arduino Nano R3, Enhanced
![ScreenShot](https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_enhanced_pcbf.png)
For Arduino Uno R3
![ScreenShot](https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_uno_pcbf.png)

## Modify Pokemon Go Plus
+ <font color="#FF3333">This modify could be damage, or lead to unrecoverable damage. Please make sure you have required tools.</font>
+ Remove CR2032 battery from Pokemon Go Plus.
+ Using Y00 triwing tripoint screwdriver teardown Pokemon Go Plus.
+ Desoldering vibration motor.
+ Figure out pinout.
![ScreenShot](https://github.takahashi65.info/lib_img/github_pokemon_pin.png)
+ Soldering 30AWG wire wrapping wire.
+ Cutting Pokemon Go Plus case, for setting pin connector.
+ Connecting Circuit from Pokemon Go Plus to pin connector.
+ Fixed it, then put everything back, without vibration motor.

## Complete PCB, Upload Arduino Code
+ Download Gerber file, Upload to PCB prototype manufacturer, or PCB fabrication manufacturer.
+ Get PCB from PCB fabrication manufacturer, or PCB prototype manufacturer.
+ Soldering electronic components, including pin header, capacitor, slide switch and micro USB breakout board.
+ Check Nokia 5110 LCD Board, if the backlight circuit has resistors, resistors "R9_D9" don't need to install, short circuit it.
+ Soldering Nokia 5110 LCD Board, or using pin header and pin connector
+ Soldering Arduino, or you can soldering pin header/connector, so you can remove it easily.
+ Plug Arduino connector cable, compile and upload program.
+ Power the board from Micro USB connector, make a smoke testing.
+ Power off, Connect Pokemon Go Plus.
+ Power on,  pray, and enjoy.

## Bill of Materials
+ Pokemon Go Plus
+ Arduino Development Board / Arduino Nano or Uno
+ Nokia 5110 Graphical LCD Board
+ Micro USB Breakout Board
+ Pin connector, 2x4 ( Male Pin, 2.54mm)
+ Pin Connector, 2x4 ( Female Pin, 2.54mm) 
+ Pin Header, 1x3 ( Male Pin, 2.54mm)
+ Pin Header, 1x5 ( Male Pin, 2.54mm) 
+ Pin Header, 1x8 ( Male Pin, 2.54mm)
+ Pin connector, 1x8 ( Female Pin, 2.54mm)
+ 1K Ohm Resistors, 1/8w
+ Slide Switch / SW DIP / SPSTx01
+ 560uF Capacitor / THT Radial D:8.0mm, P:3.50mm
+ 470uF Capacitor / THT Radial D:8.0mm, P:3.50mm

##Required Tools
+ Y00 Triwing Tripoint Screwdriver ( Teardown Pokemon Go Plus )
+ Pin Clamping Pliers
+ Soldering iron
+ Liquid Soldering Flux
+ 30AWG Wire Wrapping Wire ( Silver Plated Wire )

## Resources & Thanks
Arduino Code and Circuit Diagram Compact<br>
[PokeBot – Catch Pokémon’s in your sleep (and at work) ](https://vonkonow.com/wordpress/2017/08/pokebot-catch-pokemons-in-your-sleep-and-at-work/)  **Written by Johan von Konow**