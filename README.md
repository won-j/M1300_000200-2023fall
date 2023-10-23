# M1399.000200 Advanced Statistical Computing @ SNU 2023

This is the course website for M1399.000200: "Advanced Statistical Computing " at Seoul National University in Fall 2023. Assignments, lecture notes, and open source code will all be available on this website.

## Announcements

* 2023-10-21: [Candidate papers](./project/project.md) for Final Project is announced.
* 2023-10-19: Homework 2 is announced. Check out Github Classroom.
* 2023-09-19: Homework 1 is announced. Check out Github Classroom.

## Instructor 

Joong-Ho (Johann) Won

**Email**: wonj AT stats DOT snu DOT ac DOT kr

**Class Time**: T/Th 11:00 - 12:15 @ 25-210

**Office Hours**: By appointment.

**Textbook**: There is no required textbook.

**References**: 

- James Gentle, [Computational Statistics](https://link.springer.com/book/10.1007%2F978-0-387-98144-4), 2nd Edition, Springer (2009).
- Gene Golub and Charles Van Loan, [Matrix Computation](https://www.amazon.com/Computations-Hopkins-Studies-Mathematical-Sciences/dp/1421407949/ref=sr_1_1?keywords=matrix+computation+golub&qid=1567157884&s=gateway&sr=8-1), 4th Edition, Johns Hopkins Press (2012).
- Kenneth Lange, [Numerical Analysis for Statisticians](https://link.springer.com/book/10.1007%2F978-1-4419-5945-4), 2nd Edition, Springer (2010).
- Stephen Boyd and Lieven Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/), Cambridge University Press (2004).
- Dimitri P. Bertsekas, [Convex Optimization Theory](http://www.athenasc.com/convexduality.html) Athena Scientific (2009).
	

## Course Objectives

By the end of this course, you will be able to acquire

- basic programming skills using the [Julia programming language](https://julialang.org);
- basic knowledge of computer arithmetic;
- fundamental knowledge of numerical algorithms for statistical computing;
- hands-on knowledge of various optimization problems in statistical computing;
- basic theoretical understanding of mathematical optimization;
- wisdom of how *not* to reinvent the wheel.

## Course Overview

### Assessment

The course will be graded based on the following components:

- **Attendance** (10%): Mandatory.
- **Assignments** (65%): You will be assigned 4 homework assignments to be completed using Julia regularly throughout class. 
- **Final project** (25%): The project will be a reproduction of the code and results in a recent computational statistics research paper chosen by yourself *in Julia* . The ideas for projects will be provided towards the midpoint of the semester.

### Schedule

The following schedule is tentative, and is subject to change over the course.

| Week | Topic | Assignment | Due Date |
| --- | --- | --- | --- | 
| 1 (9/5, 9/7)      | Introduction [[slides](./lectures/01-intro/intro.html)], Julia Intro <!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/02-juliaintro/juliaintro1.ipynb)--> [[notebook](./lectures/02-juliaintro/julia101.ipynb)] [[slides](./lectures/02-juliaintro/julia101.html)] | Julia + Jupyter + Quarto <!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/02-juliaintro/jupyter.ipynb)--> [[notebook](./lectures/02-juliaintro/jupyter.ipynb)] [[html](./lectures/02-juliaintro/jupyter.html)], Plotting <!--[binder](https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/02-juliaintro/juliaplots.ipynb)--> [[notebook](./lectures/02-juliaintro/juliaplots.ipynb)] [[html](./lectures/02-juliaintro/juliaplots.html)]  |  | 
| 2 (9/12, 9/14)    | [Computer Arithmetic]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/03-arith/arith.ipynb)--> [[notebook](./lectures/03-arith/arith.ipynb)] [[slides](./lectures/03-arith/arith.html)] | Homework 1 | 2023-10-04 |
| 3 (9/19, 9/21)    | [Computer Arithmetic]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/03-arith/arith.ipynb)--> [[notebook](./lectures/03-arith/arith.ipynb)] [[slides](./lectures/03-arith/arith.html)], [Algorithm]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/04-algo/algo.ipynb)--> [[notebook](./lectures/04-algo/algo.ipynb)]  [[slides](./lectures/04-algo/algo.html)] |  |  |
| 4 (9/26, ~~9/28~~)    | Numerical Linear Algebra: [intro]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/05-numalgintro/numalgintro.ipynb)--> [[notebook](./lectures/05-numalgintro/numalgintro.ipynb)] [[slides](./lectures/05-numalgintro/numalgintro.html)], [triangular systems]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/06-trisys/trisys.ipynb)--> [[notebook](./lectures/06-trisys/trisys.ipynb)]  [[slides](./lectures/06-trisys/trisys.html)] | Homework 2 | 2023-10-30  |
| 5 (~~10/3~~, 10/5)    | [LU decomposition]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/07-gelu/gelu.ipynb)--> [[notebook](./lectures/07-gelu/gelu.ipynb)] [[slides](./lectures/07-gelu/gelu.html)] [[example](./lectures/07-gelu/gelu.pdf)]  |  |  |
| 6 (10/10, 10/12)  | [Cholesky]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/08-chol/chol.ipynb)--> [[notebook](./lectures/08-chol/chol.ipynb)] [[slides](./lectures/08-chol/chol.html)] | [Final Project Proposal](./project/project.md)  | 2023-11-02  |
| 7 (10/17, 10/19)  | [QR decomposition]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/09-qr/qr.ipynb)--> [[notebook](./lectures/09-qr/qr.ipynb)] [[slides](./lectures/09-qr/qr.html)]  |  |  |
| 8 (10/24, 10/26)  | [Linear regression]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/10-linreg/linreg.ipynb)--> [[notebook](./lectures/10-linreg/linreg.ipynb)] [[slides](./lectures/10-lingreg/linreg.html)], [Iterative methods]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/11-iterative/iterative.ipynb)--> <!--[[notebook](./lectures/11-iterative/iterative.ipynb)]--> [Eigenvalue and singular value decompositions]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/13-eigsvd/eigsvd.ipynb)--> <!--[[notebook](./lectures/13-eigsvd/eigsvd.ipynb)]--> | [Longley Data](./lectures/10-linreg/longley.txt) |  |
| 9 (10/31, 11/2)   | [Introduction to mathematical optimization]<!--(./lectures/14-optmintro/optmintro.html)-->, [Optimization in Julia]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/15-juliaopt/juliaopt.ipynb)--> <!--[[notebook](./lectures/15-juliaopt/juliaopt.ipynb)--> | Homework 3 | 2023-11-25 |
| 10 (11/7, 11/9) | [Linear programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/16-lp/lp.ipynb)--> <!--[[notebook](./lectures/16-lp/lp.ipynb)--> |  |  |
| 11 (11/14, 11/16) | [Quadratic programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/17-qp/qp.ipynb)--> <!--[[notebook](./lectures/17-qp/qp.ipynb)-->, [Second-order cone programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/18-socp/socp.ipynb)--> <!--[[notebook](./lectures/18-socp/socp.ipynb)]-->, [Semidefinite programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/19-sdp/sdp.ipynb)--> <!--[[notebook](./lectures/19-sdp/sdp.ipynb)]--> |  |  |
| 12 (11/21, 11/23) | [Geometric programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/20-gp/gp.ipynb)--> <!--[[notebook](./lectures/20-gp/gp.ipynb)-->, [KKT conditions]<!--(./lectures/21-kkt/kkt.html)--> | [Homework 4]<!--(./hw/hw4/hw04.html)--> <!--[[notebook](./hw/hw4/hw04.ipynb)]--> <!--[[corrupted image]](./hw/hw4/barbara128noisy.png)--> | 2023-12-12 |
| 13 (11/28, 11/30)   | [Newton's method I]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/22-newton/newton.ipynb)--> <!--[[notebook](./lectures/22-newton/newton.ipynb)]-->, [MM algorithms]<!--(./lectures/24-mm/mm.html)-->, [First-order methods]<!--(./lectures/23-first/first.html)--> |  |  |
| 14 (12/5, 12/7)  | [Newton's method II]<!--(./lectures/22-newton/newton_constr.html)-->      |  |  |
| 15 (12/12, 12/14)  | Final Projects      |  |  |


<!--| 2 (9/6, 9/8)     | [Julia Intro II](https://mybinder.org/v2/gh/won-j/M1399_000200-2023fall/master?filepath=lectures/02-juliaintro/juliaintro2.ipynb) [[notebook](./lectures/02-juliaintro/juliaintro2.ipynb)] | [Homework 1](./hw/hw1/hw01.html) [[notebook](./hw/hw1/hw01.ipynb)] | 2023-09-26 | -->
