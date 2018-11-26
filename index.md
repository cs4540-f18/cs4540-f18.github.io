# Course Info

**Lecture Location:** Tu/Th 3-4:15pm in Klaus 2443

**Professor:** 
- Jacob Abernethy
    + Email: prof_at_gatech_dot_edu
    + Office Hours: Monday, 11am-12pm (Klaus 2134)
    
**Teaching Assistants:** 
- Benjamin Bray
    + Email: benrbray_at_gatech_dot_edu
    + Office Hours: Fridays, 12:30-1:30pm (tables between Klaus 2116 and 2124)
- Naveen Kodali
    + Email: nkodali3_at_gatech_dot_edu
    + Office Hours: Wednesdays, 3:00-4:00pm (starting from Sep 5, tables between Klaus 2116 and 2124)

[Please fill out the COURSE SURVEY!](https://goo.gl/forms/LRJRu5DLhkLfmMCt1)

This is an advanced course on algorithms. That is quite a broad topic, and in particular this semester’s course will focus heavily on **algorithms for machine learning**. We will be especially interested in diving into the following topics:

* Numerical Analysis
* Convex Geometry & Optimization
* Probability & Statistical Inference

While students should have a strong back background in core algorithmic concepts, linear algebra, calculus, and probability, we will review many of these topics early in the course. Students will be required to write code in Python, and we will present much of the material in the course using [Jupyter Notebooks](http://jupyter.org/).

## Hands-on Format

In most courses, students learn about material in class through lecture, and then they practice problem solving on their own by doing homework.  In this course we will do the opposite! Students will be required to read material before each class period, and then arrive in class ready to dive into problem-solving.  This way, students can familiarize themselves with basic definitions and examples at home, and benefit from one-on-one interaction with the course staff during lecture while working through more challenging aspects of the material.  Lecture notes for each day will be posted online at least one week prior to each lecture (with the first week as an exception).

Why do it like this? The lecture format is an outdated way to teach mathematical material, especially for topics such as algorithms and machine learning where it is so easy to play with code and implement ideas. The lecture format also limits the professor’s ability to interact directly with students.

Each class period will have the following structure:

* *(0mins)* Students arrive and organize themselves by sitting with their group
* *(5mins)* Students take a very short and simple quiz on assigned reading material
* *(55mins)* Problem time! Instructor presents a sequence of problems, and students are given 5-10 minutes per problem to try to solve each one with their group. Instructors will move around the classroom to engage with students and answer questions.
* *(15mins)* Class wraps with a brief description of the forthcoming material for next period, in a “mini lecture”

## Grading

The course grades will be determined as follows.  Note that the in-class quizzes will be graded generously, and 50% of the credit will be given simply for showing up and answering the questions.

| Homeworks		| 35% |
| Attendance + Quizzes	| 15% |
| Midterm Exam		| 20% |
| Final Exam		| 30% |

Quizzes will be entered electronically, via a web form, so make sure you have a phone, laptop, or tablet with you in class!  If you don’t have access to any of these, please let the instructor know.  The grading scheme will be:

* 2 points for a correct answer
* 1 point for an incorrect answer
* 0 points for not taking the quiz

Your **five lowest quiz scores will be dropped**, which should be enough to account for quizzes missed due to planned or unplanned absences.

Students are allowed, and indeed encouraged, to work on homework with other students in the course. But when solutions are written up, this should be done alone and without the help of other students. Students are required to specify on their writeups which students that collaborated with. If we find solutions that appear even remotely to have been copied, these will be given a zero and the students will be notified.

## Reading

Readings will be assigned for you to complete *before each lecture*.  All required reading will either be linked to here or posted to canvas.  You are not required to purchase a textbook for this course, but you may find the following books helpful.

* Boyd & Vandengerbhe, *Convex Optimization* ([Free PDF](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf))
* Trefethen & Bau, *Numerical Linear Algebra*

## Important Dates

* *(Monday 10/8 &ndash; Tuesday 10/9)*  Fall recess, no class 
* *(Tuesday, 10/16)* **In-class Midterm** (tentative)
* *(Wednesday, 11/21 &ndash; Sun, November 25)* Thanksgiving Holiday
* *(Tuesday, 12/4)* Last day of class
* *(Thursday, 12/6)* **Final Exam** from 2:40-5:30PM

# Homework

* **Homework #1** due Sunday, September 9 @ 11:59pm

# Calendar

<iframe src="https://calendar.google.com/calendar/embed?showPrint=0&amp;showCalendars=0&amp;mode=WEEK&amp;height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=oomfeedqhivsotfkgiqofqjd8s%40group.calendar.google.com&amp;color=%23AB8B00&amp;ctz=America%2FNew_York" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

# Schedule

(Tu 8/21/18) **Lecture #1:  Introduction & Perceptron**

No Required Reading

*Additional Resources*
* CMU 15-859(B), Lecture #4, [The Perceptron Algorithm](https://www.cs.cmu.edu/~avrim/ML10/lect0125.pdf) by Avrim Blum
* Raul Rojas, Neural Networks:  A Systematic Introduction
  * [Ch 4:  Perceptron Learning](https://page.mi.fu-berlin.de/rojas/neural/chapter/K4.pdf)
  * [Ch 5:  Unsupervised Learning and Clustering Algorithms](https://page.mi.fu-berlin.de/rojas/neural/chapter/K5.pdf)
  
(Th 8/23/18) **Lecture #2:  Review of Linear Algebra & Intro to Numpy** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture02_linear-algebra.ipynb))

*Required Preparation before Class*

* Notes, [CS 4540:  Python Basics](https://cs4540-f18.github.io/notes/python-basics)
* Brush up on linear algebra!

*Additional Resources*
* 3blue1brown, [Essence of Linear Algebra](http://www.3blue1brown.com/essence-of-linear-algebra-page/) video series
* [UNSW 2501: Linear Algebra](https://gatech.instructure.com/courses/22666/files/folder/unsw-math2501_linear-algebra-notes) Notes on Canvas
* MIT OCW 18.06 Linear Algebra Lecture Videos

	
(Tu 8/28/18) **Lecture #3:  Convex Geometry** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture03_convex_sets.ipynb))

*Required Preparation before Class*

* Read Boyd & Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)
	* §2.1 Affine and Convex Sets
	* §2.2 Important Examples (of Affine and Convex Sets)
	* §2.5 Separating & Supporting Hyperplanes

*Additional Resources*

* Stanford EE364a, Lecture #2:  Convex Sets ([Slides](http://web.stanford.edu/class/ee364a/lectures/sets.pdf), [Video](https://www.youtube.com/watch?v=P3W_wFZ2kUo))
* Jeffe, UIUC Computational Geometry, ["Lecture 1:  Convex Hulls"](http://jeffe.cs.illinois.edu/teaching/compgeom/notes/01-convexhull.pdf)
* Lauritzen, *Lectures on Convex Sets*, [Ch 3: Separation](https://www.fmf.uni-lj.si/~lavric/lauritzen.pdf) (nice proof of Farkas lemma)
* ETH Zürich, Approximate Methods in Geometry, ["Chapter 1:  Some Basic Geometry"](https://www.ti.inf.ethz.ch/ew/lehre/ApproxGeom08/notes/01_Basic_Geometry.pdf)
* David L. Finn, Rose-Hullman MA 323, ["Barycentric Coordinates & de Casteljau's Algorithm"](https://www.rose-hulman.edu/~finn/CCLI/Notes/day11.pdf)

(Th 8/30/18) **Lecture #4:  Review of Multivariable Calculus** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture04_convexity_multivariable_calculus.ipynb))



*Required Preparation before Class*
* Brush up on single and multivariable calculus!
	* Sequences, series, and limits
	* Chain rule, product rule, quotient rule
	* Mean value theorem, intermediate value theorem
	* Taylor series

*Additional Resources*
* Randal J. Barnes, ["Matrix Differentiation"](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf)
* Parr & Howard 2018, ["The Matrix Calculus You Need for Deep Learning"](https://arxiv.org/abs/1802.01528)
* Petersen & Pedersen 2012, ["The Matrix Cookbook"](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)
* 3blue1brown YouTube Channel
	* Essence of Calculus #4, ["Visualizing the chain rule and product rule"](https://www.youtube.com/watch?v=YG15m2VwSjA)
	* Essence of Calculus #6, ["Implicit Differentiation, what's going on here?"](https://www.youtube.com/watch?v=qb40J4N1fa4)
	* ["What they won't teach you in Calculus"](https://www.youtube.com/watch?v=CfW845LNObM&t=241s)

(Tu 9/4/18) **Lecture #5:  Convex Functions & Intro to Optimization** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture05_convex-functions.ipynb))

*Required Preparation before Class*
 
* Boyd & Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)
	* §3.1 Basic Properties & Examples of Convex Functions
		* Skip §3.1.2 Extended-Value Extensions

*Additional Resources*

* Stanford EE364a, Lecture #3:  Convex Functions ([Slides](http://web.stanford.edu/class/ee364a/lectures/functions.pdf), [Video](https://www.youtube.com/watch?v=kcOodzDGV4c))
* Boyd & Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)
	* §2.3 Operations that Preserve Convex Sets
	* §3.2 Operations that Preserve Convex Functions
	* §2.5 Separating & Supporting Hyperplanes

(Th 9/6/18) **Lecture #6:  Linear Programming Introduction** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture06_linear-programming.ipynb))

*Required Preparation before Class*
* Tim Roughgarden, Stanford CS261, [Lecture 7: Linear Programming](http://theory.stanford.edu/~tim/w16/l/l7.pdf) (Pages 1-5)
	* Try to get used to the matrix notation for linear programs!  Think geometrically!

(Tu 9/11/18) **Lecture #7:  Linear Programming Duality** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture07_linear-programming-duality.ipynb))

*Required Preparation before Class*
* Tim Roughgarden, Stanford CS261, [Lecture 8: Linear Programming Duality I](http://theory.stanford.edu/~tim/w16/l/l8.pdf) (Pages 1-6)

*Additional Resources*
* Tim Roughgarden, Stanford CS261, [Lecture 9: Linear Programming Duality II](http://theory.stanford.edu/~tim/w16/l/l9.pdf)
* Jim Burke, University of Washington MATH 407
	* ["Section 1:  Linear Programming"](https://sites.math.washington.edu/~burke/crs/407/notes/section1.pdf)
	* ["Section 2:  Simplex Algorithm"](https://sites.math.washington.edu/~burke/crs/407/notes/section2.pdf)
  
(Th 9/13/18) **Lecture #8:  Positive Definiteness and Gradient Descent Intro** ([Lecture Slides](https://nbviewer.jupyter.org/github/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture08_duality_convexity_PSD.ipynb))

*Required Preparation before Class*
* Jonathan Shewchuk 1994, ["Painless Conjugate Gradient"](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf) (Pages 1-17)
	* We (probably) won't cover Conjugate-Gradient, but these notes are a great intro gradient descent.
	* We'll cover the Jacobi method in more detail later, so don't worry too much about §5.2

(Tu 9/18/18) **Lecture #9:  Gradient Descent for Convex Functions** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture09_gradient-descent.ipynb))

*Required Preparation before Class*
* Jonathan Shewchuk 1994, ["Painless Conjugate Gradient"](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf) (Pages 17-21)
	* Proof of convergence for gradient descent on quadratic forms
* Try to understand the definition of strong convexity in Boyd & Vandenberghe, ["Convex Optimization"](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf) §9.1.2

*Additional Resources*
* Moritz Hardt, UC Berkeley EE227C
	* ["Lecture 2:  Gradient Descent (Non-smooth and smooth)"](https://ee227c.github.io/notes/ee227c-lecture02.pdf)
	* ["Lecture 3:  Gradient Descent (Strongly convex)"](https://ee227c.github.io/notes/ee227c-lecture03.pdf)
	* ["Lecture 4:  Applications of Gradient Descent"](https://ee227c.github.io/notes/ee227c-lecture04.pdf)
* Elad Hazan, ["Introduction to Online Convex Optimization"](http://ocobook.cs.princeton.edu/OCObook.pdf), Chapters 2 & 3

(Th 9/20/18) **Lecture #10:  Stochastic, Accelerated, and Conditional Gradient Descent**  ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture10_gradient-descent-variants.ipynb))

*Required Preparation before Class*
* Elad Hazan, ["Introduction to Online Convex Optimization"](http://ocobook.cs.princeton.edu/OCObook.pdf), §7.1-7.4
	* Understand Frank Wolfe (a.k.a. conditional gradient) at a high-level
	* Compare the structure of the convergence proof to that of gradient descent from Lecture 9

*Additional Resources*
* Fabian Pedrigosa, ["Notes on the Frank Wolfe Algorithm"](http://fa.bianp.net/blog/2018/notes-on-the-frank-wolfe-algorithm-part-i/)
* Moritz Hardt, UC Berkeley EE227C, ["Lecture 5:  Conditional Gradient Method"](https://ee227c.github.io/notes/ee227c-lecture05.pdf)

(Tu 9/25/18) **Lecture #11:  Applications of Gradient Descent** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture11_gradient-descent-applications.ipynb))

*Required Preparation before Class*
* No new reading for today!  We'll talk about Frank-Wolfe, so remind yourself about the reading from L10.

*Additional Resources*
* Gabriel Goh, *Distill*, ["Why Momentum Really Works"](https://distill.pub/2017/momentum/)
* Moritz Hardt, ["The Zen of Gradient Descent"](http://blog.mrtz.org/2013/09/07/the-zen-of-gradient-descent.html)
* Peter Absil, "Optimization on Matrix Manifolds" [slides](https://perso.uclouvain.be/pa.absil/Talks/IAP_Study_Day_070416_oom_03.pdf) (and [book](https://press.princeton.edu/titles/8586.html))

(Th 9/27/18) **Lecture #12:  Second-order Methods & Fixed Point Iteration** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture12_fixed-points-newton.ipynb))

*Required Preparation before Class*
* Sauer, [*Numerical Analysis*](https://gatech.instructure.com/courses/22666/files/folder/reading?preview=1371975) (posted to Canvas)
	* §1.1 The Bisection Method (Pages 25-29)
	* §1.2 Fixed Point Iteration (Pages 30-40)
	* §1.4 Newton's Method (Pages 51-58)
* Review the following topics from multivariable calculus:
	* Multivariate Taylor's Theorem
	* Mean / Intermediate Value Theorems
	
*Additional Resources*
* Newton's Method
	* Boyd & Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf), §9.5 Newton's Method
	* Chris Hauser, ["Multivariate Newton's Method and Quasi-Newton"](http://homes.sice.indiana.edu/classes/spring2012/csci/b553-hauserk/newtons_method.pdf)
	* Wei-Ta Chu 2014, ["Multivariate Newton's Method"](https://www.cs.ccu.edu.tw/~wtchu/courses/2014s_OPT/Lectures/Chapter%209%20Newton%27s%20Method.pdf) (slides)
	* Ryan Tibshirani 2015, ["Newton's Method"](http://www.stat.cmu.edu/~ryantibs/convexopt-F15/lectures/14-newton.pdf) (slides)
	* Sean Harrington, ["Solving Logistic Regression with Newton's Method"](https://thelaziestprogrammer.com/sharrington/math-of-machine-learning/solving-logreg-newtons-method) (blog post; we'll cover logistic regression later)
* Newton Fractals
	* Simon Tatham, ["Fractals Derived from Newton-Raphson Iteration"](https://www.chiark.greenend.org.uk/~sgtatham/newton/)
	* Daniel Dreibelbis, ["Newton Fractals"](https://www.unf.edu/~ddreibel/teaching/newton/index.html)
	* Paul Bourke, ["An Introduction to Fractals"](http://paulbourke.net/fractals/fracintro/)
* Geoffrey Hinton, Coursera NNML, ["A Brief Overview of Hessian-Free Optimization"](https://www.youtube.com/watch?v=iJ67SnPHEnU)
* Nykamp DQ, *Math Insight*, ["Introduction to Taylor's Theorem for Multivariable Functions"](https://mathinsight.org/taylors_theorem_multivariable_introduction)
* Sauer, *Numerical Analysis* §1.3 briefly covers of conditioning / sensitivity, but we won't focus on these topics in class.  For a slightly more advanced treatment, see Trefethen & Bau, *Numerical Linear Algebra* §13-14.

(Tu 10/2/18) **Lecture #13:  Matrix Decompositions & SVD** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture13_matrix-decompositions.ipynb))

*Required Preparation before Class*
* Trefethen & Bau, [*Numerical Linear Algebra*](https://gatech.instructure.com/courses/22666/files/folder/reading?preview=1372008) (posted to Canvas)
	* Lecture 4:  The Singular Value Decomposition (Pages 25-31)
	* Lecture 5:  More on the SVD (Pages 32-37)

*Additional Resources*

(Th 10/4/18) **Lecture #14:  Numerical Methods for Linear Systems** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture14_linear-systems.ipynb))

*Required Preparation before Class*
* Understand §5.1-5.3 of Shewchuk, ["Painless Conjugate Gradient"](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf)
* Understand the [Gershgorin Circle Theorem](https://en.wikipedia.org/wiki/Gershgorin_circle_theorem) (Wikipedia's proof isn't too bad!)

*Additional Resources*
* Golub & van Loan, *Matrix Computations*, ["§11.2:  The Classical Iterations"](https://gatech.instructure.com/courses/22666/files/folder/reading?preview=1485926) (posted to Canvas)
* Volker John, ["Ch 3:  Classical Iterative Schemes"](https://www.wias-berlin.de/people/john/LEHRE/NUMERIK_II/linsys_3.pdf)
* Schonlieb, "Numerical Analysis" Lectures [16](http://www.damtp.cam.ac.uk/user/cbs31/Teaching_files/c16.pdf), [17](http://www.damtp.cam.ac.uk/user/cbs31/Teaching_files/c17.pdf), [18](http://www.damtp.cam.ac.uk/user/cbs31/Teaching_files/c18.pdf)
* Gilbert Strang, *Mathematical Methods for Engineers*, [§6.2:  Iterative Methods](https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/readings/am62.pdf)

(Th 10/11/18) **Lecture #15:  Numerical Methods for Computing Eigenvalues** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture15_eigenvalues-eigenvectors.ipynb))

*Required Preparation before Class*
* Trefethen & Bau, [*Numerical Linear Algebra*](https://gatech.instructure.com/courses/22666/files/folder/reading?preview=1485844) (posted to Canvas)
	* Lecture 27:  Rayleigh Quotient, Inverse Iteration (Pages 202-210)
	
*Additional Resources*
* Trefethen & Bau, [*Numerical Linear Algebra*](https://gatech.instructure.com/courses/22666/files/folder/reading?preview=1485844) (posted to Canvas)
	* Lecture 25:  Overview of Eigenvalue Algorithms (read if you want some more context about computing eigenvalues) 
	* Lecture 28:  QR Algorithm without Shifts (we won't cover this, but the algorithm is interesting!)

(Tu 10/16/18) **Lecture #16:  Random Variables and Maximum Likelihood Estimation** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture16_random_variables_maximum_likelihood.ipynb))

*Required Preparation before Class*
* Maleki and Do, Stanford Lecture Notes, [*Review of Probability Theory*](http://cs229.stanford.edu/section/cs229-prob.pdf)
	* Brush up on your probability theory, and make sure you understand the distributions *Binomial, Bernoulli, Poisson, Exponential, and Gaussian*

* Zheng, Missouri State Lecture Notes, [*Maximum Likelihood Estimation*](http://people.missouristate.edu/songfengzheng/Teaching/MTH541/Lecture%20notes/MLE.pdf)
	* Read through pages 1-7

(Th 10/25/18) **Lecture #17:  Bayes Rule, Binomial, Regression, MAP Estimation** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture17_NaiveBayes.ipynb))

*Required Preparation before Class*
* Kevin Murphy, ["Machine Learning:  A Probabilistic Perspective"](https://gatech.instructure.com/courses/22666/files/folder/reading?preview=1725476) book (on Canvas)
	* §2.2:  Probability Review (esp §2.2.3)
	* §2.3.1-2.3.2:  Binomial, Bernoulli, Multinomial, and Multinoulli distributions
	* §3.2:  Bayesian Concept Learning
	* §3.5:  Naive Bayes Classifiers
	* Make sure you understand Bayes rule well by working out examples.

(Tu 10/30/18) **Lecture is Cancelled**
	

(Th 11/1/18) **Lecture #18:  Beta-Binomial model, Conjugate Prior, Naive Bayes** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture18_NaiveBayes_Beta_Binomial.ipynb))

*Required Preparation before Class*
* Dan Navarro, Amy Perfors [In Introduction to the Beta-Binomial Model](https://compcogscisydney.org/ccs/technote_betabinomial.pdf) 


(Tu 11/6/18) **Lecture #19:  Logistic Regression Model** ([Lecture Slides](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture19_NB_Bet_LogisticReg.ipynb))

*Required Preparation before Class*
* Charles Elkan [Maximum Likelihood, Logistic Regression,
and Stochastic Gradient Training](http://cseweb.ucsd.edu/~elkan/250B/logreg.pdf)
    * You only need to read through the first 7 pages, although you are welcome to continue!


(Th 11/8/18) **Lecture #20:  Clustering** ([Lecture Slides ](https://github.com/cs4540-f18/cs4540-f18.github.io/blob/master/lectures/cs4540-f18-lecture20_clustering.ipynb))

*Required Preparation before Class*
* Lior Rokach and Oded Maimon [Clustering Methods](https://www.cs.swarthmore.edu/~meeden/cs63/s16/reading/Clustering.pdf)
    * Read Sections 1-4, and Section 5.2

(Tu 11/13/18) **Lecture #21:  Expectation Maximization** ([Lecture Slides - Soon](http://example.com))

*Required Preparation before Class*
* Benjamin Bray [Expectation Maximization](https://github.com/eecs445-f16/umich-eecs445-f16/blob/master/lecture17_clustering-mixtures-em/eecs445-f16-em-notes.pdf)
    * Read pages 1-7

(Th 11/15/18) **Lecture #22:  EM and the Gaussian Mixture Model** ([Lecture Slides - Soon](http://example.com))

*Required Preparation before Class*
* Benjamin Bray [Expectation Maximization](https://github.com/eecs445-f16/umich-eecs445-f16/blob/master/lecture17_clustering-mixtures-em/eecs445-f16-em-notes.pdf)
    * Read pages 8-12
    
(Tu 11/13/18) **Lecture #23:  Exponential Weights Algorithm** ([Lecture Slides - Soon](http://example.com))

*Required Preparation before Class*
* Jacob Abernethy [Online Learning/Exponential Weights](http://web.eecs.umich.edu/~jabernet/eecs598course/fall2015/web/notes/lec16_110515.pdf)

### Tentative Schedule (*read ahead at your own risk!*)

