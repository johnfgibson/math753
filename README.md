# Math 753/853 Introduction to Numerical Methods

University of New Hampshire, fall 2017  
Instructor: John Gibson, john.gibson@unh.edu  
Lecture: MWF 12:40-2:00pm, Kingsbury N129  
Office hours: W 11-12pm, F 2-3pm, Kingsbury N309E, or after class  
Prerequisite: Math 426; Math 445 or CS 410 or IAM 550

**Course description**: Introduction to mathematical algorithms and methods of approximation. A wide survey of approximation methods are examined including, but not limited to, polynomial interpolation, root finding, numerical integration, approximation of differential equations, and techniques used in conjunction with linear systems. Included in each case is a study of the accuracy and stability of a given technique, as well as its efficiency and complexity. It is assumed that the student is familiar and comfortable with programming a high-level computer language. (Also offered as CS 853.)

**Lecture**: You are expected to attend lecture. 10% of your grade will determined by your attendance and participation in class (e.g. asking questions). What you are responsible for understanding is defined by what is covered in lecture. You learn best by giving your undivided attention to the lecture, so private discussion and use of cell phones are strictly prohibited.

**Homeworks**: Homeworks will be posted to the [Math 753 website](https://github.com/johnfgibson/math753/homeworks) most weeks. Homework sets will usually be in form of Julia notebooks, which you modify and then return to the instructor, either via email or [git](https://git-scm.com/) (still to be determined). Discussing homework problems with fellow students is fine, but (1) you should make your own best effort before talking with others, (2) you should get help in the form of *ideas* which you then apply to form your own independent solution, (3) you should *never copy others' work*.  

**Exams**: Exams will cover new material since the last exam, except for the final exam, which is comprehensive. Exams will take place during lecture time on the dates specified on the schedule, unless changes are necessitated by snow days or other official University disruptions. Make-up or alternate exams will be given only for participants in scheduled University varsity athletic events and serious illness (e.g. hospitalization). Please notify the instructor in writing during the first week of class of scheduled University events that conflict with scheduled exams. 

**Grades**: Numerical course grades will be determined according to this formula. 

  numerical grade = 10% class participation + 40% homework + 15% exam one + 15% exam two + 20% final exam
  
Final letter grades will follow these ranges, approximately

 letter grade  | A | A- | B+ | B | B- | C+ | C | C- | D | F 
 --------------|---|----|----|---|----|----|---|----|---|--
 numerical grade |  94-100 | 90-94 | 87-90 | 84-87 | 80-84 | 77-80 | 74-77 | 70-74 | 60-70 |  < 60

## Course outline and schedule

1. Julia, Aug 28 -- Sep 8
    - [Why Julia?](https://github.com/johnfgibson/whyjulia)
    - Installation, start-up, usage modes
    - [Numbers and arithmetic](julia-basics/1-Numbers.ipynb)
    - [Vectors, matrices, and arrays](julia-basics/2-Vectors-matrices-arrays.ipynb)
    - [Dot syntax and plotting (Plots version)](julia-basics/3-Dot-syntax-and-plotting-Plots.ipynb) [(PyPlot version)](julia-basics/3-Dot-syntax-and-plotting-PyPlot.ipynb)
    - [Strings, loops, and conditionals](julia-basics/4-Strings-loops-conditionals.ipynb)
    - [Functions](julia-basics/5-Functions.ipynb)
    - [What makes Julia special](julia-basics/6-What-makes-Julia-special.ipynb): Strict typing, type inference, multiple dispatch, and just-in-time compilation.
2. Nonlinear equations, Sep 11 -- Sep 15
    - Bisection
    - Newton's method
    - [Secant method](lectures/09-Secant-method.ipynb)
3. Finite-precision mathematics, Sep 18 -- Oct 2
    - [Motivation: a failed secant search](lectures/10-Failed-secant-search.ipynb)
    - Floating-point numbers
    - Floating-point arithmetic
    - Conditioning, stability, accuracy
* **Exam 1, Wed Oct 4 in class.** Nonlinear equations and finite-precision math
4. Linear algebra, Oct 6 -- Oct 13
    - norms, orthogonality
    - conditioning of matrices
    - QR decomposition
    - least squares problems
5. Polynomials, Oct 16 -- Oct 20
    - Horner's method, with and without base points
    - Lagrange interpolating polynomial
    - Vandermonde matrices
    - Newton divided differences
6. Least-squares models, Oct 23 -- Oct 27
    - Least-squares polynomial models
    - Least-squares linearized models
7. Multidimensional nonlinear systems Oct 30 -- Nov 3
    - Newton method for systems of nonlinear equations
    - Gauss-Newton method for nonlinear least-squares
8. Numerical differentiation and integration, Nov 6 -- Nov 13
    - Finite differencing
    - Quadrature
* **Exam 2, Wed Nov 15 in class.** Polynomials, least-squares models, multi-d nonlinear systems
9. Ordinary differential equations, Nov 15 -- Nov 29
    - Forward Euler
    - Backward Euler
    - Midpoint method
    - Runge-Kutta methods
10. Partial differential equations, Dec 1 -- Dec 8
    - heat equation, implicit versus explicit
    - Kuramoto-Sivashinky equation: operator splitting, spectral methods


**Final exam, Dec 13, 2017 10:30am-12:30pm Kingsbury N129**
1. Finite precision mathematics
   - machine epsilon
   - rounding
   - finite-precision arithmetic
2. Nonlinear equations
   - 1-d bisection method, 1-d and multi-d Newton method
   - formulae, algorithms, derivation
   - convergence rates
   - requirements, advantages, disadvantages
3. Polynomials
   - Horner's method
   - Lagrange interpolating polynomial
   - Newton divided differences
   - Vandermonde matrices
4. Nonlinear models
   - y=c exp(at), y = ct^n, y = c t exp(at)
   - linearization of above
   - solution for constants via Ax=b problem
   - Gauss-Newton method for nonlinear least-squares
5. Ordinary differential equations
   - explicit methods: forward Euler, midpoint method, and 4th-order Runge-Kutta
   - implicit methods: backward Euler, implicit trapezoid
   - formulae and global error order of above
   - difference between implicit and explicit methods, pros and cons
   - stiff equations, what are they?
   

**Accommodations for disabilities**: According to the Americans with Disabilities Act (as amended, 2008), each student with a disability has a right to request services from UNH to accommodate his or her disability. If you are a student with a documented disability or believe you may have a disability that requires accommodations, please contact [Student Accessibility Services (SAS)](http://www.unh.edu/studentaccessibility), 201 Smith Hall. Accommodations letters are created by SAS with the student. Please follow up with your instructor as soon as possibile to ensure timely implementation of the identified accommodations in the letter. Faculty have an obligation to respond once they receive official notice of accommodations from SAS, but they are under no obligation to provide retroactive accommodations. 

