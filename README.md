C_HW6
=====

event

1. In event.h, the following function prototypes are added (you can download the new event.h file).  You do not need to modify this file.

•	int CurrentEventNumber(); /* gets the current event number. This simply returns the value of the file-global variable  */

•	void MoveEvent(int m, int n); /* moves event #m to event #n. Both m and n must be within the range of 0 to MAXEVENTS-1.  Event #m must be nonempty string, and event #n must be empty string. */

•	void SwapEvents(int m, int n); /* swap event strings for #m and #n, regardless of whether they are empty.  Copy one to a temporary string buffer, overwrite the saved one with the other event string, and overwrite the second event string buffer with the saved temporary. */

•	void FindEvent(char *evt); /* list events whose descriptions contain evt as a substring. You may use the strstr() function from string.h library for the match. */

•	The new #define for the new commands, including "move", "moveto", "movefrom", "swap", and "find". (CMD_MOVE, CMD_MOVETO, CMD_MOVEFROM, CMD_SWAP, CMD_FIND)


