
## Power Control Timer
Timer to control a switch, powering things like lights or electric blankets etc. Controlled by<br>
start and stop buttons. On time can be increased by repeated presses of the on button.<p>

### Installation
Before installing the blueprint, create helpers similar to the following in Settings → Devices & services → Helpers:<p>
switch.power: The switch controlling the power<br>
input_button.start_button: The button to start & increment the timer and turn on the power switch<br>
input_button.clear_button: The button to stop the timer and turn off the power switch<br>
timer.timer: The timer to control the switch<br>
number.timer_inc: Timer increment step in seconds<br>
number.timer_max_inc: Maximum timer of increments permitted, to limit on time<br>
<p>
<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarshn%2FHome-Assistant-Blueprints%2Fblob%2Fmain%2Fblueprints%2Fpower_control_timer.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>

## Motion Activated Switch
Turn on a switch when presense is detected. Timer controls the on time.<br>
Used to control heating when people are present.<p>

### Installation
Before installing the blueprint, create helpers similar to the following in Settings → Devices & services → Helpers:<p>
binary_sensor.motion_entity: Motion sensor detecting presence<br>
switch.switch: Switch controlling power

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarshn%2FHome-Assistant-Blueprints%2Fblob%2Fmain%2Fblueprints%2Fmotion_switch.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>
