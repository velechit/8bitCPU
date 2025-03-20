Clock module schematic is ready for reviews and feedbacks. improvements in clock module: 
1. Astable clock is 50% duty cycle 
2. when clock source changes inbetween a high pulse, clock glitches. this has been eliminated by synchronising the clock source selection to the clocks using additional NE555
3. Halt signal keeps the Astable NE555 reset unlike gated at output in Ben Eater's design, Maybe a very small power saving?
