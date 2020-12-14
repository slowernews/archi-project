# Archi-project

Archi-project, is an ultra-simple organization system (based on [Hamster-folder](https://github.com/slownews/hamster-system#hamster-folder)) polished to meet the needs of architects.

*Core values:*

- *simple system with an easy learning curve for newbies:* a macro understanding of the project should be easy to grasp.
- *progressive:* every project is different so folder<sup>1</sup> and files'<sup>2</sup> structure grow in complexity according the particualr needs of that project.


### So, how can you start?

**Organize your project:**

- [Folders structure](#folders-structure)
- [File naming](#file-naming)
- [Phases and drawings](#phases-and-drawings)
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

*PROJECT-PHASE-OPTION?-DRAWING-DATE*

        PROJ-CON-02-P01-20191019.dwg
        PROJ-EXE-D01-20191019.dwg


---
#### Phases and drawings:

- phases:

        concept: CON
        permit (or license): LIC
        tender (or execution): EXE
        building phase: BLD

- drawings:

        Plans: PB1, P00, P01, P02, P03, .. PPP (when all plans are in one drawing)
        Elevations: E01, E02, E03, .. EEE
        Sections: S01, S02, S03, .. SSS
        
        General plan (siteplan): G00
        Urban plan: U00
        Topography: T00
        
        Floor types plan: FB1, F00, F01, .. FFF
        Ceiling types plan: CB1, C00, C01, .. CCC
        Wall types plan: WP1, W00, W01, .. WWW
        Holes (windows & doors): H01, H02 .. HHH
        important Areas: A01, A02 ..
        Details: D01, D02, .. DDD
        Other equipment: Z01, Z02, .. ZZZ
        
        Quantities: Q01, Q02, .. QQQ
        
        Booklet: B01, B02, .. BBB
        Presentation panel/layout: L01, .. LLL  
        Visualizations: V01, V02, ..
        Model photos: M01, M02, .. 
        Sketches: K01, K02, ..
        References: R01, R02, ..

<!-- J I N O X Y -->


---
#### Layers:

- as defined in the dwg and ctb files attached. *(Coming soon)*

---
<sup>Notes:</sup><br>
<sup>1 - The biggest smell in any organizational system is *empty folders*.</sup><br>
<sup>2 - E.g. doesn't make sense to add extra XREF complexity when you are working alone in a micro project. Some offices do it..</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Archi-project</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.