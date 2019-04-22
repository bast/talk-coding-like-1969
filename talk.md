
## Coding like it’s 1969

<img src="img/ibm.jpg" style="width: 100%;"/>

.footnote[Bundesarchiv, B 145 Bild-F038812-0014, Lothar Schaack (CC-BY-SA 3.0 DE)]

---

class: center, middle, inverse

# Research software engineering recipes for the next two decades

## Radovan Bast [@\_\_radovan](https://twitter.com/__radovan)

Nordic e-Infrastructure Collaboration/
UiT The Arctic University of Norway

---

## About me

- Theoretical chemist turned research software engineer.
- I write research software and teach programming to researchers and lead the
  [CodeRefinery project](https://coderefinery.org).

.left-column[
### Projects

- DIRAC
- Dalton
- OpenRSP
- XCint
- XCFun
- Numgrid
- GIMIC
- Parselglossy
- Autocmake
- Runtest
- Sonar
- Smeshing
]

.right-column[
### Credits

- Roberto Di Remigio
- Jonas Juselius
- CodeRefinery team
]

---

## CodeRefinery

We teach tools and practices for the
development of reproducible and reusable research software.

<img src="img/map.jpg" style="width: 50%;"/>

- https://coderefinery.org
- https://coderefinery.org/workshops/

---

## CodeRefinery

- We have trained .emph[over 550 students and researchers]
- Across all academic disciplines
- Funding for 2.5 more years

### Our goal

Advance .emph[FAIRness] of software management and development practices so that research groups can
.emph[collaboratively develop], review, discuss, test, share, and reuse their codes.

---

## CodeRefinery

### Our [lessons](https://coderefinery.org/lessons/)

- Basic and collaborative Git
- Git branch design
- Code documentation
- Automated testing
- Jupyter notebooks
- Integrated development environments
- Building portable code with CMake
- Social coding and open software
- Modular code development
- Reproducible research

---

## Goals for this talk

### - Lessons learned from teaching 20 workshops on research software engineering

### - Challenges for the next two decades

- FAIRness in research software development
- Peer review and code review
- Software engineering and academic credit
- Training needs

---

## CodeRefinery: what is our impact? (1/2)

<img src="img/impact1.png" style="width: 80%;"/>

.footnote[https://coderefinery.org]

---

## CodeRefinery: what is our impact? (2/2)

<img src="img/impact2.png" style="width: 70%;"/>

.footnote[https://coderefinery.org]

---

## CodeRefinery: lessons learned

### Demand

- .emph[Demand for training] is huge.
- [The Carpentries](https://carpentries.org) offer great courses in basics but there is .emph[need for more advanced courses].

### Collaborative version control

- Around a third of workshop participants are new to .emph[version control].
- Very few participants use .emph[code review] and .emph[automated testing] before arriving at our workshop.

### FAIR

- .emph[Software licensing and copyright] aspects are new to most participants.
- Code publishing and .emph[code citation principles] are new to most participants.
- .emph[FAIR principles] in software management are far from standard.

---

the paper

---

Publishing computational results without accompanying code will become unacceptable

---

class: center, middle, inverse

## Software reproducibility 10-year challenge:

# Try to build **your code** from 10 years ago

---

## Software reproducibility 10-year challenge

### Couple of uncomfortable questions:

- Can you still .emph[find] your code?
- It was probably not on GitHub (GitHub launched only 11 years ago, GitLab is only 6 years old).
- Can you bring it to a .emph[well-defined state]?
- Can you bring its documentation to refer to the same state?
- How about .emph[external dependencies]? Have you locked their versions?
- Have you used Git submodules? Have they moved?
- Any hard-coded paths?
- If you manage to build it, how do you know it produces the same results as in the past?

---

Public access today may not be enough to make software findable and accessible in the future

---

Code review should become a standard practice

---

FAIR

---

Dependencies and package management

---

Sharing code and encouraging derivative work may boost your academic impact

---

respect version control

---

version control without code review

---

how code review works

---

why code review

- learning

---

forking

- licenses
- open master

---

social coding

in/out

licenses

---

doi

---

developer of QC code:
"i don't have time to learn tool x, i am a chemist"

experimental spectroscopist:
"i don't have time to learn how the instrument works, i am a chemist"

"we don't need tests, we are not a software company"

"we don't need a NMR calibration sample, we are not a pharma company"

---

languages

---

iterop
pypi
conda
semver
interop data

---

Establishing a culture and the need for training

---

credit

---

challenges

---

code reading sessions

---

conclusions

link to these slides
