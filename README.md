# Archi-project

Archi-project, is an ultra-simple organization system (based on [Hamster-folder](https://github.com/slownews/hamster-system#hamster-folder)) polished to meet the needs of architects.

*Core values:*

- *progressive:* every project is different so folder's structure complexity will be adapted to each project.<sup>1</sup>
- *simple system with an easy learning curve for newbies:* a macro understanding of the project should be easy to grasp.

### So, how can you start?

**Organize your project:**

- [Folders structure](#folders-structure)
- [Subproject (phases)](#subproject-phases)
- [File naming](#file-naming)
- [Archiving](#archiving)
- [Layers](#layers)

---
#### Folders structure:

*#project @phase -specific folder*

- project: **#**

        Example: #house in lisbon

- phase: **@**

    	Inside projects you have project phases:
        Example: @permit

---
#### File naming:

*PROJECT-PHASE-(OPTION-)DRAWING-DATE*

-E.g:

        PROJ-CON-02-P01-20191019.dwg
        PROJ-EXE-D01-20191019.dwg

---
#### Phases and drawings:

- phases:

        concept: CON
        permit: LIC
        tender: EXE
        building works: BLD

- drawings:

        Plans: PP1, P00, P01, P02, P03, .. PPP (when all plans are in one drawing)
        Elevations: E01, E02, E03, E04, .. EEE
        Sections: S01, S02, S03, .. SSS
        
        Booklet: B01, B02, B03 .. BBB
        Presentation panel/layout: L01, .. LLL  
        Visualizations: V01, V02, V03, ..
        Model photos: M01, M02, M03, ..
        
        Siteplan: G00
        Urban plan: U00
        Topography: T00
        
        Floor types plan: FP1, F00, F01, .. FFF
        Ceiling types plan: CP1, C00, C01, .. CCC
        Wall types plan: WP1, W00, W01, .. WWW
        'Holes' (windows & doors): H01, H02 .. HHH
        Functional cores: N01, N02 .. NNN
        Detail: D01, D02, D03, .. DDD
        Other equipment: Z01, Z02 .. ZZZ
        
        Quantities: Q01, Q02, .. QQQ

<!-- A H I J K O R X Y -->

---
#### Layers:

- as defined in the dwg and ctb files attached. *(Coming soon)*

---
<sup>Notes:</sup><br>
<sup>1 - E.g. doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices do it..</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Gerbil-project</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.