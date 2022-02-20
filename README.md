# GameShift
Enable or disable GameShift feature on Dell laptop. Run the script just like any other software by double clicking on it upon which the script will be executed by Auto Hot Key (AHK) software.

In Dell G15 5515 Ryzen Edition laptop with AMD Ryzen 7 5800H and NVIDIA RTX 3060, pressing F9 switches GameShift mode. The F9 key in this laptop simulates F17 key. When using the laptop with other than default keyboard, for example either with docking station and USB keyboard or remotely, neither pressing F9 key on the laptop nor pressing an F17 key on the remote keyboard (because no standard keyboard comes with F17 key) is not possible. This essentially one line script solves the problem.


Requirement:

GameShift mode: CPU and GPU fans at 100 %. Highest performance.
The feature is provided by Dell Alienware Command Center. If Dell has not provided this feature for your device then this script is useless for the purpose.

Must install: Auto Hot Key (AHK): https://www.autohotkey.com/


Debug:

If this script does not work, then press your usual key on the default keyboard and check with the nice utility from nirsoft to check which key needs to be simulated.
Show pressed key: https://www.nirsoft.net/utils/keyboard_state_view.html
