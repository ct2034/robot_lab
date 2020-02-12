# Robot Instructions

## Boot
- Turn power switch on the safety cabinet on
- Release the emergency stop button (if pressed)
- Wait until gatebox buttons light up
- Press Reset
- Press Braketest Snooze (Blue button) to get 20min of free robot movement
- Press the acknowledge button, STO light on the manipulator should turn green
- Bring your CAN up (if not configured to do automatically https://github.com/PilzDE/pilz_robots#running-on-the-real-robot)
- Make sure your PC can talk to the PSS via modbus (i.e. try to ping 192.168.0.10)
- Run your roslaunch

## Switch operation mode
- Press respective button on the PitMode (with token inserted)
- Press RESET on the GateBox
