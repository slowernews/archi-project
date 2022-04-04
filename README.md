# Archi-project

An ultra-simple organization system (based on [Hamster-folder](https://github.com/slownews/hamster-system#hamster-folder)) polished to meet the needs of architects.

### Core values

- *Easy learning curve for newbies:* a macro understanding of the project should be easy to grasp.
- *Progressive:* every project is different so folder[^1] and file[^2] structure are not fixed. However complexity - when needed - will grow in a predictable way.

### So, how can you start organizing your project?

- [Folders structure](#folders-structure)
- [File naming](#file-naming)
- [Layers](#layers)




## Folders structure

*#project @phase -specific folder*

- project: **#**

        Example: #house in lisbon

- phase: **@**

    	Inside projects you have project phases:
        Example: @license

- folder: **@**

        Inside phases you have specific folders:
        Example: -sections



## File naming

*project -phase -drawing +date*

        PROJ-CON2-P01+20211019.dwg
        PROJ-EXE-D01+20211019.dwg

- phases (and version when needed):

        concept: CON (CON2, CON3, ..)
        permit (or license): LIC (LIC2, LIC3, ..)
        tender (or execution): EXE (EXE2, EXE3, ..)
        building phase: BLD

- drawings:

        Urban plan: U00 or UUU
        Topography: T00 or TTT
        General plan (siteplan): G00 or GGG

        Plans: PB1, P00, P01, P02, P03, .. PPP (when all plans are in one drawing)
        Elevations: E01, E02, E03, .. EEE
        Sections: S01, S02, S03, .. SSS

        Floor types plan: FB1, F00, F01, .. FFF
        Ceiling types plan: CB1, C00, C01, .. CCC
        Wall types plan: WP1, W00, W01, .. WWW
        Holes (windows & doors): H01, H02 .. HHH
        important Areas: A01, A02 .. AAA
        Details: D01, D02, .. DDD
        other equipment: Z01, Z02, .. ZZZ

        Quantities: Q01, Q02, .. QQQ

        sKetches: K01, K02, .. KKK
        Visualizations: V01, V02, .. VVV
        Model photos: M01, M02, .. MMM
        presentation panel/Layout: L01, .. LLL  
        Booklet: B01, B02, .. BBB
        References: R01, R02, .. RRR

<!-- J I N O X Y -->




## Layers

- as defined in the dwg and ctb files attached. *(Coming soon)*




---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Archi-project</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

[^1]: The biggest "smell" in any organizational system is *empty folders*
[^2]: E.g. doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices still do it..