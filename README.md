# Control Drone with Keyboard

The `keycontrol.py` in this repository helps to control any mavlink supported drones. After the execution of `keycontrol.py`, try entering any of the following keys:

| Keys    | Description                   |
|---------|-------------------------------|
| t       | Takeoff                       |
| l       | Land                          |
| g       | Guided Mode                   |
| r       | RTL Mode                      |
| &#8592; | Vehicle to the Left           |
| &#8594; | Vehicle to the Right          |
| &#8593; | Moves the Vehicle to Forward  |
| &#8595; | Moves the Vehicle to Backward |

## Requirements
- [python](https://www.python.org/)
- [dronekit-python](https://github.com/dronekit/dronekit-python)
- [sshkeyboard](https://sshkeyboard.readthedocs.io/)
- [pymavlink](https://github.com/ArduPilot/pymavlink)

## USAGE
```
$ python keycontrol.py
```
