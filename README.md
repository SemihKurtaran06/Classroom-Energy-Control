**CLASSROOM ENERGY CONTROL USING OCCUPANCY AND DAYLIGHT**

I wanted to do this research to explore how we could use energy more efficiently
at my school while learning more about electronics and circuit simulation. I also
wanted to take my first step into the research culture I hope to be part of as
an engineering student in the United States. This project gave me a chance to follow
a question of my own, learn through trial and error, and share what I found.
I hope you enjoy exploring it as much as I enjoyed working on it!

I compare manual and automatic lighting for a model of my school's classrooms,
then test how missed detections and switch-off delays affect service continuity.
The scope is four fluorescent fixtures and one smartboard per classroom.

START HERE
report/       Research report, results and limitations.
figures/      Schematic previews in PNG.
schematics/   Editable circuits and command text files.
results/      Measurement tables and school-scale totals.
NOTES.txt     Model assumptions and input sources.

RUNNING THE EXPERIMENTS
Software used: LTspice 26.1.1 for Windows.

Main comparison:
Open schematics/classroom_main_clean.asc. Open main_commands.txt in the same
folder, copy its contents and paste them as a SPICE directive in the schematic.

Sensor-gap test:
Open schematics/classroom_stress_clean.asc and do the same with
stress_commands.txt.

Use only the matching command block, once. If you have already pasted commands,
replace them rather than adding another copy. Run the simulation and open the
SPICE Output Log for measurements. The setting outputs identify each case.

The results are simulations, not measured school energy savings.
