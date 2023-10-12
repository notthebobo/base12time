# base12time
Base-12 clock in JavaScript

This JavaScript file is intended to demonstrate the advantages of a time system based consistently on a duodecimal or base-twelve system.

The code is demonstrated on the website https://sites.google.com/view/kwkbase12times.

A base-twelve system has twelve unique characters representing the twelve digits, similar to how base ten has ten digits. The clock face uses the two additional Pittman characters for numbers ten and eleven.

The day is divided into twelve units, each equal in length to two common hours. These are tracked by the short white hand which makes a full rotation once ever day. The white hand points up at noon and down at midnight, so the white hand essentially shows where in the sun is in the sky.

Each of those twelve units is divided into twelve smaller units, equating to ten standard minutes. These units are tracked by the larger blue hand which makes a full rotation for every number the white hand counts down, meaning it makes twelve full rotations in a day, or one rotation every two standard hours.

The time is further broken down into three more levels, making a full rotation
- 12 x 12 x 12 times daily, or once every ten minutes (green hand)
- 12 x 12 x 12 x 12 times daily, or once every fifty seconds (red hand)
- 12 x 12 x 12 x 12 x 12 times daily, or once every four and one-third second (orange hand)

Benefits:
This clock allows for a better understanding of time over a full day period
- There is no need for the AM or PM times anymore. Before noon (AM) is when the white hand is on the left and afternoon (PM) is when the white hand is on the right.
- Noon and midnight are not the same as they are on a standard clock; noon has the white hand straight up and midnight has the white hand straight down.
- Time can be read with just two hands to within a minute or two's accuracy by using the smaller marks between the major ticks. The extra hands are there if more precision is required.

Additional application features:

- There are controls for which of the multiple hands are displayed
- A daily update of the time bands shows twilight, morning, afternoon, dusk, and evening times around the face of the clock
- Markers showing key times for waking up and going to bed
