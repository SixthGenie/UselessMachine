# UselessMachine
This is my Useless Machine implementation for an Arduino. What makes this one different from other useless machine
implementation is that is which has a behavior that can be edited and downloaded to EEPROM from a Windows PC. It has one
built-in action only, which only raises the lid, switches off and closes it again. By using the accompanying UselessMachineController
program, you can create/edit and test different actions on the PC before downloading them to the machine itself without having
to reprogram it.

My version also lets you define different anger levels. If it is switched on after it switches itself off within a specified amount
of time, it starts to get aggravated. Too many of these raises the anger level and a different set of actions is performed. Let it
cool down by switching it on less frequent and the anger level drops. Up to 5 anger levels can be defined, and they are set by
the number of levels found when downloading new behavior sequences from the PC.

 The maximum behavior sequences is 255, and is limited to the amount of available EEPROM. A sequence normally takes between 25-50 
 bytes of EEPROM.


