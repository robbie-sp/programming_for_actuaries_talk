# programming talk

## takeaways

- programming is essential in actuarial work, not an afterthought
- actuarial teams need to be supported through training, access to tools, access to experts and adjusted hiring policies

## programming model

- project management and communication:
    - short development cycles - sprints, agile
    - issue tracking, pipeline management
    - Ditching email e.g. Slack, MS Teams, projection management systems, 
- version control which leads to:
    - clear version history
    - backup, easy to revert if necessary
    - understanding why things went wrong
    - easier collaboration (both within teams and across teams), a process to merge changes by team members
    - being able to view changes
    - code reviews
    - pull requests (links to project management and CI)
    - no more accidental changes
    - no more  Jan 10 with RAS change final v3 RAS draft final v2.xslx
    - can 
- conintuous integration:
    - automated checks of changes
    - automated builds
    - automated deployments
- DRY don't repeat yourself
- Project and code documentation
- Testing
    - test driven development
    - unit testing
    - batch testing
    - reconciliation testing
    - speed tests
    - No backward steps, no regressions, speed slow downs
    - Documentation coverage
- Containerised environments
    - reproducible code
    - guarantees analysis/process works the same for everyone
- Quality
    - Decide on a stack (but don't make it too rigid as new tech is coming in all the time)
        - Which base languages (R, Python, Julia, Scala, Matlab, C++, etc)
        - Which version control tool (Git, Murcurial, SVN)
        - Which version control server (GitHub, BitBucket, GitLab)
        - Which continuous integration and testing tool (Jenkins, CircleCI)
    - Coding style
        - For Python - PEP8, docstring standards
    - Documentation tools:
        - For Python: Sphynix, readthedocs
        - For R: Vignettes, etc
    - 
    

## standard actuarial team model

- 'Get some data', explore an idea
- some rough work
- gets developed
- becomes messy, move on to the next problem
- needs to be maintained indefinitely

- data stored in silos
- lots of spreadsheets and links
- copies of logic
- easy for errors to slip in
- difficult to test
- how to version control
- how to refactor
- poor data visualisation options
- cannot extend to more advanced statistical methods
- difficult to follow - complex array formulas, nested if statements, formula in name definitions
- struggles with data changing size
- spreadsheets create dimension problems - restricted to 2 dimensions (how do you model a process that varies by class, underwriting and calendar year)

## A path towards to adopting 'programming techniques'

1. Engage with IT
    - Don't let IT own the conversation - just because you are talking in their language doesn't give them a right of refusal.
    - 'Spec it up and IT will implement it' is not often the solution
    - Explain what you need (simple but will develop over time):
        - access to software - almost everything is free (but you should try to contribute)
        - websites
        - hardware (down the line)
        - try to find IT staff interested (they should be for their own development)
    - Staff shouldn't have to figure this out in their own time or on their own machines first
2.  Training:
    - Add to objectives
    - loads of stuff for free
    - Lots of online courses use Freemium model (e.g. Datacamp, etc)
    - Go on training courses
    - In house training / lunch-and-learns (give people time to run these)
    - Aim for a mix of skills in the team
    - Who is supporting teams in projects
3.  Start simple
    - Give people time / avoid the temptation to rush for results
    - Show off progress to others in the team
    - Examples:
        - Try a new reserving method for a class of business
        - Validation of capital model output
        - An ETL process
        - A dashboard
        - NLP for claims
        - Clustering on a class of business
4.  Get Version Control into projects as soon as possible
    




Get some tools (luckily)

## views

Microsoft engineers tweet: https://twitter.com/DynamicWebPaige/status/1003752510924808193?s=19

Joel test

Data Science for startups book https://bgweber.github.io/

https://www.slideshare.net/PuppetLabs/how-to-build-highperforming-it-teams-including-new-data-on-it-performance-from-puppet-labs-2015-state-of-devops-report

Hadley Wickham slides:
https://speakerdeck.com/hadley/should-all-statistics-students-be-programmers?slide=36

R course
https://dcl-2017-04.github.io/curriculum/upcoming.html
