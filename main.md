---
title: "I Aver: Providing Declarative Experiment Specifications 
Facilitates the Evaluation of Computer Systems Research"
author:
  - name: "Ivo Jimenez and Carlos Maltzahn"
    affiliation: "UC Santa Cruz"
  - name: "Jay Lofstead"
    affiliation: "Sandia National Laboratories"
  - name: "Adam Moody and Kathryn Mohror"
    affiliation: "Lawrence Livermore National Laboratory"
  - name: "Remzi Arpaci-Dusseau and Andrea Arpaci-Dusseau"
    affiliation: "University of Wisconsin-Madison"
abstract: |
  Validating experimental results in the field of computer systems is a 
  challenging task, mainly due to the many changes in software and 
  hardware that computational environments go through. Determining if 
  an experiment is reproducible entails two separate tasks: 
  re-executing the experiment and validating the results. Existing 
  reproducibility efforts have focused on the former, envisioning 
  techniques and infrastructures that make it easier to re-execute an 
  experiment. By focusing on the latter and analyzing the validation 
  workflow that an experiment re-executioner goes through, we notice 
  that validating results is done on the basis of experiment design 
  and high-level goals, rather than exact quantitative metrics.

  Based on this insight, we introduce a declarative format for 
  describing the high-level components of an experiment, as well as a 
  language for specifying generic, testable statements that serve as 
  the basis for validation [@jimenez_tackling_2015 ; 
  @jimenez_aver_2015]. Our language allows to express and validate 
  statements on top of metrics gathered at runtime. We demonstrate the 
  feasibility of this approach by taking an experiment from an already 
  published article and obtain the corresponding experiment 
  specification. We show that, if we had this specification in the 
  first place, validating the original findings would be an almost 
  entirely automated task. If we contrast this with the current state 
  of our practice, where it takes days or weeks (if successful) to 
  reproduce results, we see how making experiment specifications 
  available as part of a publication or as addendum to experimental 
  results can significantly aid in the validation of computer systems 
  research.

documentclass: tinytocs
tinytocs: true
numbersections: false
csl: "ieee.csl"
bibliography: "citations.bib"
usedefaultspacing: true
---

# BODY

_Providing declarative statements that describe the outcome of an 
experiment can significantly improve the task of validating its 
results._

# REFERENCES

<!-- hanged biblio -->

\noindent
\vspace{-2em}
\setlength{\parindent}{-0.17in}
\setlength{\leftskip}{0.2in}
\setlength{\parskip}{8pt}
