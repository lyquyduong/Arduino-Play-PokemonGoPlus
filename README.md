#  Arduino Play Pokemon Go Plus
Spinning Pokestops and Catching Pokémon without Manually !  
So you can let Arduino clicking Pokemon Go Plus while you are sleeping, or working

**Pokemon Go Plus Enhanced Solution**<br>
Let Pokemon Go Plus become Pokeball Plus, or even batter in catching Pokémon.

## File Description
+ Code_Arduino.zip | Arduino Code
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
<font color=red>This modify could be damage, or lead to unrecoverable damage. Please make sure you have required tools.</font><br>
+ Remove CR2032 battery from Pokemon Go Plus.
<img src="https://github.takahashi65.info/lib_img/github_image_thumb.png" width="800"><br>
+ Using Y00 triwing tripoint screwdriver teardown Pokemon Go Plus.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_teardwon.png" width="800"><br>
+ Desoldering vibration motor.
<img src="https://github.takahashi65.info/lib_img/github_image_thumb.png" width="800"><br>
+ Figure out pinout.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_led_pin.png" width="800"><br>
+ Soldering 30AWG wire wrapping wire, it should stretch seven connect wires.
<img src="https://github.takahashi65.info/lib_img/github_image_thumb.png" width="800"><br>
+ Cutting Pokemon Go Plus case, for setting pin connector.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_case_cut.png" width="800"><br>
+ Connecting Circuit from Pokemon Go Plus to pin connector, then fixed the wire
<img src="https://github.takahashi65.info/lib_img/github_pokemon_pinout.png" width="800"><br>
+ Fixed the pin connector, then put everything back, without vibration motor.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_reassembly.png" width="800"><br>

## Complete PCB, Upload Arduino Code
+ Download Gerber file, Upload to PCB prototype manufacturer, or PCB fabrication manufacturer.
+ Get PCB from PCB fabrication manufacturer, or PCB prototype manufacturer.
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_pcb.png" width="800"><br>
+ Soldering electronic components, including pin header, capacitor, slide switch and micro USB breakout board.
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_assembly.png" width="800"><br>
+ Check Nokia 5110 LCD Board pinout, make sure it can directly connect to board or need wire.
+ Also, if the backlight circuit already has resistors, [ Resistors R9_D9 ] don't need to install, soldering as jumper.
+ Soldering Nokia 5110 LCD Board, or using pin header and pin connector
+ Soldering Arduino, or you can soldering pin header/connector, so you can remove it easily.
<img src="https://github.takahashi65.info/lib_img/github_arduinoplaypokemon_complete.png" width="800"><br>
+ Plug Arduino connector cable, compile and upload program.
+ Making Pokemon Go Plus connect cable, pinout and circuit rule as follows.
<img src="https://github.takahashi65.info/lib_img/github_pokemon_connect_wire.png" width="800"><br>
+ Power on the Board, Connect Pokemon Go Plus.
+ Pray that everything goes well
<img src="https://github.takahashi65.info/lib_img/github_pokemon_running.png" width="800"><br>
+ Now, enjoy  

## Demo Video
+ Actual Operation  
<a  href="https://youtu.be/BAgr38G4zdQ" title="YouTube"><img src="https://github.takahashi65.info/lib_img/github_pokemon_youtube.png" width="800"  alt="github_pokemon_youtube"></a><br>

## Bill of Materials
+ [View Bill of Materials, PDF File](https://github.takahashi65.info/lib_circuit/BOM_Arduino_play_pokemon.pdf)

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