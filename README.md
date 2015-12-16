Gerbil-project
==============

Gerbil-project, is an ultra-simple system (based on [Hamster-GTD](http://github.com/we-build-dreams/hamster-gtd)) polished to meet the specific needs of my (your) architectural team.

**Mantras:**

- *ultra-simple system with an easy learning curve for newbies:* newbies don't need to deal with all project files - in large projects there is no time to explain all complexity - so every project has a folder with project managing related files.
- *dynamic:* every project is different so nesting complexity will be adapted to each project (but always following general rules).<sup>2</sup>


###So, how can you start?

**Organize your project:**

- [Folders structure](#folders-structure)
- [Subproject (phases)](#subproject-phases)
- [File naming](#file-naming)
- [File archiving](#file-archiving)
- [Layers](#layers)
- [Others](#others)

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
        
- level of completeness: **layout** or **work**        

===
####Subproject (phases):

- concept or CON
- permit or BP
- tender or TEN
- execution or EXE
- (project) management or PM
       
===
####File naming:

*@ project . subproject (phase) - file + version*

- name your files adding folders notation plus drawing/document name:

        Plans, PP1, P00, P01, P02, P03, (...)
        Elevations, E01, E02, E03, E04, (...)
        Sections, S01, S02, S03, (...)
        Visualization, V01, V02, V03, (...)
        Booklet, B01, B02, B03, (...)
        Detail, D01, D02, D03, (...)
        Siteplan, U01, (...)
        Floors, F01, F02, (...)
        Ceilings, C01, C02, (...)
        Walls, W01, W02, (...)

===
####File archiving:

- archive files using ArqVer<sup>1</sup> (system inspired on [BranchVer](https://github.com/we-build-dreams/branchVer) where each version *adds* a change on data: **+ branch . progress**

        Use a letter as major branch, a letter as minor branch and 2 digits for work progress. No dots.
        Example: @house in lisbon.permit-plans+AF02

===
####Layers:

- as defined in the dwg and ctb files attached. *(Coming soon)*

===
####Others:

- to simplify (not everybody is a geek) when naming use spaces.
- but avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

---
<sup>Notes:</sup><br>
<sup>1 - SemVer implies an incremental versioning that doesn't always happen in architectural projects, one particular version might not be more advanced than other, it is just a different path. ArqVer appears to solve that problem.</sup><br>
<sup>2 - E.g. doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices do it..</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Gerbil-project</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
