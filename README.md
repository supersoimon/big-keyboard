# Big Keyboard Simon V2!!!!!!!
Big Keyboard is a custom tenkeyless keyboard (87 keys) designed to fit inside a fully-3d printable case. It uses a Raspberry Pi Pico, and connects via a Micro-USB. 

# CAD
The CAD design consists of 3 layers, using dovetail joints to hold the outer, inner, and middle layers together, while also allowing them to be easily taken apart. 

<img width="540" height="320" alt="Screenshot 2026-08-25 212428" src="https://github.com/user-attachments/assets/eeaea3d5-e343-4082-ac58-71e953f67e34" /> <br>
<img width="288" height="156" alt="Screenshot 2026-10-29 202124" src="https://github.com/user-attachments/assets/faa9d536-2409-44a4-a6d9-16f7b8dff47f" /> <br>
<img width="511" height="198" alt="Screenshot 2026-10-29 202100" src="https://github.com/user-attachments/assets/cf6a2a2b-0060-4de6-a13f-03728aeda144" />


# PCB
Big Keyboard's PCB has got a couple of parts to it - a Raspberry Pi Pico (no wireless) and, diodes, and keys (pretty simple). The Diodes and Pi Pico are SMD, while the Cherry MX keys are THT.

<img width="667" height="160" alt="Screenshot 2026-08-26 194612" src="https://github.com/user-attachments/assets/c4ef8cb0-c684-44fe-9fc9-4b8c726a6c9e" />
<img width="584" height="218" alt="Screenshot 2026-08-26 194628" src="https://github.com/user-attachments/assets/72b945d1-6c66-457f-a595-3efc67fefc1c" />
<img width="354" height="301" alt="Screenshot 2026-08-26 194633" src="https://github.com/user-attachments/assets/963b8abc-0635-4d09-9289-8a19d1c0ac88" />

# FIRMWARE/SOFTWARE
Pretty simple firmware, used QMK (had prior experience). Haven't coded the function of the function keys (f1, f2, etc) when not in function mode, haven't decided what I want them to do.

<img width="884" height="435" alt="image" src="https://github.com/user-attachments/assets/9f6efd55-db96-4beb-b6f9-17748f17156f" />

# EXTRA
Originally Big Keyboard was intentended to be a 104-key keyboard, but was pivoted to 87-key after wiring a 104-key didn't work out (matrix wasn't set up properly).
CAD was done in Onshape, PCBs done in KiCAD
