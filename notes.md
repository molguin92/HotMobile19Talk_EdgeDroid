# Introduction
3 slides
slide 1:
only talk about Human-in-the-loop
we're seeing more and more hitl apps
pokemon go, google glass
the ambission of the work is to target all human in the loop
how to get this to work in an automated scalable fashion
all work with same principle
apps in circle, human loop in middle

slide 2:
problem statement
customers: app developer and system design, researchers

app developer: debug, resource consumptions, interaction vs infrastructure, optimization

system designers (infrastructure providers):
interaction (scaling) 

How do I study these factors?
Problems:
- costs (hiring people)
- repeatability

don't make HARD statements
say it's an important topic

slide 3:
related work
cite zhou, but we don't have systematic knowledge
another argument for work
we know so little because there's no methodological approach
mathematical approach is unpractical

present contributions

slide 4:
narrow down to cognitive assistancea
task model

slide 5:
general approach (trace based)

implementation

################

hitl will be become prolific
dont explain jobs
how do these applications interact with the infrastructure and each other?
we need to understand and optimize these apps and the infrastructure.
core question: which methodology can this optimization with done?
what do these applications comprise
we miss an efficient methodology

high level (categories)
people have been adressing
prototypes
latency studies
maybe something third (analytical models)

--> nobody has been adressing benchmarks

merge work and contributions

discuss approach then cognitive assistance

# comments

slide numbers
Trace-based system is non-trivial, why is it non-trivial?
Trace timing interacts with system.
Don't call model simplistic, talk about straightforward.
Don't call it user model task-state model, sufficient for this task, don't downplay it.

fundamental exciting new wave of applications
no apologetic tone
we have an idealized user, real users get annoyed and so on, this is not captured and that's why there's future work.
this whole task was about a droid, what if this droid could become more human
change trace icon

talk about what the trace is, talk about segmentation

talk more about comparisons, on an optimal system you get '1 Client'
what matters is the upper bound of the system performance
imagine how hard these results would have been to collect with real users
what is the right edge computing infrastructure?

define RTT
reference latency bounds for LEGO
clarify that they come from Zhuo's thesis
clarify that latencies are for end of step to beginning of next one

clarify that we want to measure latencies under load
re-cut slides
cut implementation 
cut user model

use lego as a running example

merge results into 1/2 slides

key question: credibility

remove 'IRB free'
avoids the complexity of human subjects research

change from Results to Use Cases or Example Use of EdgeDroid