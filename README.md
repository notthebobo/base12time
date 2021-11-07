# base12time
Base-12 clock in Javascript

This Javascript file is intended to demonstrate the advantages of a time sysetm based  consistently on a duodecimal or base-twelve system.

The code is demonstratedon the website https://sites.google.com/view/kwkbase12times.

A base twelve system has twelve unique characters reporesenting the twelve digits, similar to how base ten has ten digits. The clock face uses the two additional Pittman characters for numbers ten and eleven.

The day is divided into twelve units, each equal in lengtto two common hours. These are shown by the short white hand which makes a full rotation once ever day. The white hand points up at noon and down at midnight, so the white hand essentially shows where in the sun is in the sky.

Each of those twelve units is divided into twelve smaller units, equating to ten standard minutes. These units are shown by the larger blue hand and make a full rotation for every number the white hand counts down.

The time is further broken down into three more levels, making a rotation
- every ten minutes (green hand)
- every fifty seconds (red hand)
- every four and a third second (orange hand)

Benefits:
This clock allows for better understanding of the full day period
- There is no AM or PM required when telling the time: any time where the white hand is on the left is AM and any time when the white hand is on the right is PM.
- Noon and midnioght are not the same as they are on a standard clock; noon has the white hand straight up and midnight has the white hand straight down.
- Time can be read with jsut two hands to within a minute or two's accuracy by using the smaller marks between the major ticks. The extra hands are there if more precision is required.

Key app features:

- Control on which of the multiple hands is displayed
- A daily update of the tmie bands showing twilight, morning, afternoon, dusk, and eveningtimes aruond the face of the clock
- Markers shownig key times for waking up and going to bed
