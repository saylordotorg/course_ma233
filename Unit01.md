---
layout: default
title: "MA233: Elementary Number Theory"
course_description: "A detailed introduction to the study of integers, including their fundamental properties and ways to represent numbers."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Prime Numbers** <span id="1"></span> 
*One of the greatest mathematicians of all time, C. F. Gauss, remarked
that “Mathematics is the queen of the sciences, and number theory is the
queen of mathematics”; we would modify this only by adding that, “prime
numbers are the queen of number theory.” Indeed, the major goal of this
unit is to introduce you to the* **prime numbers***, a powerful tool
that we rely on repeatedly throughout the course. We have no doubt that,
as you close the metaphorical book on the final unit, you will agree
with our addendum to Gauss’s observation.*  
    
 *As this is a theoretical course, we are interested more in precision
and properties than in computation. It is very easy to be led astray by
vague notions – historically, incorrect assertions in number theory are
due precisely to this fact – so we need to make our ideas precise. You
will find much of the material in the first two sections familiar, as
you have seen them in MA111 and MA231. By and large, the numbers that we
study in elementary number theory are those obtainable by performing
simple operations on the integers, so we start with a review of the
structure of the integers: their* **ring properties***, their*
**orderings***, and* **mathematical induction***. The property of being
prime, called* **primality***, is related to factorization, which is
related to* **divisibility***. This requires us to precede our
investigation of primality with a precise investigation of what it means
to divide two integers; it may surprise you that, in this course, we
almost never pay attention to the quotient, but focus instead on the
remainder.*  
    
 *With the review out of the way, we turn to the* **Fundamental Theorem
of Arithmetic***, which states that every integer larger than 2 can be
written as a product of prime numbers in exactly one way. We show this
in two different ways, then take a look at the question, “Just how many
primes are there, anyway?” It turns out that there are infinitely many,
but whether this is more interesting than the reason why is debatable.
Mathematicians like to say that if God had a book that contained the
most elegant proofs ever written, Euclid’s solution to this question
would surely take its place among them. We also ask, “How many prime
numbers can we find, up to a certain size?” Alas, a proof would take us
beyond elementary number theory, so we omit it – but the result is still
worth discussing.*

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   identify the properties of a ring;
-   distinguish some orderings as linear or well;
-   identify and prove patterns in important sequences of numbers, such
    as triangular numbers, square numbers, and Fibonacci numbers;
-   recognize the Golden Ratio and its importance to Fibonacci and Lucas
    numbers;
-   define prime numbers, and identify important properties;
-   explain why there are infinitely many prime numbers; and
-   apply the Sieve of Eratosthenes to identify prime numbers.

**1.1 Integers and Induction** <span id="1.1"></span> 
**1.1.1 Ring Properties of the Integers** <span id="1.1.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Chapter 1: Introduction and Section 1.1: Algebraic
    Operations with Integers”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Chapter 1: Introduction and Section 1.1: Algebraic
    Operations with
    Integers”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: A **ring** is a set with two operations, addition and
    multiplication, that satisfy the ordinary rules of addition and
    multiplication. Read the introduction to chapter 1 and “Section 1.1:
    Algebraic Operations with Integers” on pages 7–10 to re-familiarize
    yourself with the properties of these operations. Despite its
    familiarity, don't rush through it.  
      
     Reading these sections and taking notes should take approximately
    15 minutes.

-   **Assessment: The Saylor Foundation’s “Justification that the
    Additive Inverse of any Element Is Unique”**
    Link: The Saylor Foundation’s [“Justification that the Additive
    Inverse of any Element Is
    Unique”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/1.1.1-AdditiveInverseAssessment-FINAL.pdf)
    (PDF)  
        
     Instructions: This first assessment gives a gentle introduction. We
    have outlined a proof that the additive inverse of any element of a
    ring is unique. This proof applies not only to the integers, but to
    *any* ring. We have left some spaces blank. Fill in those spaces
    with the appropriate property listed in the reading. You need not be
    quite so pedantic when completing most of the assessments in this
    course, but the problem itself illustrates how often we glide over
    the seemingly obvious and why you should try to be careful when
    doing assessments like these.  
        
     Completing this assessment should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Rings and Fields Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Rings and Fields
    Exercise”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercise 1 on page 10.  
        
     After attempting Exercise 1 assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assignment should take approximately 15 minutes.

**1.1.2 Well Orderings** <span id="1.1.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.2.1: The Well Ordering Principle”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.2.1: The Well Ordering
    Principle”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 1.2.1: The Well Ordering Principle” on
    page 11.  
        
     Reading this section and taking notes should take less than 15
    minutes.

