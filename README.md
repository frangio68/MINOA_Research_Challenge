# MINOA Challenge Documentation and Instances

This repository contains instances of a *Non-Periodic Integrated
Timetabling and Vehicle Scheduling Problem* (ITTVS) with a mixed
fleet of electric and internal combustion engines vehicles.
The problem and this data has been developed by personnel of
[M.A.I.O.R. S.r.l.](https://www.maior.it) in collaboration with
personnel of the [Dipartimento di Informatica
dell'Universit&aacute; di Pisa](https://www.di.unipi.it) for the
purpose of the *Scientific Challenge* of the H2020 project
[MINOA - Mixed-Integer Nonlinear Optimization
Algorithms](https://minoa-itn.fau.de).


## Cite

To cite this material you can use the following BibTeX entry:

```
@misc{MINOA2022 ,
 author = {Samuela Carosi and Antonio Frangioni and
           Lorenzo Frangioni and Francesco Geraci} ,
 title =  {MINOA Challenge Documentation and Instances} ,
 year =   {2022} ,
 url =    {https://github.com/frangio68/MINOA_Research_Challenge}
 }
```


## Contents

Three variants of the problem have been devised, of increasing
complexity, for three different categories of participants:
"Junior", "Senior", and "Professional". Accordingly, the [doc](doc)
folder contains three different files which describe the
[Junior](doc/Problem\_Description\_Junior.pdf),
[Senior](doc/Problem\_Description\_Senior.pdf), and
[Professional](doc/Problem\_Description\_Professional.pdf)
different but closely related variants of the problem. A
[unique file](doc/Input\_Output\_format\_description.pdf) describes
the format of the provided JSON input files and required output files,
detailing where the three variants differ. Finally, one file describes
the [rules of the challenge](doc/MINOA\_Challenge\_Rules.pdf),
although these are of little use as of now.

The [instances](instances) folder contains the two sub-folders
[test](instances/test) and [challenge](instances/challenge); the
first contains the instances released during the preliminary phase of
the challenge to let the teams test the waters, while the second
contains the instances released during the final phase for the
purpose of actual scoring. Each of these folders in turn contains the
three sub-folders "Junior", "Senior" and "Professional", each of which
contains what basically are the same instances, except restricted to
the subset of the data required by the simpler versions of the problem
in the case of the "Junior" and "Senior" ones.

No solution data, nor information about the challenge results, is
released here; interested readers can refer to the appropriate
[MINOA web page](https://minoa-itn.fau.de/?page_id=921).


## Authors

The material has been entirely developed by employees of
[M.A.I.O.R. S.r.l.](https://www.maior.it) in collaboration with
personnel of the [Dipartimento di Informatica
dell'Universit&aacute; di Pisa](https://www.di.unipi.it).


## License

This data and the accompanying documents are provided free of
charge under the [Creative Commons Attribution 4.0 International
License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/);
see the [LICENSE](LICENSE) file for details.


## Acknowledgements

MINOA has received funding from the Europeans Union's EU Framework
Programme for Research and Innovation Horizon 2020 under the Marie
Sk&#322;odowska-Curie Actions Grant Agreement No 764759. Samuela
Carosi and Antonio Frangioni are personally very grateful to
Etienne de Klerk for bravely volunteering for the role of member
of the Award Committee. The Challenge Team is grateful to the
MINOA Supervisory Board, and in particular to the Project
Coordinator Frauke Liers, for their unrelenting support to the
Challenge during these complicated times. Specific kudos to
Dennis Adelh&uuml;tte for his collaboration, in particular
regarding the management of the MINOA web pages.
