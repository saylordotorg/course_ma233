**Unit 2: The Greatest Common Divisor** <span id="2"></span> 
*Even when an integer is not prime, it can still behave in a prime-like
fashion with many other integers. We call two integers that act this
way* **relatively prime***. This concept is as important to elementary
number theory as the notion of prime numbers, and it depends entirely on
the* **greatest common divisor** *of the two integers in question,
abbreviated as their* **gcd***. A surprisingly efficient method to
compute the gcd is due to the same Euclid who showed us earlier that
there are infinitely many primes, and we will study it here in some
detail.*  
  
 *We next turn to the topic of **linear Diophantine equations**. These
are basically the same linear equations that you studied in precalculus,
but with a twist: we only want integer solutions. This greatly restricts
what we can do, but the gcd provides a criterion for when a linear
Diophantine equation can be solved, and the Euclidean algorithm – which
we need to compute the gcd anyway – provides a splendid technique for
solving them. This leads us to **Bezout’s identity**, which “turns the
tables” on these relationships and provides a powerful tool for
subsequent units.*

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   define the greatest common divisor (gcd) and identify important
    properties of the gcd;
-   compute the gcd of two integers using the Euclidean Algorithm and
    predict how many steps it will take;
-   explain why there are infinitely many prime numbers in arithmetic
    sequences with a certain property defined by the gcd;
-   determine which linear Diophantine equations have solutions and
    solve them; and
-   use the Extended Euclidean Algorithm to write the gcd in terms of
    Bezout’s identity.

**2.1 The Greatest Common Divisor** <span id="2.1"></span> 
**2.1.1 Definition and Elementary Properties** <span id="2.1.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.5: The Greatest Common Divisor”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.5: The Greatest Common
    Divisor”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 1.5: The Greatest Common Divisor” on
    pages 21-24.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - GCD Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - GCD
    Exercises”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1, 3, 4, 5, and 6 on page 25.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**2.1.2 Dirichlet’s Theorem** <span id="2.1.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory: Section 2.4.1: The Fundamental Theorem of Arithmetic
    and Section 2.4.2: More on the Infinitude of Primes”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory: Section 2.4.1: The Fundamental Theorem of Arithmetic and
    Section 2.4.2: More on the Infinitude of
    Primes”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Reread “Section 2.4.1: The Fundamental Theorem of
    Arithmetic” on pages 41–44. Then read “Section 2.4.2: More on the
    Infinitude of Primes” on pages 45-46.  
      
     Reading these sections, taking notes, and studying the examples
    should take approximately 1 hour.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Infinitude of Primes Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Infinitude of Primes
    Exercise”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 4 on page 46.  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take approximately 15 minutes.

**2.2 The Euclidean Algorithm** <span id="2.2"></span> 
**2.2.1 Statement of the Algorithm and Some Examples** <span
id="2.2.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.6: The Euclidean Algorithm”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.6: The Euclidean
    Algorithm”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf#_blank)
    (PDF)  
      
     Instructions: Read “Section 1.6: The Euclidean Algorithm” on pages
    25-28. Be sure to follow the examples carefully!  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Euclidean Algorithm Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Euclidean Algorithm
    Exercises”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 2, 3, 4, and 5 on pages 28–29.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**2.2.2 “How Much Time Do I Have To Waste On This?” An Analysis of the
Algorithm’s Efficiency** <span id="2.2.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.7.1: Lame’s Theorem”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.7.1: Lame’s
    Theorem”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 1.7.1: Lame’s Theorem” on pages
    29-31.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Upper Bound Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Upper Bound
    Exercises”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 3 and 4 on page 34.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes.

**2.2.3 Binet’s Formula and the Golden Ratio** <span id="2.2.3"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 1.7.2: Binet’s Formula”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 1.7.2: Binet’s
    Formula”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 1.7.2: Binet’s Formula” on pages
    31–34.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Binet’s Formula Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Binet’s Formula
    Exercises”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 5 and 6 on page 34.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes.

**2.2.4 The Lucas Sequence (Optional)** <span id="2.2.4"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Lucas Sequence Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Lucas Sequence
    Exercise”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 7 on page 34.  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**2.3 Linear Diophantine Equations** <span id="2.3"></span> 
**2.3.1 Definition and Criterion for Solvability** <span
id="2.3.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.6: Linear Diophantine Equations”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.6: Linear Diophantine
    Equations”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 2.6: Linear Diophantine Equations” on
    pages 49-51.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Linear Diophantine Equation Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Linear Diophantine Equation
    Exercises”](http://www.saylor.org/site/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1, 2, and 4 on page 51.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**2.3.2 Sage Lab: “Visualizing the Solutions to Linear Diophantine
Equations”** <span id="2.3.2"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Visualizing
    Solutions to Linear Diophantine Equations”**
    Link: The Saylor Foundation’s Sage Lab: [“Visualizing Solutions to
    Linear Diophantine
    Equations”](http://www.saylor.org/site/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked set of labs. Upload the second
    one (2.3.2-SageWS2.sws) to the Sage website where you created an
    account (subunit 1.4.2). Work through the lab carefully.  
      
     Completing this assignment should take approximately 30 minutes.


