Answer 1:
If the swap gird starts as a grid filled with zeroes, then the grain that "does not move" will appear to be frozen mid air.
Copying the original grid instead of starting clean (all zeroes) helps preserve everything by default and only updates the direction changes.
This allows the grain that doesn't move to do nothing and just stay in its positon.

Answer 2:
Scanning only from the left to right creates an update bias, causing all the particles to lean or accumulate towards the right. This causes various asymmetries.
Randomizing the column scans removes this bias and maintains symmetry over time as neither side is preferred. It randomly updates the position through out the whole grid columns.


My Brief:
This was a very fun assignment too. It was very cool to see how a small set of rules lead to such a beautiful simulation.
Few problems i faced were optimizing the code so the sand falls a little quicker and adding a lifetime to the fire and smoke particles.
I did try something, but it's not very accurate.
I couldn't spend as much time as i wanted on this due to the time crunch from studying for mid-sems, but i got the main parts done and im happy about that.
Definitely looking forward to finding the optimum ways of writing such code. (for all i know it could be a laptop issue too, which is why the code runs so slow idk).
The thing i found most intersting is how the falling sand very closely mimicks gravity and the wetting property of water (the tendency to spread out) just by checking the cells around a particle.