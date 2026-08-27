# Big Keyboard Simon V2!!!!!!!
Big Keyboard is a custom tenkeyless keyboard (87 keys) designed to fit inside a fully-3d printable case. It uses a Raspberry Pi Pico W, and connects via a Micro-USB. 

# CAD
The CAD design consists of 3 layers, using dovetail joints to hold the outer, inner, and middle layers together, while also allowing them to be easily taken apart. 
<img width="540" height="320" alt="Screenshot 2026-08-25 212428" src="https://github.com/user-attachments/assets/eeaea3d5-e343-4082-ac58-71e953f67e34" />
<img width="515" height="221" alt="Screenshot 2026-08-25 212419" src="https://github.com/user-attachments/assets/0c6a632b-8fad-4c66-a13a-b6e12488763b" />
<img width="441" height="221" alt="Screenshot 2026-08-24 192838" src="https://github.com/user-attachments/assets/ec8e123a-6426-44c2-8eb2-a579a268f25a" />

# PCB
Big Keyboard's PCB has got a couple of parts to it - a Raspberry Pi Pico W and, diodes, and keys (pretty simple). The Raspberry Pi Pico and Diodes are surface mounted, while the Cherry MX keys go through the PCB.
<img width="667" height="160" alt="Screenshot 2026-08-26 194612" src="https://github.com/user-attachments/assets/c4ef8cb0-c684-44fe-9fc9-4b8c726a6c9e" />
<img width="584" height="218" alt="Screenshot 2026-08-26 194628" src="https://github.com/user-attachments/assets/72b945d1-6c66-457f-a595-3efc67fefc1c" />
<img width="354" height="301" alt="Screenshot 2026-08-26 194633" src="https://github.com/user-attachments/assets/963b8abc-0635-4d09-9289-8a19d1c0ac88" />

# FIRMWARE/SOFTWARE
Pretty simple firmware, used QMK (had prior experience). Haven't coded the function of the function keys (f1, f2) when not in function mode, haven't decided what I want them to do.
<img width="884" height="435" alt="image" src="https://github.com/user-attachments/assets/9f6efd55-db96-4beb-b6f9-17748f17156f" />

# EXTRA
Originally Big Keyboard was intentended to be a 104-key keyboard, but was pivoted to 87-key after wiring a 104-key didn't work out (matrix wasn't set up properly).
CAD was done in Onshape, PCBs done in KiCAD
