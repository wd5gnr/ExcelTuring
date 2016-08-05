# ExcelTuring
Turing Machine Simulation in Excel Spreadhseet

Excel Turing Machine -- Williams 

Row 1 has the current state of the machine and buttons:

* Execute - Start executution in current state and tape position
* Step - Do one head movement and stop
* Reset - Reset state/position (see row 2)
* Reset Tape - Clear tape to blank

You can initialize the tape (row 4) as you see fit

The table starts in row 7. Columns:

* Current state to match (can be $ANY)
* Current character to match (can be $ANY)
* Next character to put on tape (can be $NOCHANGE)
* Direction to move tape (can be L, R, or anything else for no movement; can also use words that start with L or R and not case sensitive)
* Next state (can be $HALT or $BREAK or $NOCHANGE; not recommended but can be  $ERROR)

Machine stops on $HALT state or $ERROR state or $BREAK state. $ERROR state occurs if tape is overrun or no rule matches
