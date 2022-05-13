
## WIPER CONTROL SYSTEM


| TEST ID  | OBJECTIVE      | INPUT DATA  | EXPECTED OUTPUT | ACTUAL OUTPUT | STATUS |
| -------  | ---------      | ----------- | --------------- | ------------- | ------ |
| TP1      | Turn on ignition| Turn on the compailer| LED blink | LED blink | PASS |
| TP2      | Turn on wiper system| press blue pushbutton in QEMU| show button pressed in console | show button pressed in console | PASS |
| TP3      |                 |   | Blink three LED's with specific duration | Blink three LED's with specific duration | FAIL |
| TP4      | Change speed of LED(wipers)| short press blue pushbutton| Change speed of LED's| Change speed of LED's| FAIL |
| TP5      |                 | Without pushbutton| Change speed of LED's| Change speed of LED's| PASS |
