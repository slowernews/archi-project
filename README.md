Gerbil-project
==============

Organizing and naming files of an architectural project - and specially with an easy learning curve for newbies - is an huge challenge for any studio. Gerbil-project, is an ultra-simple system (based on [Hamster-GTD](http://github.com/we-build-dreams/hamster-gtd)) polished to meet the specific needs of your team.

**Gerbil-project mantras:**

- *ultra-simple system with an easy learning curve for newbies:* newbies will never see every files of the project where they are working - there is no time to explain all complexity, so every project has a folder with project managing related files. These files are not mixed with the drawings once normally there is specific person that manages them.
- *dynamic:* all projects are different so nesting complexity will change from project to project (but always following general rules). Doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices do it..


###So, how can you start?

**Organize your project:**

- [Folders structure](#folders-structure)
- [Project phases](#project-phases)
- [File naming](#file-naming)
- [File archiving](#file-archiving)
- [Layers](#layers)
- [Others](#others)

---
###// Organize your project

===
####Folders structure:

*@ project . phase - level of completeness - file + version*

- project: **@**

        Example: @house in lisbon

- phase: **.**

    	Inside projects you have project phases:
        Example: .permit

        To reduce the need of memorization, when naming the subproject folder
        you'll add the project name:
        Example: @house in lisbon.permit
        
- level of completeness: **layout** or **work**        

===
####Project phases:

- concept or CON
- permit or BP
- tender or TEN
- execution or EXE
       
===
####File naming:

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
- archive files using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . work in progress**

*(Under revision)*

===
####Layers:

- as defined in the dwg and ctb files attached. *(Coming soon)*

===
####Others:

- to simplify (not everybody is a geek) when naming use spaces instead of camelCase, PascalCase or snake_case.
- but avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Gerbil-project</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
