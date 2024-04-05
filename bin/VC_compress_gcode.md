### VC Compress gcode 

VC Compress gcode CLI command line arguments per machine type:

- X-CF Pro
  - `$ VC_compress_gcode_MAC /Users/lashadolidze/Library/Application Support/QIDIPrint/6.4/data.gcode 0.010611 0.010611 0.002490 0.007300 /Users/lashadolidze/Library/Application Support/QIDIPrint/6.4 303 255 304 0`

- X-MAX
  - `$ VC_compress_gcode_MAC /Users/lashadolidze/Library/Application Support/QIDIPrint/6.4/data.gcode 0.010611 0.010611 0.002490 0.007300 /Users/lashadolidze/Library/Application Support/QIDIPrint/6.4 303 255 304 0`
- I-Fast
  - `$ VC_compress_gcode_MAC /Users/lashadolidze/Library/Application Support/QIDIPrint/6.4/data.gcode 0.010611 0.010611 0.002490 0.007300 /Users/lashadolidze/Library/Application Support/QIDIPrint/6.4 303 255 304 0 `



### Useful G-code

```
M104 T0 S200 ; Heat Extruder Up to 200C
M104 T0 S0 ; Heat Down Extruder to 0C
M140 S60 ; Heat bed to 60C
M140 S0 ; Heat down bed to 0C

G1 E-20 F300 I0 T0 ; Filement unload distance = 20mm (E-20) speed = 5mm (5 * 60 = F300) 
G1 E20 F300 I0 T0 ; Filement load distance = 20mm (E-20) speed = 5mm (5 * 60 = F300) 

M8029 D0 ' Fielement runout sensor off
M8029 D1 ' Fielement runout sensor on
```



