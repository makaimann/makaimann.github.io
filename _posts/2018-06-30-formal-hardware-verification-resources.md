---
layout: post
title: "Formal Hardware Verification Resources"
date: 2014-04-30
---
# Formal Hardware Verification Resources

Hello everyone! I've finally gotten around to making myself a website. Since Jekyll makes blogging so easy, I thought I'd give it a try.

I started working in the formal methods area about a year and a half ago. Specifically, I've been applying SMT solvers for various applications -- primarily hardware verification. I've found it to be an engaging and exciting field with a very cool body of literature. That being said, there seems to be a horrifying lack of well-curated, introductory resources for formal verification. Of course, there are a few good websites and classes, but compared to a field like machine learning, there's a relatively high barrier to entry. In other words, it's difficult to understand right away and it's easy to get discouraged. This *could* be inherent to the field, but I doubt that. At least for me, a better set of introductory materials could have dramatically improved my learning curve. I've spoken with other students new to the field and the consensus seems to be similar -- the first year in formal methods is rough. There are several fantastic summer school programs aimed at graduate students, but it would be great to have more online resources targeting a less experienced audience.

Because of this need in the field, I have the ambitious goal of creating an introductory set of materials for model checking through this blog. My dream would be to start with basic propositional logic and work up to word-level model checking techniques. This will clearly take time -- of which I don't have enough -- so in the meantime I've collected a few resources that I found useful for learning about formal verification and model checking. This list is biased towards seminal papers in model checking approaches to hardware (as opposed to software or hybrid systems) verification. While this is a biased choice because of my research area, this also seems reasonable as most of the initial formal verification research was for hardware. The majority of the papers on this list were suggested to me by [Dr. Cristian Matterei](http://www.mattarei.eu/cristian/). I'm also throwing in a couple resources for SAT and SMT.

This is by no means an exhaustive list, there are plenty of great papers and resources. If you feel that there is an important missing resource, please let me know!

* Boolean Satisfiability (SAT) and Satisfiability Modulo Theories (SMT)
  * [A Primer on Boolean Satisfiability](https://homes.cs.washington.edu/~emina/blog/2017-06-23-a-primer-on-sat.html)
  * [Introduction to First Order Logic](https://plato.stanford.edu/entries/logic-classical/)
  * [Introduction to Satisfiability Modulo Theories](https://cs.nyu.edu/~barrett/pubs/BT14.pdf)
  * [NYU Class Materials: Logic in Computer Science](https://cs.nyu.edu/courses/fall09/G22.2390-001/index.html)
  * [NYU Class Materials: Topics in Automated Deduction](https://cs.nyu.edu/courses/spring07/G22.3033-009/index.html)
  * A fantastic set of fun problems and examples: [SAT/SMT by example](https://yurichev.com/writings/SAT_SMT_by_example.pdf)
  * Books
    * [Decision Procedures -- An Algorithmic Point of View](http://www.decision-procedures.org/)
    * [Handbook of Satisfiability](https://www.amazon.com/Handbook-Satisfiability-Artificial-Intelligence-Applications/dp/1586039296)

* Other Collections
  * [One of the Few Great Collections of SAT/SMT and Model Checking Resources](http://satassociation.org/tutorials.html)

* Seminal Papers in Hardware Model Checking
  * BDD-based Model Checking: [Symbolic Model Checking: 10^20 States and Beyond (1990)](http://www.cs.cmu.edu/~emc/15-820A/reading/burch90symbolic.pdf)
  * Bounded Model Checking: [Symbolic Model Checking without BDDs (1999)](http://fmv.jku.at/papers/BiereCimattiClarkeZhu-TACAS99.pdf)
  * K-Induction: [Checking safety properties using induction and a SAT-solver (2000)](http://www.di.ens.fr/~pouzet/cours/mpri/sheeran-FMCAD00.pdf)
  * Liveness to Safety: [Liveness Checking as Safety Checking (2002)](http://fmv.jku.at/papers/BiereArthoSchuppan-FMICS02.pdf)
  * Interpolation Based Model Checking: [Interpolation and SAT-based Model Checking (2003)](http://www.kenmcmil.com/pubs/CAV03.pdf)
  * Survey on Hardware Verification: [A Survey of Recent Advances in SAT-Based Formal Verification (2005)](http://fmv.jku.at/papers/prasadbieregupta-sttt-7-2-2005.pdf)
  * Property Directed Reachability (IC3): [SAT-Based Model Checking without Unrolling (2011)](https://link.springer.com/content/pdf/10.1007/978-3-642-18275-4.pdf#page=81)
  * Property Directed Reachability Alternate Implementation: [Efficient Implementation of Property Directed Reachability (2011)](https://pdfs.semanticscholar.org/c00f/8211ef5e8ef158d98491f35c7d1f2d565829.pdf)
  * Great Resource to Understand PDR/IC3 (it's tough! I definitely don't have it down yet): [Understanding IC3](http://theory.stanford.edu/~arbrad/papers/Understanding_IC3.pdf)
  * K-Liveness: [A Liveness Checking Algorithm that Counts (2012)](http://www.cs.utexas.edu/~hunt/fmcad/FMCAD12/013.pdf)
  * IC3 with Implicit Predicate Abstraction: [IC3 Modulo Theories via Implicit Predicate Abstraction (2013)](https://pdfs.semanticscholar.org/9d07/b740dffefc9a57f24440d768ee915d51530f.pdf)
  * PDR and k-induction [Property-Directed k-induction (2016)](http://csl.sri.com/users/dejan/papers/jovanovic-fmcad2016.pdf)
  * Modular Reasoning: [Compositional Model Checking](http://www.kenmcmil.com/pubs/CHARME99a.pdf)

* Model Checking Resources
  * [Temporal Logic Introduction](https://plato.stanford.edu/entries/logic-temporal/)
  * [NYU Class Materials: Temporal Logic](https://cs.nyu.edu/courses/fall09/G22.2390-001/index.html)
  * [CMU Class Materials: Introduction to Model Checking](http://www.cs.cmu.edu/~emc/15817-s05/)
  * [Introduction to Model Checking](https://members.loria.fr/SMerz/papers/mc-iste2008.pdf)
  * Books on Model Checking
    * [Model Checking](https://www.amazon.com/Model-Checking-Clarke-Edmund-published/dp/B00EKYH80W/ref=sr_1_5?ie=UTF8&qid=1530411611&sr=8-5&keywords=model+checking+clarke)
    * [Introduction to Formal Hardware Verification](https://www.amazon.com/Introduction-Formal-Hardware-Verification-Thomas/dp/3540654453/ref=sr_1_1?s=books&ie=UTF8&qid=1530411669&sr=1-1&keywords=introduction+to+formal+hardware+verification)
