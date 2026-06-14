# University_Timetabling
This repository contains a report detailing an attempt to carry out the timetabling for the University of Edinburgh. The goal is to schedule all "events" (Lectures, Workshops, Tutorials, etc..) to a timeslot and room, such that resource constraints are satisfied and soft constraint violations are minimised. 

Due to the scale of the challenge two approaches were taken, an exact Mixed Integer Programming approach, and a heuristic approach. We explored scheduling the timetabling in the standard case (Monday-Friday, 9-6) in addition to the cases where we (1) remove friday afternoon teaching, (2) remove teaching from 5-6, (3) remove both.
