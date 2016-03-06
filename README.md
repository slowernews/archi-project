Gerbil-project
==============

Gerbil-project, is an ultra-simple system (based on [Hamster-GTD](http://github.com/we-build-dreams/hamster-gtd)) polished to meet the needs of an architectural team.

*MANTRAS:*

- *dynamic:* every project is different so nesting complexity will be adapted to every project (but always following general rules).<sup>1</sup>
- *ultra-simple system with an easy learning curve for newbies:* newbies don't need to deal with all files - in large projects there isn't even time to explain all complexity - so every project has a subproject with project managing related files.

###So, how can you start?

**Organize your project:**

- [Folders structure](#folders-structure)
- [Subproject (phases)](#subproject-phases)
- [Naming](#naming)
- [Archiving](#archiving)
- [Layers](#layers)

===
####Folders structure:

*@ project . subproject (phase) - level of completeness - specific folder*

- project: **@**

        Example: @house in lisbon

- phase: **.**

    	Inside projects you have project phases:
        Example: .permit

        To reduce the need of memorization, when naming the subproject folder
        add the project name:
        Example: @house in lisbon.permit
        
- level of completeness: **layout (release)** or **work (in progress)**        

===
####Subproject (phases):

- concept or CON
- permit or BP
- tender or TEN
- execution or EXE
- (project) management or PM
       
===
####Naming:

*@ project . subproject (phase) - file + version*

- name your files adding folders notation plus drawing/document name:

        Plans: PP1, P00, P01, P02, P03, ...
        Elevations: E01, E02, E03, E04, ...
        Sections: S01, S02, S03, ...
        Visualization: V01, V02, V03, ...
        Booklet: B01, B02, B03, ...
        Detail: D01, D02, D03, ...
        Siteplan: U00, ...
        Floors: FP1, F00, F01, ...
        Ceilings: CP1, C00, C01, ...
        Walls: WP1, W00, W01, ...
        
- avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

===
####Archiving:

- archive releases of (sub)projects using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . progress**

- archive files using [BranchVer](https://github.com/we-build-dreams/branchVer) (each version *adds* a change on data): **+ branch . progress**

        Use a letter as branch and 3 digits for work progress. No dots.
        Example: @house in lisbon.permit-plans+AF02

===
####Layers:

- as defined in the dwg and ctb files attached. *(Coming soon)*

---
<sup>Notes:</sup><br>
<sup>1 - E.g. doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices do it..</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Gerbil-project</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
