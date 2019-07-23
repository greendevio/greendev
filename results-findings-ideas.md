# Aggregated Results

This document shall serve as an aggregate of findings we had/will have during our hangout meetings or ideas that one might come up with.

## Problems

### OSGi-Framework

* bad reputation
* accidental introduction of compexity (at least perceived so by many developers)

### OSGi-Alliance

* members only
* pay to participate
* shows 'some' inertia regarding change

### OSGi-Community

* scattered
* not very active

## Ideas / Solutions
During the last hangout meetings several ideas have come up. Those can roughly be divided into two different categories:

1) Ideas regarding the current/future OSGi framework 
2) Ideas regarding the onboarding and general developer experience with current OSGi framework/future OSGi framework

### Current / Future OSGi Framework

These ideas revolve around rewriting/changing OSGi or creating something completely new that offers developers the advantages of OSGi, namely modularization on classpath level while at the same time avoiding its disadvantages, e.g., many libraries are not supported (no manifest, doing black classpath magic)

Ideas that came up:
* Isolation on process level (@Holger: please elaborate ;) )
* [Febo](https://github.com/greendevio/febo)  
* Use OSGi as plugin-host only (the old embedd osgi into existing app idea, but taken seriously and not just as a "drug to get into OSGI")

### Developer Experience

These ideas address the hard onboarding of new developers and the centralization of tutorials/how-tos/curated libraries/etc.

Ideas that came up:
* A well-curated website with the above mentioned items (including a forum that is not a mailing list -.-)
* A tool like JHipster for OSGi (define your domain model and get a working prototype application)
* A tool like Stackery for OSGi (architect your application visually and get a compiling skeleton)
* The GreenDev Slack Channel could be a spot for OSGi-Newbies people could ask questions too (not discusssed yet)
