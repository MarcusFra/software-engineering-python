# The Modomics story

In March 2007 I inherited the [Modomics database](http://www.genesilico.pl/modomics) from Staszek, a MSc student in the lab. Staszek handed me the passwords. Then he moved to Germany. Although he did whatever he could to support me by email, a sackful of knowledge moved away with him.

![Modomics](modomics.jpg)

There was a hard deadline for publication in June. In May, the hard disk of the server crashed. I restored most of the code from the SVN repository and loaded the DB dump. However, some features were lost on the way. I was determined to not only fully recover the project, but also to add enough value to submit the publication on time.

Working on the code was tough: *"What does this mean? How does this work? Why is this character on the web page three positions further to the left than it should?"*

When the deadline drew near, I worked literally every minute until the very last moment, including late evenings and weekends. I was constantly overslept and emotionally brittle to the point of resignation. It took me a year to realize that the correct term for this was burnout.

I missed the deadline, or to be precise, my supervisor hit the **STOP** button. An extra year was the best thing that could happen to the project and its maintainer. I spent more time talking to scientists using the site, clean up many of the issues, and introduce a cleaner structure. In the end, I had rewritten most of the code.

Finally, it was time to give the project away to my successors Sebastian and Kaja. The first thing Sebastian did was that he dumped most of the code and rewrote it in Django within two weeks. Kaja kept on maintaining the server and so the database lives on until the day I write these lines, with different code, but the same vision as when it was first created.

What I learned is that taking over a program from someone is difficult.

### Modomics: Project Overview

| Name | Modomics |
|------|----------|
| Summary | Web database of modified RNA nucleotides. |
| Duration | 2006 - 2014 |
| Developers | 2 coders (2009) |
| Stakeholders | 2 senior scientists, 4 data curators (2009) |
| Size | ~10000 Python LOC |
| Technologies used | TurboGears web server <br> PostGreSQL database <br> Biopython <br> PIL |
| Development tools used | bug tracker (TRAC) <br> automatic tests (partial) <br> SVN repository <br> User Stories <br> Entity-relationship diagram |
| Publications | ADD 3 REFERENCES |

#### Development:
- Everything stored in a single
SVN repository.
- Continuously kept User Stories.
Python libs:
TurboGears
PIL
BioPython

