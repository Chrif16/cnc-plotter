# CNC plotter
a writing machine that turns vector images that you send it into drawings on a piece of paper, i guess you could consider it an impractical printer.
it uses 2 stepper motors; one controlling the x axis and one controlling the y axis. when the motor spins, the screw spins with it, and when the screw spins, because the sliding part if fixed to a sliding ball bearing it turns the rotation into translation. and combining the two translations together we get a machine that moves according to xy coordinates.
# 3d model
i used the base to mount the components on the sides and left the middle part empty for the paper (also sorry if the assembly uses a lot of screws you can replace them with glue or anything for that matter it doesnt how anything works)
# Wiring diagram
you just have to plug the motors into the motor drivers and the motor drivers into the esp32 and configure the firmware according to your wiring.<img width="1477" height="603" alt="Capture d&#39;écran 2026-11-08 190205" src="https://github.com/user-attachments/assets/d53212f4-ccf9-411e-b6c0-c6cbeb4fa3c2" />
# Firmware
use blablabla's web flasher and change the configuration file to your setup
# BOM
