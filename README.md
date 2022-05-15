This repository is archived as its functionality has been integrated into [PLA Multi Checker](https://github.com/capitalism-sudo/pla-multi-checker)

# PLA Distortion Checker

Flask application that displays information about Space-Time Distortions

All important code was created by [capitalism-sudo](https://github.com/capitalism-sudo) (distortion script) and [Lincoln-LM](https://github.com/Lincoln-LM) (PyNXReader, PLA-Live-Map). This is a thin gui on their work.

PyNXReader is a fork of PyNXBot by [wwwwwwzx](https://github.com/wwwwwwzx) so additional credit to them and other who worked on the original project.

## pla-distortion-checker uses [sysbot-base](https://github.com/olliz0r/sys-botbase) to connect to the switch, and this must be installed on your console

Performance may be better (fewer disconnects) if you have [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm) installed.

# How to run:
1. Install requirements ``pip install -r requirements.txt``
2. Copy-paste ``config.json.template`` and rename to ``config.json``
3. Edit the ``IP`` field to contain your switch's IP
4. Run main.py ``python3 ./main.py``
5. Open ``http://localhost:8100/`` in your browser
6. Select the map and options

## Warning
I won't be liable if your Switch get damaged or banned. Use at your own risk.

## Requirements
* [Python](https://www.python.org/downloads/)
* CFW
* Internet Connection
* [sys-botbase](https://github.com/olliz0r/sys-botbase)
* [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm)

## Credits:
* olliz0r for his great [sys-botbase](https://github.com/olliz0r/sys-botbase) which let open sockets on the Nintendo Switch
* spacemeowx2 for his livesafer [sys-module](https://github.com/spacemeowx2/ldn_mitm). It avoids Switch to disconnect from wifi once game is opened

