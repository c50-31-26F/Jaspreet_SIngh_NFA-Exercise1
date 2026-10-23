# Jaspreet_SIngh_NFA-Exercise1
The part that gave me the most trouble was not the NFA design itself but the tools,
because I was completely new to GitHub and JFLAP and felt stressed at the start.
Problem #6 took me the longest, but I did not skip any problem for being too hard.
To get unstuck, I met my professor on Zoom, and he showed me how to use Multiple Run
(batch run) and Simulate (step by step) in JFLAP. I also used AI to understand
why my strings were rejected and to learn how to commit files and write Markdown on GitHub.
My gold-st-ring came in #6 (starts with 10): "100" and every longer string was rejected.
I had typed the q2 self-loop as "0,1" and then "01", and JFLAP reads each of those as one
multi-character string. So after reading "10", the set of next states was empty instead
of {q2}, and the path died. I fixed it with two separate loops, one for 0 and one for 1.
In future projects, exams, or real state controllers, I will use one symbol per transition,
test the shortest and edge-case strings first, and use Simulate to see exactly where a path
fails. I also learned that Windows can hide file extensions, and that a .md file only links to pictures.
