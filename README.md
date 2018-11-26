# Arduino G29 Shifter

The shifter Internally uses 2 potentiometer and a button for the reverse gear

# Requeriments

* Logitech G29 Shifter
* Arduino Leonardo
* Wire ( i used a lan Cable)
* DB9 male connector

# Shifter Pinout

The logitech uses a female shifter, let's see the pinout

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSu9WPtlZwppyEhPwWwFBGUPpkCjzNeYiPBXw0HjFjio9QPhMz0" title="DB9 female port" />

1&nbsp;2&nbsp;3&nbsp;4&nbsp;5 <br />
.&nbsp;.&nbsp;.&nbsp;.&nbsp;.  <br/>
&nbsp;.&nbsp;.&nbsp;.&nbsp;.<br/>
&nbsp;6&nbsp;7&nbsp;8&nbsp;9<br/>


Pin 2 -> X Axis <br />
Pin 7 -> Y Axis <br />
Pin 4 -> Reverse Button<br />
Pin 3,8 -> Vcc<br />
Pin 9 -> Ground<br />

# Arduino Pinout

After soldering the wires to the male DB9 make the connections to match according to this

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DB9 <br />
A0 -> Pin 2 <br/>
A2 -> Pin 7 <br />
D2 -> Pin 4 <br />
Vcc -> Pin 8<br />
GND -> Pin 9 <br />


# Contributors

based on this project <https://github.com/functionreturnfunction/G27_Pedals_and_Shifter/>


