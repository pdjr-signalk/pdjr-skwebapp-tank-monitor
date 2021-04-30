# pdjr-skwebapp-tank-monitor

Signal K plugin implementing a webapp that displays current tank levels.

The webapp display is constructed from two components.

* [pdjr-skwidget-tank-monitor](https://github.com/preeve9534/pdjr-skwidget-tank-monitor#readme)
  is used to display current tank levels.
  This component will only render tank path data if the .currentValue
  property is accompanied by .meta.timeout property.
  
* [pdjr-skwidget-alarm-popup](https://github.com/preeve9534/pdjr-skwidget-alarm-popup#readme)
  is used to present an alarm annunciator popup when an alarm
  condition is detected by
  [pdjr-skplugin-alarm-manager](https://github.com/preeve9534/pdjr-skplugin-alarm-manager#readme).

