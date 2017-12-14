---
layout: default
---

# [](#header-1)Contact Information



<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
}

/* Create two equal columns that floats next to each other */
.column {
    float: left;
    width: 50%;
    padding: 10px;
    height: 370px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media (max-width: 600px) {
    .column {
        width: 100%;
    }
}
</style>

<div class="row">
  <div class="column" style="background-color:white;">
    <img src="./assets/images/image10.png" width="200" height="200" />
    <img src="./assets/images/UL.png" width="200" />
    <p> CRIStAL UMR CNRS 9189 </p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h3>Email</h3>
    <p>john DOT klein AT univ-lille.fr</p>
    <h3>Address</h3>
    <p> Université de Lille, 
    Bureau 205, P2 Building, avenue Carl Gauss
59655 Villeneuve d'Acsq, France.</p>
    <h3>Position</h3>
    <p> Associate Professor </p>
  </div>
</div>

[comment]: <> (![](./assets/images/image10.png =200x200))

* * *

# [](#header-1)Short Bio

Since September 2009, I am a (tenured) associate professor at the University of Lille (formerly University of Lille1 Sciences and Technologies). I belong to the faculty of sciences and technologies which is located in the "Cité Scientifique" campus of Villeneuve d'Ascq. I am a member of the department of electrical engineering and automation department but I also teach in the department of computer sciences. I am also affiliated to CRIStAL, the research center in computer sciences, automatic control and signal processing of the university.

I obtained the H.D.R. in mathematical sciences from the University of Lille1 Sciences and Technologies and a Ph.D. in informations sciences from the University of Rouen. Prior to that, I was an intern in Beijing University and I obtained a Master degree from the University of Bordeaux1 and ENSEIRB.

* * *

# [](#header-1)Research

Here is a short description of my research activities (topics and publications)

## [](#header-2)Topics

My leading research activity is (computational) **reasoning under uncertainty** which is a field of data sciences and artificial intelligence. 

**Uncertainty** arises in many circumstances:
* when data is noisy (e.g. photon counting data is Poisson distributed),
* when we need a simpler picture (e.g. a Brownian motion describes general statistical properties of the movement of a dust particle),
* when data is missing (e.g. the value of a feature is sometimes unknown for some examples in a dataset).

**Probabilities** are an appealing mathematical model to grasp uncertainty. However, there are several kinds of uncertainty and, in particular, imprecision needs special care to be correctly modeled. When the truth or the falsity of a proposition cannot be (fully) determined in light of evidence, one can introduce a third epistemic state: the _don't know_ state. 

State      | known to be true | known to be false | don't know |
-----------|:-----------------|:------------------|:-----------|
Probability|_u_               | _v_               | _w_        |

Probabilities can be distributed on each state as usual: _u + v + w = 1_. By building upon this idea, we see that probability triplets for each proposition must follow some assignment rules. This is one way to derive the framework of the theory of **belief functions** in which I made most of my contributions.

> Related frameworks are:
> Fiducial inference, Robust Bayesian analysis, Imprecise probabilities, Lower previsions, Second order probabilities, Random measures,

I also work on image processing, information fusion and machine learning.

## [](#header-2)Publications

### Journal papers

 J. Klein, S. Destercke, O. Colot, ***Idempotent conjunctive and disjunctive combination of belief functions by distance minimization***, in International Journal of Approximate Reasoning, vol. 92, pp. 32-48, 2018 [https://doi.org/10.1016/j.ijar.2017.10.004](https://doi.org/10.1016/j.ijar.2017.10.004) - [Code](https://github.com/john-klein/Conjunctive-and-Disjunctive-combination-by-distance-minimization) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal8.pdf" style="color: rgb(22,184,78)">PDF</a>

 J. Klein, S. Destercke, O. Colot, ***Interpreting evidential distances by connecting them to partial orders: Application to belief function approximation***, in International Journal of Approximate Reasoning, vol. 71, pp. 15-33, April 2016, [http://dx.doi.org/ 10.1016/j.ijar.2016.01.001.](http://www.sciencedirect.com/science/article/pii/S0888613X16000025) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal7.pdf" style="color: rgb(22,184,78)">PDF</a>
 
 S. Li, H. Wang, Y. Tian, A. Aitouche and J. Klein. ***Direct power control of DFIG wind turbine systems based on an intelligent proportional-integral sliding mode control***, in ISA Transactions, vol. 64, pp. 431-439, September 2016, 
 [http://dx.doi.org/10.1016/j.isatra.2016.06.003.](http://www.sciencedirect.com/science/article/pii/S0019057816301112) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal6.pdf" style="color: rgb(22,184,78)">PDF</a>
 
 M. Loudahi, J. Klein, J. M. Vannobel and O. Colot, ***Evidential Matrix Metrics as Distances Between Meta-Data Dependent Bodies of Evidence***, in IEEE Transactions on Cybernetics, vol. 46, no. 1, pp. 109-122, Jan. 2016., [doi: 10.1109/TCYB.2015.2395877](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7035103) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal5.pdf" style="color: rgb(22,184,78)">PDF</a>

 M. Loudahi, J. Klein, J.-M. Vannobel, O. Colot, ***New distances between bodies of evidence based on Dempsterian specialization matrices and their consistency with the conjunctive combination rule***, in International Journal of Approximate Reasoning, vol. 55, issue 5, pp. 1093-1112, July 2014, 
 [http://dx.doi.org/10.1016/j.ijar.2014.02.007.](http://www.sciencedirect.com/science/article/pii/S0888613X1400036X) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal4.pdf" style="color: rgb(22,184,78)">PDF</a>

 C. Feudjio, J. Klein, A. Tiedeu, O. Colot, ***Automatic extraction of pectoral muscle in the MLO view of mammograms***, in Physics in Medicine and Biology, vol.58 , no. 23, pp.8493-515, 2013, [doi: 10.1088/0031-9155/58/23/8493](http://iopscience.iop.org/article/10.1088/0031-9155/58/23/8493/meta;jsessionid=A27324D21E5FAA2B1838D5FB7DCA99BA.c3.iopscience.cld.iop.org). - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal3.pdf" style="color: rgb(22,184,78)">PDF</a>
 
 J. Klein and O. Colot, ***Singular sources mining using evidential conflict analysis*** in International Journal of Approximate Reasoning, vol. 52, pp. 1433–1451, Dec. 2011, [http://dx.doi.org/10.1016/j.ijar.2011.08.005](http://www.sciencedirect.com/science/article/pii/S0888613X11001204) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal2.pdf" style="color: rgb(22,184,78)">PDF</a>

 J. Klein, C. Lecomte and P. Miché, ***Hierarchical and conditional combination of belief functions induced by visual tracking***, in International Journal of Approximate Reasoning, vol. 51, pp. 410-428, March 2010, [http://dx.doi.org/10.1016/j.ijar.2009.12.001](http://www.sciencedirect.com/science/article/pii/S0888613X09001819) - 
<a href="https://john-klein.github.io/assets/files/journal_papers/journal1.pdf" style="color: rgb(22,184,78)">PDF</a>


### Conference papers

 J. Klein, S. Destercke, O. Colot. ***Idempotent Conjunctive Combination of Belief Functions by Distance Minimization***, in
Belief Functions: Theory and Applications: Fourth International Conference, BELIEF 2016, Pragua, Czech Republic, September 21-23, 2016. Lecture Notes in Computer Science, Springer.
[doi: 10.1007/978-3-319-45559-4\_16](http://link.springer.com/chapter/10.1007%2F978-3-319-45559-4_16) ***Best paper award*** - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf8.pdf" style="color: rgb(22,184,78)">PDF</a>  -
<a href="https://github.com/john-klein/Conjunctive-and-Disjunctive-combination-by-distance-minimization" style="color: rgb(241,105,19)">CODE</a> 

 J. Klein, M. Loudahi, J. M. Vannobel, O. Colot, ***α-Junctions of Categorical Mass Functions***, in Belief Functions: Theory and Applications: Third International Conference, BELIEF 2014, Oxford, UK, September 26-28, 2014.  Lecture Notes in Artificial Intelligence, Springer, 
[doi: 10.1007/978-3-319-11191-9\_1](http://link.springer.com/chapter/10.1007%2F978-3-319-11191-9_1) - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf7.pdf" style="color: rgb(22,184,78)">PDF</a>

 M. Loudahi, J. Klein, J. M. Vannobel, O. Colot, ***Fast Computation of Lp Norm-Based Specialization Distances between Bodies of Evidence***, in Belief Functions: Theory and Applications: Third International Conference, BELIEF 2014, Oxford, UK, September 26-28, 2014.  Lecture Notes in Artificial Intelligence, Springer, [doi: 10.1007/978-3-319-11191-9\_46](http://link.springer.com/chapter/10.1007%2F978-3-319-11191-9_46) - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf6.pdf" style="color: rgb(22,184,78)">PDF</a>

 J. Klein, O. Colot, ***A Belief Function Model for Pixel Data***, in Belief Functions: Theory and Applications: Second International Conference, BELIEF 2012, Compiègne, France, September 26-28, 2014.  Lecture Notes in Artificial Intelligence, Springer, [doi: 10.1007/978-3-642-29461-7\_22](http://link.springer.com/chapter/10.1007%2F978-3-642-29461-7_22) - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf5.pdf" style="color: rgb(22,184,78)">PDF</a>
 
 J. Klein, O. Colot, ***Automatic discounting rate computation using a dissent criterion***, in Belief Functions: Theory and Applications: First International Conference, BELIEF 2010, Brest, France, September 26-28, 2010. - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf4.pdf" style="color: rgb(22,184,78)">PDF</a>

 J. Klein, C. Lecomte and P. Miché, ***Preceding car tracking using belief functions and a particle filter***, in IEEE International Conference on Pattern Recognition, ICPR 2008, Tampa, FL, USA, December 8-11, 2008,
 [doi:10.1109/ICPR.2008.4761008](http://ieeexplore.ieee.org/document/4761008/) - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf3.pdf" style="color: rgb(22,184,78)">PDF</a>

 J. Klein, C. Lecomte and P. Miché, ***Tracking objects in videos with texture features***, in IEEE International Conference on Electronics, Circuits and Systems, ICECS 2007, Marrakech, Morocco, December 11-14, 2007, 
 [doi:10.1109/ICECS.2007.4511049](http://ieeexplore.ieee.org/document/4511049/) - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf2.pdf" style="color: rgb(22,184,78)">PDF</a>

 J. Klein, C. Lecomte and P. Miché, ***Fast Color-Texture Discrimination: Application to Car Tracking***, in IEEE Intelligent Transportation Systems Conference, ITSC 2007, Seattle, WA, USA, September 30- October 3, 2007,
 [doi:10.1109/ITSC.2007.4357765](http://ieeexplore.ieee.org/document/4357765/) - 
<a href="https://john-klein.github.io/assets/files/conf_papers/conf1.pdf" style="color: rgb(22,184,78)">PDF</a>

### [](#header-3)Thesis

 J. Klein, ***Algebraic and metric structures for belief functions***, HDR thesis, defended on December the 7th, 2017. Université Lille1 Sciences et Technologies. - 
 <a href="https://john-klein.github.io/assets/files/slides_HDR_v3_handout.pdf" style="color: rgb(22,184,78)">SLIDES</a>

 J. Klein, ***Suivi robuste d'objets dans les séquences d'images par fusion de sources, application au suivi de véhicules dans des scènes routières***, PhD thesis (in French), defended on December the 4th, 2008. Université de Rouen. - 
<a href="https://john-klein.github.io/assets/files/TheseFinale_copie1.pdf" style="color: rgb(22,184,78)">PDF</a>



* * *

# [](#header-1)Teaching

I am passionate with teaching and deeply involved in each unit I participate in. I systematically renew teaching contents (both lectures and practicals) when I take over a unit. I also update these contents every year based on students' feedback and colleagues' suggestions.

Here is the list of my current activities

*  Machine Learning > [unit details (in French)](another-page).
*  Real Time Operating Systems > [unit details (in English)](str). 
*  Data Fusion > [unit details (in French)](datfus).
*  Signal Processing > [unit details (in French)](sis).
*  Mobile Robotics > [unit details (in French)](rob).
*  UML > [unit details (in French)](uml).
*  Software Engineering > [unit details (in French)](gl).

In the past, I also taught linear control, digital electronics as well as C, C++ and Java programming. 

* * *


# Responsibility

I have been leading the automation teaching team since 2012. 
This team has 12 tenured members, 4 non teaching staff members and from 2 to 6 temporary members. We are responsible for teaching units dealing with computer engineering, automatic control and signal processing in the faculty of sciences of technologies. We teach every year to around 500 students.


* * *


[comment]: <> (![](https://assets-cdn.github.com/images/icons/emoji/octocat.png))



Copyright © John Klein 2017


