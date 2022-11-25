* Open-source multilingual biographic resources of A. Grothendieck

[[./img/groth2.jpeg]]

Small biographic desc

* Why learn Category Theory?

Category Theory is considered by many to be an involved subject to get into. It becomes a ground for unification of interdisciplinary mathematical ideas; and the way it achieves this is by taking an abstract vantage point on objects, relationships, states, events, processes, and trajectories of these disciplines. This level of abstraction acts as a ground for reasoning precisely about a wide gamut of patterns happening in distinct domains by drawing rigorous analogies across them.

This abstract viewpoint is *both a strength and weakness* of the approach. The abstract nature of the subject makes it very powerful by giving it the generality to unite very different fields of study such as say algebraic topology, probability theory, real analysis, functional analysis, number theory, combinatorics, and computation. But at the same time this abstract nature means that it becomes a rather tough endeavour to make its bearings on concrete subjects of study. It makes it hard to elucidate these without first learning enough terminology and understanding to set up a framework for discourse for the discipline under the study.

#+BEGIN_HTML
<a href="https://math.ucr.edu/home/baez/rosetta.pdf"><img align="center" src="./img/rosetta-stone.png" /></a>
#+END_HTML

Category theory in certain communities of practice has moved towards being the heart of capturing the correspondences across different systems under study. One of the great papers that catalogues the gems by taking this vantage point is the *[[https://math.ucr.edu/home/baez/rosetta.pdf][Rosetta Stone paper]]* by John Carlos Baez and Mike Stay.

In this paper they detail how disparate domains like physics, topology, logic, and computation show strong parallels between their concepts when seen from the Category Theory viewpoint. As can be seen in the table, they point out the parallels between concepts among different domains of inquiry. Seen this way, Category Theory gives a language and a setting to talk about working concepts in different domains of inquiries and unifies them using higher level abstractions.

If you feel this is getting highly theoretical, ultimately, as Christopher Strachey put it, the divide between theory and practice is artificial and injurious. For doing computing both needs to be put together in a symbiotic circle to *make each other a fertile field of knowledge and action*. Category Theory in this manner can be said to be a subject whose keen study will payoff in the form of better decision-making in your day-to-day job over the long term. To articulate exactly how this is something a bit elusive to me at the moment, I am only seeing glimpses of how the concepts give me a way to talk about ideas happening in my daily programming. As I am a learner only trying to come in terms with the deep implications Category Theory has on my work, I will need some more time to reframe this section to articulate the benefits of Category Theory in the long term on my daily practice.

So at this moment, this repository is a curation of the best resources that were recommended to me. It also includes the ones that came across my way and those that have helped me in understanding the lay of the land better. Hope you enjoy going through it as much as I enjoyed in putting it together. Happy learning!

* Introduction

#+BEGIN_HTML
<img align="left" src="./img/samuel-eilenberg.png" />
<img align="left" src="./img/saunders-maclane.png" />
#+END_HTML

Category Theory is a field of study that emerged around 1940s. By that time, the tangled web of inquiries in mathematics had accumulated many ideas from other fields. The inventors used Category Theory as a ground for unifying these different ideas under a common set of abstractions by studying these broad ranging ideas deeply. It was introduced by *Samuel Eilenberg* and *Saunders Mac Lane* to study algebraic topology, where they wanted to introduce the idea of natural transformation to make tractable the idea of naturality occuring on functors between functors (A functor is a category theoretical term that roughly means functions and the idea of naturality can very roughly be compared to the idea of talking about a concept without a given frame of reference).

#+BEGIN_HTML
<br />
<a href="https://garlandus.co/OfGroupsAndMonads.html"><img align="left" src="./img/on-groups-and-monads.png" /></a>
#+END_HTML

If you enjoy reading the history of the subject before diving into it, I highly recommend this accessible work by Garlandus [[https://garlandus.co/OfGroupsAndMonads.html][describing the emergence of Category Theory]]. Garlandus’ essay holds a high place in my mind, it is the kind of work that gives a sufficient background on the field discussing details of how it took shape as a result of contributions between multiple people. He locates *Hilbert’s Göttingen* as a central locus that lead to the germination of work on Category Theory.


#+BEGIN_HTML
<br />
<img align="left" src="./img/samuel-eilenberg.png" />
<img align="left" src="./img/eilenberg-automata.png" />
#+END_HTML

Now, seeing that the subject emerged from algebraic topology, the application to Computer Science may seem arbitrary. But this came after deep investigations into computational structures and programming since around 1960s, where multiple links between algebra, automata, computational control/data structures, recursion schemes were unearthed. If you are interested in knowing about it more deeply, I have a [[https://github.com/prathyvsh/morphisms-of-computational-structures][repo]], which is a work in progress, where I try to unravel these links. A curious fact that I have to mention is that, one of the co-inventors of Category Theory, Samuel Eilenberg, went on to apply his ideas to automata after inventing Category Theory!

A nice recent article is penned by Emily Riehl showing how ∞-categories act as a great foundation for mathematics [[https://www.scientificamerican.com/article/infinity-category-theory-offers-a-birds-eye-view-of-mathematics1/][up here]]. It is written in an accessible manner to give a bird’s eye view of the whole field showing how it interconnects with other mathematical fields.

Now that we have seen how Category Theory came around, let us look at the resources that can guide us in building a working knowledge of the subject.

* Overview

Because of the standing of Category Theory as a general domain of inquiry, I have constantly felt it better to first get a cursory knowledge in functional programming and abstract algebra before tackling the subject. These paradigms are closer to the work done in Category Theory. If you come around to Category Theory without having some concrete experience in dealing with problems to which you can relate the ideas you learn here, I feel it might be a bit hard to connect with this domain of study and gain intuition into to why such machinery is needed.

Functional programming techniques are a way in which a lot of these concepts find a space to talk about them and ground them in a concrete setting where their behaviours can be probed and pondered. So I proceed to recommend some resource that might help you develop some functional programming knowledge before you come around to Category Theory.

#+BEGIN_HTML
<div>
<img align="left" height="300px" src="./img/htdp-cover.gif" />
#+END_HTML

** [[https://htdp.org][How to Design Programs (First Edition)]]

How to Design Programs is an accessible introduction to functional programming. The book is thorough in its coverage of essential ideas and slowly walks a novice through exercises to understand the concepts and how to put them to use in practical problems that one may encounter in their daily practice.

#+BEGIN_HTML
</div>
<br/><br/><br/><br/><br/><br/>
<div>
<img align="left" height="300px" src="./img/intro-to-fp-cover.jpg" />  
#+END_HTML

** [[https://amzn.to/2S129wI][Introduction to Functional Programming]]

Introduction to Functional Programming by Richard Bird and Philipp Wadler is a more formal treatment of functional programming. They use the language Miranda to elucidate the concepts.

#+BEGIN_HTML
</div>
<br/><br/><br/><br/><br/><br/><br/><br/>
<div>
<img align="left" height="300px" src="./img/sicp-cover.jpg" />
#+END_HTML

** [[https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html][Structure and Interpretation of Computer Programs]]

SICP by Abelson and Sussman is considered a classic text that provides a synthesis of great ideas of computer science using LISP. It is a natural second choice once you have mastered the ideas in HtDP.

#+BEGIN_HTML
</div>
<br/><br/><br/><br/><br/><br/><br/><br/>
#+END_HTML

Reading some or all of the books here will give you a solid footing in functional programming. With that knowledge under your belt, next step is to develop sufficient understanding of the field of mathematics. This knowledge would make the transition into CT much more smooth as there are deep links within CT that lead you onto very different domains and having a well-rounded knowledge of the field would help you to ease into fields which might be remote from your experience, but would nevertheless hold the gold, so to speak.


* Breadth and Depth

#+BEGIN_HTML
<br />
<img align="left" src="./img/saunders-maclane.png" />  
<img align="left" height="300px" src="./img/mathematics-form-and-function.jpg" />  
#+END_HTML

** [[https://amzn.to/3jpD9eO][Mathematics Form and Function]]

To make this case, let me first mention this book by Saunders Mac Lane, the co-inventor of Category Theory, where he gives a tour of ideas of mathematics in a comprehensive way. This book doubles out as an atlas of mathematical inquiry as there are multiple maps in this book that give you an idea on how to navigate the field. Such is the kind of breadth and depth that has gone into building Category Theory. I don’t mean this as something to intimidate the reader, but just to provide the awareness that the field is vast and finds application in many areas, computation being one among many. Mastery of all these fields is not a pre-requisite to be proficient in it. But it has to be pointed out that the masters of the subject have done a great deal of exploration to bring forth the fruits of Category Theory.

#+BEGIN_HTML
<img align="center" width="400px" src="./img/mathematics-form-and-function-map.jpg" />  
#+END_HTML

* Introduction through Abstract Algebra

Now an adjacent field to Category Theory is Abstract Algebra. The route I have taken is to first learn abstract algebra which undergirds the algebraic species that are often subjects of study in Category Theory. To make sense of these, let me mention a few books. It is not mandatory reading, if you want to dive first into Category Theory. In fact some of the books that I have put together here allows one to learn Category Theory without much prerequisite knowledge but abstract algebra is a field that I have felt is most proximate and has aided me ease into Category Theory texts.

#+BEGIN_HTML
<br />
<img align="left" height="300px" src="./img/a-book-of-abstract-algebra.jpg" />  
#+END_HTML

** [[https://amzn.to/2S3SOVc][A Book of Abstract Algebra]]
*Charles Pinter*

This book by Charles Pinter reads not like a textbook but like a description of the field.

#+BEGIN_HTML
<br /> <br /> <br /> <br /> <br /> <br /> <br /> <br />
<img align="left" height="300px" src="./img/a-concrete-approach-to-abstract-algebra.png" />  
#+END_HTML

** [[https://archive.org/details/AConcreteApproachToAbstractAlgebra][A Concrete Approach to Abstract Algebra]]
*W. W. Sawyer*

A narrative approach for Abstract Algebra is given by Sawyer by focussing on concrete applications.

#+BEGIN_HTML
<br /> <br /> <br /> <br /> <br /> <br /> <br /> <br />
<img align="left" height="300px" src="./img/visual-group-theory.jpg" />  
#+END_HTML

** Visual Group Theory
*Nathan Carter*

Visual Group Theory by Nathan Carter gives an overview of the field by relying on visualizations. His playground for the cayley diagram explorations gives a good idea of the quality of work that has gone into producing this book.

#+BEGIN_HTML
<br /> <br /> <br /> <br /> <br /> <br /> <br /> <br />
#+END_HTML

I will try to expand on this catalogue once I have better perspective, but these three seem to be the most promising to get a good overview of the algebraic structures.

Once the above works are studied, starting with Category Theory texts should be an easy process. I will now proceed to list the works which will help an enthusiast to navigate the field of Category Theory and understand it deeper.

* Visual Nature of Category Theory

#+BEGIN_HTML
<img align="left" src="./img/modular-lattice-mckeown.gif" />  
#+END_HTML

Category Theory is the study of objects and morphisms and for this purpose, I find it most important to have a visual setting for exploring these ideas. Many of the ideas being talked about in Category Theory spawns dynamic pictures of morphisms in my head, but I find it hard to visualize them as there is so little Category Theory with pictures around. What is pictured here is an animation by James McKeown of a modular lattice rotating on its vertical axis. These sort of algebraic structures are a part of what we study with Category Theory. And I think there is a certain truth to the idea that geometry is the missing link to ground the abstract ideas that is being studied under Category Theory.

In the orientation section of [[https://raw.githubusercontent.com/mattearnshaw/lawvere/master/pdfs/1996-grassmans-dialectics-and-category-theory.pdf][the paper by Lawvere on Grassman’s mathematical work]] there is a really nice paragraph on the significance of category theory and how it functions as an instrument of analysis and dialectics by serving as a “universal geometric calculus”:


#+BEGIN_HTML
<br/>
<br/>
<br/>
<br/>
<br/>

<blockquote>
<p>
Grassman in his philosophical introduction describes the two-fold division of formal sciences, that is, the science of thinking, into dialectics and mathematics. He briefly describes dialectics as seeking the unity in all things, and he describes mathematics as the art and practice of taking each thought in its particularity and pursuing it to the end. There is a need for an instrument which will guide students to follow in a unified way both of these activities, passing from the general to the particular and from the particular to the general.
</p>

<img src="./img/mathematics-dialectics.png" width="400px" alt="Image showing how mathematics takes the particular to the general and dialectics takes the general to the particular" />


<p>I believe that the theory of mathematical categories (which was made explicit 50 years ago by Eilenberg and Mac Lane, codifying extensive work done by Hurewicz in particular during the 1930’s), can serve as such an instrument. It was introduced and designed in response to a very particular question involving passage to the limit in calculating cohomology of certain portions of spheres, but this particular calculation necessitated an explicit recognition of the manner in which these spaces were related to all other spaces and, in particular, how their motion might induce other motions. In other words, category theory was introduced (and still serves) as a “universal geometrical calculus”.</p>
</blockquote>

</div>

#+END_HTML

#+BEGIN_HTML
<br />
<br />
<br />
<br />
#+END_HTML

* Jamie Vicary’s work

I came across this talk by Jamie Vicary on building tools for exploring Category Theory. His works [[https://globular.science][Globular.science]] and [[https://homotopy.io][Homotopy.io]] are (awe)inspiring. Do check out his talk titled *Category Theory: Visual Mathematics for the 21st Century* and his works to see how he connects proofs, programs, and geometry together in a triad!

*** Category Theory: Visual Mathematics for the 21st Century
#+BEGIN_HTML
<a href="https://www.youtube.com/watch?v=HdZk92s7z1U"><img src="./img/jamie-vicary-talk.jpg" /></a>
#+END_HTML

*** Globular.science and Homotopy.io 

#+BEGIN_HTML
<a href="https://homotopy.io"><img width="450px" src="./img/globular-science.png" /></a>
<a href="https://homotopy.io"><img width="500px" src="./img/homotopy-io.jpg" /></a>
<br /><br /><br /><br />
#+END_HTML

Now when studying category theory, to start seeing how the pieces fit together one has to recourse to abstract diagrams and attempt to connect these concepts with how the same concepts model things in a more visual domain, say topology. This recourse is my best bet at the moment to gain the geometric intuitions in Category Theory when learning. If you find geometric intuitions helpful in understanding mathematics, let me draw your attention to this incomplete but [[https://boris-marinov.github.io/category-theory-illustrated/][beautiful work]] by Boris Marinov.

#+BEGIN_HTML
<a href="https://boris-marinov.github.io/category-theory-illustrated/"><img width="400px" src="./img/category-theory-illustrated.png" /></a>
#+END_HTML

Another work, which is something I am looking forward to work out in detail after I have built up enough fluency is Eduardo Ochs’ internal/external diagrams. He has consistently put out some great set of works where the diagrammatic undercurrent of Category Theory is brought to the forefront. One of his recent works in this direction is: http://angg.twu.net/math-b.html#favorite-conventions The whole page is fully of Category Theory goodness!

[[./img/ochs-convention1.png]]
[[./img/ochs-convention2.png]]

* Some notes on Category Theory

** As a unifying field

Category theory becomes a setting from which you can understand the connection between various mathematical objects that come couched in the contingent scaffolding of a particular theory. Category Theory allows one to map out the structure preserving mappings of a theory’s connection or morphism to other theoretical settings. These mappings go by the name of various “morphisms”, common ones being homomorphism and isomorphism i.e. partial/total equivalent representations of a source representation to a target representation. By adopting such an approach, Category Theory acts as a tool of knowlege transfer and as a medium that helps transfer conceptual knowledge among disparate domains in mathematics.

TODO: List some domains which are far removed at a cursory glance, but is brought together with Category Theory.

** A relational setting

Set theory is seen as a canonical extensional setting where one-to-one correspondence between different mathematical objects is established. Category Theory shifts this focus from elements of the set or any particular theory and asks about what kind of connections exist between two different mathematical structures. This approach gains more patency as we move towards an algebraic approach where mathematical objects are determined and understood by the network of relationships they enjoy with other objects. The idea when operating in Category Theory is that the structure of a mathematical object is sought in the network of relationships it enjoys with other structures of the same kind. These connections are characterized by the morphisms and natural transformations the structure partakes in. A mathematical object in Category Theory gets defined as the sum total of network of relations that object is involved with others. In some sense, this metamathematical outlook seems to derive from topology where connection between two spaces are talked about and how one is the other but modulo some property.

TODO: Elaborate and integrate this idea into this prose. I can't help but feel that this is a crystallization of the idea of manifolds as devised by Bernhard Riemann polished to a fine theoretical setting.

Since a lot of modern mathematics since 1900s was developed using set theory, Category theory assimilates these results by talking about the category of sets. But it is not limited to this vantage point. Categories provide a way to interpret concepts within a category relationally without the need for set theory to back it up.

There is also a way in which Category Theory shows affinity with Synthetic Differential Geometry / Smooth Infinitesimal analysis thereby providing a setting in which continuous concepts can be grounded using this theory.

TODO: Learn more about the relationship between sets and category theory and present a concrete instance where they display pros/cons.

** Elements of Category Theory

Category Theory has nouns (objects), verbs (morphisms), associative law, and composition. Using these basic properties as the primitives, it generates templates with which we can package mathematical objects of arbitrary complexities. Objects of a category are the instances of a certain associated form and transformation between these instances are "morphisms" which preserve the structure of these instances in some specified way.

** Category Theory and Linguistics

With Category Theory, we are moving into a setting where the duality between nouns and verbs find a rigorous expression. That being the case, it might come as no surprise that there is something called Categorical logic which attempts to ground linguistic phenomena and natural language grammar in a category theoretical setting.

TODO: Briefly sketch the work of people using Category Theory for linguistics.
These might be helpful:
- [[https://publish.uwo.ca/~jbell/catlogprime.pdf][The Development of Categorical Logic]]
- [[https://www.webdepot.umontreal.ca/Usagers/marquisj/MonDepotPublic/HistofCatLog.pdf][The History of Categorical Logic 1963-1977]]

TODO: Document how Category Theory becomes an apt setting to study processes. Might also be helpful to outline how Whitehead’s process theory and adjacent fields are finding expression in this field.

* Books

#+BEGIN_HTML
<img width="150px" align="left" src="./img/seven-sketches-in-compositionality.jpg" />
#+END_HTML

** [[https://amzn.to/2RUAIoU][An Invitation to Applied Category Theory: Seven Sketches in Compositionality]]
*David I. Spivak and Brendan Fong (2019)*, 348 pages

#+BEGIN_HTML
<img width="75px" align="left" src="./img/david-spivak.png" />
<img width="75px" align="left" src="./img/brendan-fong.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

This book is considered to be an entry level read into Category Theory. The book samples 7 topics from category to offer a tour of its applications. By showing concrete real life examples are emphasized, a taste for the abstract theoretical concepts is given. It is a pretty good book to get an understanding of the use of Category Theory which a lot of people are puzzled about.

A free electronic edition is available here: [[https://arxiv.org/abs/1803.05316]]

A course to go along with this book is available here: https://forum.azimuthproject.org/discussion/1717/welcome-to-the-applied-category-theory-course

Video lectures for this book are available here: https://youtube.com/playlist?list=PLhgq-BqyZ7i5lOqOqqRiS0U5SwTmPpHQ5

#+BEGIN_HTML
<img width="150px" align="left" src="./img/algebra-chapter-0.png" />
#+END_HTML

** [[https://amzn.to/3brrok3][Algebra: Chapter 0]]
*Paolo Aluffii (2009)*, 728 pages

#+BEGIN_HTML
<img width="75px" align="left" src="./img/paolo-aluffi.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

Once you have covered the abstract algebra books described above, Aluffi’s book is a natural segue as a second course. The book starts by reviewing the basics and very early on gives the reader exposure to Category theoretical language to make sense of the algebraic structures. One curious fact about this book is that there are almost no references to outside resources in this book as the author wanted it to be self-contained. Aluffi explains each topics in a personal style without losing rigour and this book is a favourite among many who have learnt Category Theory. The book is a bit dense at 700 pages but the added advantage is that you get exposed to homological algebra, something that connects algebra with topology, towards the end of the book. I consider this a great read to widen your expertise once you have gotten a cursor understanding of abstract algebra and categorical language.

#+BEGIN_HTML
<img width="150px" align="left" src="./img/conceptual-mathematics.jpg" />
#+END_HTML

** [[https://amzn.to/2zjvbli][Conceptual Mathematics: A First Introduction to Categories]]
*William Lawvere and Stephen Schaneul (2nd edition 2009, 1st edition 1991)*, 408 pages

#+BEGIN_HTML
<img align="left" width="75px" src="./img/william-lawvere.png" />
<img align="left" width="75px" src="./img/stephen-schaneul.png" />
<br /><br /><br /><br />
#+END_HTML

Conceptual Mathematics is a popular favourite choice as an introduction to Category Theory. It starts with set theory and goes upto introducing toposes. It does this 
with minimal amount of prerequisites. The lucid introductions are said to give a conceptual understanding of the ideas of Category Theory. 

#+BEGIN_HTML
<img width="150px" align="left" src="./img/awodey-category-theory.jpg" />
#+END_HTML

** [[https://amzn.to/2HAe42N][Category Theory]]
*Steve Awodey (2010)*, 311 pages

#+BEGIN_HTML
<img align="left" src="./img/steve-awodey.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

Steve Awodey’s work is considered to be a book that goes slightly braoder that Lawvere and Schaneul’s work but for the prerequisities it assumes is on the same level as Conceptual Mathematics. It is a highly recommended work among Category Theorists.

Lectures to this book is available here: https://www.youtube.com/playlist?list=PLGCr8P_YncjVjwAxrifKgcQYtbZ3zuPlb

#+BEGIN_HTML
<img width="150px" align="left" src="./img/basic-category-theory.jpg" />
#+END_HTML

** [[https://arxiv.org/abs/1612.09375][Basic Category Theory]]
*Tom Leinster (2014)*, 190 pages

#+BEGIN_HTML
<img align="left" src="./img/tom-leinster.png" />
<br /><br /><br /><br />
#+END_HTML

Tom Leinster’s book is an edited version of his lecture notes. This concise work with focussed attention given on the topics it addresses. The fundamental topics are covered in this book and a free version is available online here: https://arxiv.org/abs/1612.09375

#+BEGIN_HTML
<img width="150px" align="left" src="./img/category-theory-for-programmers.jpg" />
#+END_HTML

** [[https://github.com/hmemcpy/milewski-ctfp-pdf/][Category Theory for Programmers]]
*Bartosz Milewski (2018)*, 350 pages

#+BEGIN_HTML
<img align="left" src="./img/bartosz-milewski.png" />
<br /><br /><br /><br />
#+END_HTML

Bartosz version features a rich blend of images with descriptions of Category Theory oriented towards a practicing programmer. He frequently blogs about ideas on Category Theory and gives examples in of programming instances where category theory provides leverage. He is an active figure in the discourse surrounding Category Theory on the internet.  

Videos for this book is available as a series here: 
https://www.youtube.com/playlist?list=PLbgaMIhjbmEnaH_LTkxLI7FMa2HsnawM_

PDF versions that is compiled from the blogposts with support for different language is available here: https://github.com/hmemcpy/milewski-ctfp-pdf

#+BEGIN_HTML
<img width="150px" align="left" src="./img/category-theory-in-context.jpg" />
#+END_HTML

** [[https://amzn.to/2yARvpW][Category Theory in Context]]
*Emily Riehl, 2016*, 272 pages

#+BEGIN_HTML
<img align="left" width="75px" src="./img/emily-riehl.png" />
<br /><br /><br /><br />
#+END_HTML

This is an advanced text that can be read by a serious student after one or more of the previous texts have been mastered. The prose is said to be very well written as an exposition ta Category Theory and an example driven approach is relied upon before the category theoretical language is shown to encompass the ideas.

Definitely a book to keep in mind on your journey once you have crossed the rubicon of having understood the basics and has become fluent in the language.

Available as a free PDF here: http://www.math.jhu.edu/~eriehl/context.pdf

#+BEGIN_HTML
<img width="150px" align="left" src="./img/an-introduction-to-category-theory.jpg" />
#+END_HTML

** [[https://amzn.to/3mVREsY][An Introduction to Category Theory]]
*Harold Simmons (2011)*, 238 pages
#+BEGIN_HTML
<img align="left" width="75px" src="./img/harold-simmons.png" />
<br /><br /><br /><br />
#+END_HTML

This is a lesser known introduction to Category Theory. But from the people who have read it, I have heard only good words about it.

#+BEGIN_HTML
<img width="150px" align="left" src="./img/introduction-to-categories-and-categorical-logic.png" />
#+END_HTML

** [[https://arxiv.org/abs/1102.1313][Introduction to Categories and Categorical Logic]]
*Samson Abramsky and Nikos Tzevelekos (2011)*, 101 pages


#+BEGIN_HTML
<img align="left" width="75px" src="./img/samson-abramsky.png" />
<img align="left" width="75px" src="./img/nikos-tzevelekos.png" />
<br /><br /><br /><br />
#+END_HTML

This book was suggested to me by Eduardo Ochs.

This is a short read at around 100 pages, but is said to build up the concepts by giving examples of how category theory captures things in the large and in the small, which showcases ideas like naturality, generality, and rigour that powers Category Theory.

#+BEGIN_HTML
<img width="150px" align="left" src="./img/computational-category-theory.png" />
#+END_HTML

** [[http://www.cs.man.ac.uk/~david/categories/][Computational Category Theory]]
*David Rydehead and Rod Burstall (1988)*, 263 pages

#+BEGIN_HTML
<img align="left" width="75px" src="./img/david-rydehead.png" />
<img align="left" width="75px" src="./img/rod-burstall.png" />
<br /><br /><br /><br />
#+END_HTML

Computational Category Theory uses the Standard ML programming language to give a hands on experience into the category theory ideas.
Having an REPL for interacting with your ideas is a solid way to build your understanding of how these ideas can be represented and manipulated with the computer.
It is available for free online.

#+BEGIN_HTML
<img width="150px" align="left" src="./img/basic-category-theory-for-computer-scientists.jpg" />
#+END_HTML

** [[https://amzn.to/33hXCN6][Basic Category Theory for Computer Scientists]]
*Benjamin Pierce (1991)*, 114 pages

#+BEGIN_HTML
<img align="left" src="./img/benjamin-pierce.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

Pierce’s book is a concise treatment of category theoretical concepts oriented towards a computer scientist. At around 60 pages, the book touches on basic ideas like categories, products, pullbacks, limits, functors, F-algebras, natural transformations, adjoints and gives a discuss on the application of these ideas.

[[https://people.csail.mit.edu/jgross/personal-website/papers/academic-papers-local/repository.cmu.edu__cgi__viewcontent.cgi_article=2846_context=compsci.pdf][Paper]] by Pierce on Category Theory

#+BEGIN_HTML
<img width="150px" align="left" src="./img/topoi-the-categorical-analysis-of-logic.jpg" />
#+END_HTML

** [[https://amzn.to/3n97rF2h9][Topoi: The Categorical Analysis of Logic]]
*Robert Goldblatt (1984)*, 569 pages

#+BEGIN_HTML
<img align="left" src="./img/robert-goldblatt.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

This book begins from a set theorical standpoint of logic and walks the user carefully to develop an understanding of the Category theoretic perspective. Author presents the concrete examples in logic and then abstracts out the common patterns to ground it in the categorical language. I think I wouldn’t be too off if I say that this book is close to Sawyer’s A Concrete Approach to Abstract Algebra. The application of topology to logic makes it a natural segue to understanding Steven Vickers’ work mentioned below.

The book is available online here: https://projecteuclid.org/euclid.bia/1403013939

#+BEGIN_HTML
<img width="150px" align="left" src="./img/category-theory-for-the-sciences.jpg" />
#+END_HTML

** [[https://amzn.to/2Vr801a][Category Theory for Scientists]]
*David I. Spivak (2014)*, 486 pages

#+BEGIN_HTML
<img align="left" src="./img/david-spivak.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

These are the edited version of Spivak’s notes for his 2013 Category Theory course. The original lectures are available online: http://math.mit.edu/~dspivak/CT4S.pdf

#+BEGIN_HTML
<img width="150px" align="left" src="./img/categories-for-the-working-mathematician.jpg" />
#+END_HTML

** [[https://amzn.to/3mHPk8D][Categories for the Working Mathematician]]
*Saunders Mac Lane, (1st Edition 1971, 2nd Edition 1998)*, 317 pages

#+BEGIN_HTML
<img align="left" src="./img/saunders-maclane-small.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

An comprehensive reference on the book written by the co-founder of the field.  The book is said to be thorough on its treatment and a bit demanding on the reader as the mathematics is involved. But this pays off by giving you a rigorous grounding in the material. It is recommended to read this book after one or two of the above books are read before or simultaneously with it.

** Adjacent Reads

Now these are works a bit removed from Category Theory, but still I feel will give one a good understanding of the big picture if put in the effort to understand these:

#+BEGIN_HTML
<img width="150px" align="left" src="./img/topology-via-logic.jpg" />
#+END_HTML

** [[https://amzn.to/2Vp5HLJ][Topology via Logic]]
*Steven Vickers (1989)*, 220 pages

#+BEGIN_HTML
<img align="left" src="./img/steven-vickers.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

Topology via Logic is a book that intrigued me for it showed the link between geometry and logic that I have been always enamoured about. As I have indicated above, there is something geometrical about the abstract mathematical structures and this one is a book that I wish to explore once I have developed sufficient mathematical rigour to understand what is happening in the intersection of topology and logic.

#+BEGIN_HTML
<img width="150px" align="left" src="./img/diagrammatic-immanence.jpg" />
#+END_HTML

** [[https://edinburghuniversitypress.com/book-diagrammatic-immanence.html][Diagrammatic Immanence]]
*Rocco Gangle (2015)*, 264 pages

#+BEGIN_HTML
<img align="left" src="./img/rocco-gangle.png" />
<br /><br /><br /><br /><br /><br />
#+END_HTML

I found out about this book accidentally when searching on Twitter for Category Theory related topics. Once I looked into it, I found the material addressing philosophy from a Category Theoretical standpoint. The work builds on previous works of the author and tries to identify how Category Theory gives us the visual tools to ground the ideas immanent in the work of Spinoza, Peirce, and Deleuze. It contains a rich amount of diagrams showing how category theoretical concepts allows one to locate different kinds of morphisms between different levels and across them. This is something I intend to read once I have worked myself on Peirce’s ouevre and built some amount of category theoretical fluency. But if you are into philosophy and mathematics, I recommend you check it out.

#+BEGIN_HTML
<img width="150px" align="left" src="./img/homotopy-type-theory-cover.png" />
#+END_HTML

** [[https://homotopytypetheory.org/book/][Homotopy Type Theory: Univalent Foundations of Mathematics]]
*Univalent Foundations Project (2015)*, 620 pages

Homotopy came out as the result of [[https://www.ias.edu/ideas/2014/voevodsky-origins][Voevodsky’s attempt]] at trying to create an environment for theorem proving.

And some of the results from this line of inquiry is stunning to say the least. There are interpretations of topological shapes as corresponding types.
It is a bit above my level of understanding to fully articulate what this means for computation and Category Theory. But definitely one of those aspiring reads for me.

** Under investigation

*** [[https://maartenfokkinga.github.io/utwente/mmf92b.pdf][A Gentle Introduction to Category Theory: The Calculational Approach]]

*** [[https://arxiv.org/abs/1912.10642][Notes on Category Theory with examples from basic mathematics (2020)]]

*** [[https://www.di.ens.fr/users/longo/files/CategTypesStructures/book.pdf][Categories, Types, and Structures]]

*** [[http://www.tac.mta.ca/tac/reprints/articles/17/tr17abs.html][Abstract and Concrete Categories: The Joy of Cats]]

** [[https://www.logicmatters.net/resources/pdfs/GentleIntro.pdf][Category Theory: A Gentle Introduction]]
Peter Smith (2018)

* Papers and Presentations

** [[https://people.cs.clemson.edu/~steve/Papers/Rosetta/rosetta1.pdf][Category Theory — Rosetta Paper 1: How Categories Arise Naturally]]

** [[http://www.cs.toronto.edu/~sme/presentations/cat101.pdf][An introduction to Category Theory for Software Engineers]]
Steve Easterbrook

** [[http://www.cs.ox.ac.uk/people/bob.coecke/ctfwp1_final.pdf][Categories for the Working Physicist]]
Bob Coecke and Eric Oliver Paquette

Notes from Coecke and Paquette that introduces category theory for an interested physicist. They introduce the ideas by connecting with vector spaces and tensors.

** [[https://www.cs.ox.ac.uk/files/3395/PRG72.pdf][A Categorical Manifesto]]
Goguen

** [[http://web.sfc.keio.ac.jp/~hagino/thesis.pdf][A Categorical Programming Language]]
Tatsuya Hagino

** [[https://github.com/mattearnshaw/lawvere][Collected Works of William Lawvere]]

* Tools

** Charity

** [[https://github.com/msakai/cpl][CPL Interpreter]]

An interpreter for Tatsuya’s work above.

* Talks

* Series

* The Catsers

* Single Session

** [[https://www.youtube.com/watch?v=cJ46AOEOc14][David Spivak’s intro into Category Theory]]
** [[https://www.youtube.com/watch?v=BLk4DlNZkL8][Adjunctions in Everyday Life]]
** [[https://www.youtube.com/watch?v=JMP6gI5mLHc][Category Theory: The Essence of Interface Design]]

* Blogs

** [[http://chalkdustmagazine.com/features/an-invitation-to-category-theory/][An Invitation to Category Theory]]

A brief introductory post by Tai-Danae Bradley on Category Theory

** [[https://semantic-domain.blogspot.com/2018/08/category-theory-in-pl-research.html][On applications of Cateogry Theory to PL Research]]
A really nice post by Neel Krishnaswami on the applications of Category Theory to programming language research.

** https://www.math3ma.com/blog/what-is-category-theory-anyway
** https://bartoszmilewski.com/category/category-theory/
** https://golem.ph.utexas.edu/category/

* Compilations

** [[https://nodebook.io/nodebook/717/t/x=359.07&y=391.68&k=0.53][Nodebook by Dragan Okanovic]]
This is a really nice collection of some of the resources laid out in a "graph"ical format by Dragan.

** [[https://github.com/statebox/awesome-applied-ct][Awesome applied CT]]
Compilation of applications of Category Theory

** [[http://www.logicmatters.net/categories/][Compendium by Logic Matters]]
A really good roundup of resources for learning Category Theory

** [[https://github.com/drever/act-munich][Applied Category Theory Munich]]
Pretty nice curation by Johannes Drever which includes softwares to explore Category Theory and podcasts for being in the know.

** [[https://wiki.portal.chalmers.se/cse/pmwiki.php/CTFP11/CTFP11][Resources from Chalmers University]]

** [[https://github.com/bgavran/Category_Theory_Machine_Learning/blob/master/README.md][Category Theoretic Approaches to Machine Learning]]
Curation of materials on Category Theory as it applies to Machine Learning

** [[https://diliberti.github.io/Read/Read.html][Suggested readings on Category Theory and Categorical Logic]]
A curated collection of materials on category theory and categorical logic designed for bachelors and masters students who want to have a first encounter with these topics.

** [[https://blog.metatheorem.org/published/2015-12-06-Resources-CT-CS.html][Resources for Category Theory for Computer Science]]
Resources compiled by Harley Eades III

* Category Theory ∩ Open Systems

There are some interesting lines of work unfolding where category theory is illuminating how open systems interact with each other.

An introduction to this can be found at [[https://www.brown.edu/academics/math/sites/math/files/O.Lynch%20thesis.pdf][Open Systems for the Working Mathematician]]

Some of the interesting works in this direction are:

** Generative effects / Emergence

- [[http://www.mit.edu/~eadam/eadam_PhDThesis.pdf][Systems, Generativity, and Interactional Effects]]

Elie Adam

2017

294 pages

** Courser/Baez Double Categorical approach

- [[https://arxiv.org/pdf/2008.02394.pdf][Open Systems: A Double Categorical Approach]]

Kenny Courser

March 2020

183 pages

- [[https://arxiv.org/abs/1911.04630][Structured Cospans]]

John Baez

November 2019

50 pages

** Open Games

- [[https://julesh.com/2017/09/29/a-first-look-at-open-games/][A first look at open games]]

Jules Hedges

September 2017

Blogpost

- [[https://matteocapucci.wordpress.com/2021/05/26/open-cybernetics-systems-i-feedback-systems-as-optics/][Open Cybernetics Systems I: Feedback Systems as Optics]]

Matteo Capucci

May 2021

Blogpost

- [[https://arxiv.org/pdf/1603.04641.pdf][Compositional Game Theory]]

Neil Ghani, Jules Hedges, Viktor Winschel, Philipp Zahn

February 2018

10 pages

- [[https://arxiv.org/abs/1902.08666][From open learners to open games]]
Jules Hedges
February 2019
9 pages

** Algebra of Open and Interconnected Systems

- [[https://arxiv.org/pdf/1609.05382.pdf][The Algebra of Open and Interconnected Systems]]

Brendan Fong

September 2016

230 pages

* Contributors

People who have helped me with resources:

- [[https://twitter.com/mimblewabe][Marek Bernát]]
- [[http://angg.twu.net/math-b.html][Eduardo Ochs]]
- [[https://twitter.com/comandingo][Johannes Drever]]
- [[https://twitter.com/HarmonicesMvndi][Mundy Reimer]]
- And a lot of people who were generous enough to share their recommendations on Reddit / Stackoverflow / Twitter / Quora