-   **Reading: Citizendium: “Countable Set: Rational Numbers”**
    Link: Citizendium: [“Countable Set: Rational
    Numbers”](http://en.citizendium.org/wiki/Countable_set) (HTML)  
        
     Instructions: Read the Section on Rational Numbers carefully, as
    you will need it for the next assessment.  
        
     Reading this webpage, taking notes, and studying the proof should
    take approximately 15 minutes.  
        
     This resource is licensed under a [Creative Commons
    Attribution-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-sa/3.0/). It is
    attributed to Citizendium.

**1.1.3 Mathematical Induction** <span id="1.1.3"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.2.2: The Pigeonhole Principle and Section
    1.2.3: The Principle of Mathematical Induction”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.2.2: The Pigeonhole Principle and Section 1.2.3:
    The Principle of Mathematical
    Induction”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 1.2.2: The Pigeonhole Principle” and
    “Section 1.2.3: The Principle of Mathematical Induction” on pages
    11–14.  
        
     Reading these sections, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Mathematical Induction Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Mathematical Induction
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 3 and 6 on page 14.  
        
     After attempting Exercises 3 and 6 assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
        
     Completing this assessment should take between 15 minutes and 1
    hour, depending on your comfort level with the material.

**1.1.4 Geometric Numbers** <span id="1.1.4"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 3.1: Geometric Numbers”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 3.1: Geometric
    Numbers”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 3.1: Geometric Numbers” on pages
    57–59.  
        
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Geometric Number Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Geometric Number
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercises 1 and 2 on page 59.  
        
     After attempting Exercises 1 and 2 assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
        
     Completing this assessment should take less than 30 minutes.

**1.2 The Division Algorithm** <span id="1.2"></span> 
**1.2.1 Integer Divisibility** <span id="1.2.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.3.1: Integer Divisibility”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.3.1: Integer
    Divisibility”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 1.3.1: Integer Divisibility” on pages
    15-16.  
        
     Reading this section, taking notes, and studying the examples
    should take less than 15 minutes.

-   **Assessment: The Saylor Foundation’s “Theorem 4: Sketch of Proof of
    Equation (1.6)”**
    Link: The Saylor Foundation’s [“Theorem 4: Sketch of Proof of
    Equation
    (1.6)”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/1.2.1-Sketch1.6Assessment-FINAL.pdf)
    (PDF)  
        
     Instructions: Use induction to show that equation (1.6) on page 16
    of *An Introductory Course in Elementary Number Theory* is true. You
    can use the sketch of the proof, provided at the link.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Divisibility Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Divisibility
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1, 4, 6, 7, 11, and 12 on pages
    17-18. For 6 and 7, use the forms of even and odd numbers given in
    Example 3 on page 15.  
      
     After attempting the divisibility exercises assigned above, discuss
    your solutions in the course discussion forum. Feel free to respond
    to other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes,
    depending on your comfort level with the material.

**1.2.2 The Division Algorithm** <span id="1.2.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.3.2: The Division Algorithm”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.3.2: The Division
    Algorithm”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 1.3.2: The Division Algorithm” on pages
    16–17.  
        
     Reading this section and taking notes should take less than 15
    minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Division Algorithm Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Division Algorithm
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercises 2 and 3 on page 17.  
        
     After attempting the division algorithm exercises assigned above,
    discuss your solutions in the course discussion forum. Feel free to
    respond to other students’ postings as well. If you haven’t already
    done so, you will need to create a free account at the link above to
    participate in the discussions.  
        
     Completing this assessment should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Divisibility Exercises 5 and 8”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Divisibility Exercises 5 and
    8”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercises 5 and 8 on page 17. It will help
    to divide this problem into three cases, organized by the remainder
    of division of *m* by 3. For each case, write *m* in a form similar
    to that used in Example 3 for even and odd numbers.  
        
     After attempting the divisibility exercises assigned above, discuss
    your solutions in the course discussion forum. Feel free to respond
    to other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
        
     Completing this assessment should take approximately 15 minutes.

**1.3 Definition and Characterization of a Prime Number** <span
id="1.3"></span> 
**1.3.1 Definition via Divisibility (Traditional Definition) and the
Sieve of Eratosthenes** <span id="1.3.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.1: The Sieve of Eratosthenes”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.1: The Sieve of
    Eratosthenes”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 2.1: The Sieve of Eratosthenes” on
    pages 35–37.  
        
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - The Sieve of Eratosthenes Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - The Sieve of Eratosthenes
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercises 1, 3, and 4 on page 37. Exercise
    3 can be resolved by a factorization formula. To best use the hint
    for Exercise 4, try proving the contrapositive.  
        
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
        
     Completing this assessment should take approximately 15 minutes.

**1.3.2 Definition via Division (Euclid’s Criterion)** <span
id="1.3.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.2: Alternate Definition of Prime Number”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.2: Alternate Definition of Prime
    Number”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 2.2: Alternate Definition of Prime
    Number” on pages 38–39.  
        
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

**1.4 Prime Numbers Are the Building Blocks of Integers!** <span
id="1.4"></span> 
**1.4.1 The Fundamental Theorem of Arithmetic: Traditional Proof** <span
id="1.4.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.4: Introduction and Section 2.4.1: The
    Fundamental Theorem of Arithmetic”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.4: Introduction and Section 2.4.1: The
    Fundamental Theorem of
    Arithmetic”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read the introduction to “Section 2.4” on page 41,
    and “Section 2.4.1: The Fundamental Theorem of Arithmetic” on pages
    41–44.  
      
     Reading these sections, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Prime Factorization Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Prime Factorization
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercises 1, 2, and 3 on page 46.  
        
     After attempting the prime factorization exercises assigned above,
    discuss your solutions in the course discussion forum. Feel free to
    respond to other students’ postings as well. If you haven’t already
    done so, you will need to create a free account at the link above to
    participate in the discussions.  
        
     Completing this assessment should take approximately 30 minutes.

**1.4.2 Sage Lab: Introduction to Sage** <span id="1.4.2"></span> 
-   **Web Media: The Sage Foundation’s “The Sage Notebook”**
    Link: The Sage Foundation’s [“The Sage
    Notebook”](http://www.sagenb.org/) (HTML)  
        
     Instructions: Visit The Sage Notebook website, create an account
    for yourself. To create an account you will need to click on the
    Google, Yahoo!, or OpenID buttons.  
        
     After you’ve created an account, go to the Sage guided tour found
    [here](http://www.sagemath.org/doc/tutorial/tour.html) and work
    through the following sections:  

    -   [Assignment, Equality, and
        Arithmetic](http://www.sagemath.org/doc/tutorial/tour_assignment.html)
    -   [Getting
        Help](http://www.sagemath.org/doc/tutorial/tour_help.html)
    -   [Functions, Indentation, and
        Counting](http://www.sagemath.org/doc/tutorial/tour_help.html)
    -   [Basic Algebra and
        Calculus](http://www.sagemath.org/doc/tutorial/tour_algebra.html)
        (Stop once you get to “Solving Differential equations.”)
    -   [Plotting](http://www.sagemath.org/doc/tutorial/tour_plotting.html)
    -   [Some Common Issues with
        Functions](http://www.sagemath.org/doc/tutorial/tour_functions.html)
    -   [Basic
        Rings](http://www.sagemath.org/doc/tutorial/tour_rings.html)
    -   [Linear
        Algebra](http://www.sagemath.org/doc/tutorial/tour_linalg.html)
        (Stop once you get to “Matrix spaces.”)

    Creating an account, reading through the guided tour, and taking
    notes should take approximately 2 hours.  
      
     This resource is licensed under a [Creative Commons Attribution 3.0
    Unported License](http://creativecommons.org/licenses/by/3.0/).
    Attributions can be found
    [here](http://sagemath.org/development-ack.html).

**1.5 How Many Prime Numbers Are There? Absolute and Relative Measures**
<span id="1.5"></span> 
**1.5.1 There Are Infinitely Many Primes** <span id="1.5.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.3: The infinitude of Primes”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.3: The infinitude of
    Primes”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 2.3: The Infinitude of Primes” on pages
    39-40.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 5 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - The Infinitude of Primes Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - The Infinitude of Primes
    Exercises”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Try to do Exercises 1, 3, and 4 on pages 40-41.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes.

**1.5.2 Sage Lab: “Relatively Speaking, How Many Primes Are There?”**
<span id="1.5.2"></span> 
-   **Web Media: The Saylor Foundation’s “Sage Lab: Relatively Speaking,
    How Many Primes Are There?”**
    Link: The Saylor Foundation’s [“Sage Lab: Relatively Speaking, How
    Many Primes Are
    There?”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked set of labs. Upload the first one
    (1.5.2-SageWS1.sws) to the Sage website where you created an account
    (subunit 1.4.2). Work through the lab, trying to guess a formula for
    π(*x*).  
      
     Completing this assignment should take approximately 15 minutes.

**1.5.3 The Prime Number Theorem (Without Proof) and Some Famous
Conjectures Regarding Prime Numbers** <span id="1.5.3"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.8: Theorems and Conjectures Involving
    Prime Numbers”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.8: Theorems and Conjectures Involving Prime
    Numbers”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 2.8: Theorems and Conjectures Involving
    Prime Numbers” on pages 54-56.  
      
     Reading this section, taking notes, and studying the examples
    should take less than 15 minutes.


