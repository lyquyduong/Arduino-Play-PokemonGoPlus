#  Arduino Play Pokemon Go Plus
Spinning Pokestops and Catching Pokémon without Manually !

**Pokemon Go Plus Enhanced Solution**<br>
Let Pokemon Go Plus become Pokeball Plus, or even batter in catching Pokémon.

## File Description
+ Code_Arduino.zip | Arduino Program
+ Gerber_Arduino-Play-PokemonGoPlus.zip | PCB Layout FIle, For Arduino nano
+ Gerber_Arduino-Play-PokemonGoPlus_v2.zip | PCB Layout FIle, For Arduino nano, Enhanced
+ Gerber_Arduino-Play-PokemonGoPlus_Uno.zip | PCB Layout FIle, For Arduino Uno

## Circuit Design /  PCB Simulatiion
+ Circuit
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_circuit.png" width="800"><br>
+ For Arduino Nano Ver 3.0
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_pcbf.png" width="800"><br>
+ For Arduino Nano Ver 3.0, Enhanced
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_enhanced_pcbf.png" width="800"><br>
+ For Arduino Uno R3
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_uno_pcbf.png" width="800"><br>

## Modify Pokemon Go Plus
+ <font color=red>This modify could be damage, or lead to unrecoverable damage. Please make sure you have required tools.</font>
+ Remove CR2032 battery from Pokemon Go Plus.
+ Using Y00 triwing tripoint screwdriver teardown Pokemon Go Plus.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_teardwon.png" width="800"><br>
+ Desoldering vibration motor.
+ Figure out pinout.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_pin.png" width="800"><br>
+ Soldering 30AWG wire wrapping wire.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_pinwire.png" width="800"><br>
+ Pokemon Go Plus should stretch seven connect wires as follows.
+ <font color=red>LED_Red_GND</font>/<font color=blue>LED_Blue_GND</font>/<font color=green>LED_Green_GND</font>/<font color=orange>Switch</font>/<font color=red>Vibration_Vcc</font>/Vibration_GND/GND
+ Cutting Pokemon Go Plus case, for setting pin connector.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_case.png" width="800"><br>
<img src="https://github.takahashi65.info/lib_img/github_pokemon_case_cut.png" width="800"><br>
+ Connecting Circuit from Pokemon Go Plus to pin connector, then fixed the wire
<img src="https://github.takahashi65.info/lib_img/github_pokemon_pinconnect.png" width="800"><br>
+ Fixed the pin connector, then put everything back, without vibration motor.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_done.png" width="800"><br>

## Complete PCB, Upload Arduino Code
+ Download Gerber file, Upload to PCB prototype manufacturer, or PCB fabrication manufacturer.
+ Get PCB from PCB fabrication manufacturer, or PCB prototype manufacturer.
+ Soldering electronic components, including pin header, capacitor, slide switch and micro USB breakout board.
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_asb.png" width="800"><br>
+ Check Nokia 5110 LCD Board pinout, make sure it can directly connect to board or need wire. 
+ Alsom if the backlight circuit already has resistors, [ Resistors R9_D9 ] don't need to install, just short circuit it.
+ Soldering Nokia 5110 LCD Board, or using pin header and pin connector
+ Soldering Arduino, or you can soldering pin header/connector, so you can remove it easily.
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_com.png" width="800"><br>
+ Plug Arduino connector cable, compile and upload program.
+ Power the board from Micro USB connector, make a smoke testing.
+ Making Pokemon Go Plus connect cable, pinout and circuit rule as follows.
+ <font color=red>A3 - LED_Red_GND</font> / <font color=blue>A2 - LED_Blue_GND</font> / <font color=green>A4 - LED_Green_GND</font> / <font color=orange>A1 - Switch</font> / <font color=red>Vcc - Vibration_Vcc</font>
+ <font color=black>A0 - Vibration_GND</font> / <font color=black>GND - GND</font>
+ Power on, Connect Pokemon Go Plus.
+ Pray, and enjoy.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_running.png" width="800"><br>

## Demo Video
<a  href="https://youtu.be/BAgr38G4zdQ" title="YouTube"><img src="https://github.takahashi65.info/lib_img/github_pokemon_youtube.png" width="800" height="450" alt="github_pokemon_youtube"></a><br>

## Bill of Materials
+ Pokemon Go Plus
+ Arduino Development Board / Arduino Nano V3.0, or Arduino Uno R3
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

## Required Tools
+ Y00 Triwing Tripoint Screwdriver ( Teardown Pokemon Go Plus )
+ Pin Clamping Pliers
+ Soldering iron
+ Liquid Soldering Flux
+ 30AWG Wire Wrapping Wire ( Silver Plated Wire ) / or Enamelled Wire
+ 24AWG Stranded Conductors Wire
+ Super Glue

## Resources & Thanks
Arduino Code and Circuit Diagram Compact<br>
[PokeBot – Catch Pokémon’s in your sleep (and at work) ](https://vonkonow.com/wordpress/2017/08/pokebot-catch-pokemons-in-your-sleep-and-at-work/)  **Written by Johan von Konow**