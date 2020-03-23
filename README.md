# tools
Miscellaneous tools

<H3>qtime</H3>

A tool to report some timing information about a jobs submitted to an Sun Grid Engine (SGE) cluster. The output based on Jim Kent and Galt Barber's para command and the time option in the parasol batch system.

<pre>
qtime h
qtime - List timing information about a Sun Grid Engine job.

usage:  qtime [hD] -j [job_id|job_name|pattern]
</pre>

<pre>
qtime -j 574
Checking completed tasks for job 574 :' my.interesting.job '
Completed: 385 tasks 
Tasks failed: 0 ( 0 zero-time tasks )
Maximum task virtual memory usage: 4170.75M (max.) 3071.62M (avg.)
Wallclock time in finished tasks:  15071677s 251194.62m 4186.58h 174.44d  0.48y
User time    (278.81%):            42021770s 700362.85m 11672.71h 486.36d  1.33y
System time  ( 20.84%):              3140756s 52345.93m  872.43h  36.35d  0.10y
Average wallclock task time:           39147s   652.45m   10.87h   0.45d  0.00y
Longest completed task:               357287s  5954.78m   99.25h   4.14d  0.01y
Submission to last task:             3165773s 52762.88m  879.38h  36.64d  0.10y
</pre>
