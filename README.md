# Discrete-7-segment-driver
7-segment display driver with a discrete diode ROM

The matrix of diodes is hardwired memory.
Each row is one word/byte with the 
length of 7 bits. The circuit 'stores' data
for displaying a number on a 7 segment LED display
(hence 7 bit word)
I made the memory and the display from
discrete diodes and the only chips are for
changing the address. Counting up at 1Hz frequency.
It would also work by putting logic HIGH on anode
of one of the leftmost diodes and get your output
on the bottom. That's where the display is wired.

It's an educational board with a bit of computer
history. This is what the pioneers of computing
used for microcode. Storing vital data, such as
the instruction set and boot sequence.

You can read some more about it on my blog
https://unregulatedpowersupply.wordpress.com/
