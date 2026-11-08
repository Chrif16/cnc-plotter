# CNC plotter
a writing machine that turns vector images that you send it into drawings on a piece of paper, i guess you could consider it an impractical printer.
it uses 2 stepper motors; one controlling the x axis and one controlling the y axis. when the motor spins, the screw spins with it, and when the screw spins, because the sliding part if fixed to a sliding ball bearing it turns the rotation into translation. and combining the two translations together we get a machine that moves according to xy coordinates.<img width="1920" height="813" alt="cnc machine" src="https://github.com/user-attachments/assets/1c195289-4e4a-4e72-a6a5-af5214d2c4ac" />

# 3d model
i used the base to mount the components on the sides and left the middle part empty for the paper (also sorry if the assembly uses a lot of screws you can replace them with glue or anything for that matter it doesnt how anything works)
<img width="1007" height="577" alt="Capture d&#39;écran 2026-11-08 194627" src="https://github.com/user-attachments/assets/045b4fcf-5679-4c6d-b878-988acf4fad87" />
<img width="1917" height="1005" alt="Capture d&#39;écran 2026-11-08 194638" src="https://github.com/user-attachments/assets/bf461b52-0232-4ad8-a909-42c417f2ae26" />
<img width="1917" height="1008" alt="Capture d&#39;écran 2026-11-08 194651" src="https://github.com/user-attachments/assets/3fdc080c-2ebc-4c12-99aa-2405e7f84d10" />

# Wiring diagram
you just have to plug the motors into the motor drivers and the motor drivers into the esp32 and configure the firmware according to your wiring.<img width="1477" height="603" alt="Capture d&#39;écran 2026-11-08 190205" src="https://github.com/user-attachments/assets/d53212f4-ccf9-411e-b6c0-c6cbeb4fa3c2" />
# Firmware
use [FluidNC](https://installer.fluidnc.com/fluidnc)'s web flasher and change the configuration file to your setup
# BOM
