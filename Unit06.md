---
layout: default
title: "MA233: Elementary Number Theory"
course_description: "A detailed introduction to the study of integers, including their fundamental properties and ways to represent numbers."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: Multiplicative Functions, with Applications** <span
id="6"></span> 
*Our final topic consists of* **multiplicative functions***. We begin,
not with a general analysis of multiplicative functions, but with*
**Euler’s φ*-*function***, which measures how many positive integers are
smaller than a given integer and relatively prime to it. We then
consider the* **sum-of-divisors function σ***. In both cases, we build
up a general method to compute the value of the function, based on how
an integer factors into primes.*  
  
 *As you will see,* φ*and* σ*share a property that allows us to evaluate
them at any integer by factoring it into primes, then evaluating the
function for these primes, or their powers. These functions are easy to
evaluate for prime numbers, which makes it easy to evaluate then for any
integer. After discussing some consequences of this common property, we
discuss two other multiplicative functions of interest.*  
  
 *We finally turn to some applications of multiplicative functions. One
of them is a purely mathematical application: that of computing*
**perfect numbers***, which are the sum of their divisors. You should
already see that the function* σ*is of interest in this case. Perfect
numbers are related to* **Mersenne primes***, which turn out to be very
difficult to come by. In an ironic way, they are even more difficult to
come by than Mersenne himself envisioned! As we're already analyzing the
mistaken claims of a great number of theorists - a phenomenon which
should both inspire and intimidate you - we also discuss the* **Fermat
numbers***, all of which Fermat thought would be prime, but only few
are.*  
  
 *After these diversions inspired by* σ*, we come in a very fitting way
to* φ*, the function that began our investigations of multiplicative
functions. We can use φ to generalize Fermat’s Little Theorem from Unit
3.* **Euler’s Theorem** *essentially shows, yet again, how we can
generalize an idea about numbers that are prime to numbers that are
relatively prime.*  
  
 *A moment ago, we said that these multiplicative functions are easy to
compute once we have a factorization of an integer. Hopefully, you
remember what we said in Unit 1 about factoring: it is a deceptively
simple problem. How deceptive is its simplicity? A trio of
mathematicians formulated an algorithm for private communication whose
security is based entirely on the premise that an eavesdropper could
understand the communication if she could but factor a large integer
into two primes. That’s it! The* **RSA algorithm***, named after its
inventors, thus draws together the main strands of this course into a
tour-de-force of elegant simplicity: prime numbers, the greatest common
divisor, relatively prime numbers, congruence, and multiplicative
functions.*

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   identify the criteria of a multiplicative function, and compute the
    values of such functions for integers that are “easy” to factor;
-   identify important multiplicative functions, especially Euler’s
    φ-function, the sum-of-divisors function σ;
-   describe the relationships between perfect numbers, the σ-function,
    and Mersenne primes;
-   search for large prime numbers using ideas of Mersenne and Fermat;
-   describe how Euler’s φ-function allows us to generalize Fermat’s
    Little Theorem; and
-   describe the mathematical theory of the RSA encryption scheme, and
    successfully encrypt and decrypt short messages using simple
    parameters.

**6.1 Euler’s φ-Function** <span id="6.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 4.2.2: Euler’s φ-Function”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 4.2.2: Euler’s
    φ-Function”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 4.2.2: Euler’s φ-Function” on page
    86.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 5 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Euler’s φ-Function Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Euler’s φ-Function
    Exercise”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 3 on page 86.  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**6.1.1 Sage Lab: “Computing φ(*n*)”** <span id="6.1.1"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Computing φ(*n*)”**
    Link: The Saylor Foundation’s Sage Lab: [“Computing
    φ(*n*)”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked set of labs. Upload the seventh
    one (6.1.1-SageWS7.sws) to the Sage website where you created an
    account (Unit 1.4.2). Work through the lab carefully.  
      
     Completing this assignment should take approximately 30 minutes.

**6.1.2 Computing φ(*n*)** <span id="6.1.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 5.2.1: The Euler φ-Function”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 5.2.1: The Euler
    φ-Function”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 5.2.1: The Euler φ-Function” on pages
    107-110.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - The Euler φ-Function Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - The Euler φ-Function
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1, 3, 5, 6 on pages 112-113.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**6.2 The Sum-of-Divisors Function, σ** <span id="6.2"></span> 
**6.2.1 Sage Lab: “Computing σ(*n*)”** <span id="6.2.1"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Computing σ(n)”**
    Link: The Saylor Foundation’s Sage Lab: [“Computing
    σ(*n*)”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked set of labs. Upload the eight one
    (6.2.1-SageWS8.sws) to the Sage website where you created an account
    (subunit 1.4.2). Work through the lab carefully.  
      
     Completing this assignment should take approximately 30 minutes.

**6.2.2 σ(*p*) When *p* is Prime** <span id="6.2.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 5.2.2: The Sum-of-Divisors Function”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 5.2.2: The Sum-of-Divisors
    Function”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 5.2.2 The Sum-of-Divisors Function” on
    pages 110-111.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Sum-of-Divisors Function Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Sum-of-Divisors Function
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 7 and 8 on page 113. Compute the
    sum of positive divisors only, not the number of divisors; you'll do
    those later.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**6.3 The Common Thread: Multiplicative Functions** <span
id="6.3"></span> 
**6.3.1 Properties of Multiplicative Functions** <span
id="6.3.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Introduction to Chapter 5 and Section 5.1:
    Definitions and Properties”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Introduction to Chapter 5 and Section 5.1: Definitions and
    Properties”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read the introduction to “Chapter 5 Multiplicative
    Number Theoretic Functions” and all of “Section 5.1: Definitions and
    Properties” on pages 103-106.  
      
     Reading these sections, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Multiplicative Functions Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Multiplicative Functions
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1 and 2 on pages 106-107.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 15 minutes.

**6.3.2 Two Other Multiplicative Functions: τ, μ** <span
id="6.3.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 5.2.3: The Number-of-Divisors Function and
    Section 5.3: The Mobius Function and the Mobius Inversion Formula”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 5.2.3: The Number-of-Divisors Function and Section
    5.3: The Mobius Function and the Mobius Inversion
    Formula”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 5.2.3: The Number-of-Divisors Function”
    on pages 111-112 and “Section 5.3: The Mobius Function and the
    Mobius Inversion Formula” on pages 113-116.  
      
     Reading these sections, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Number-of-Divisors and Mobius Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Number-of-Divisors and Mobius
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 7 and 8 on page 113. Compute the
    number of positive divisors only, not the sum of divisors, as you
    already computed them. Then Try to do Exercises 1-3 on page 116.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**6.4 Perfect Numbers** <span id="6.4"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Perfect, Mersenne, and Fermat Numbers, pages
    116-118”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Perfect, Mersenne, and Fermat Numbers, pages
    116-118”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read the beginning of “Section 5.4: Perfect,
    Mersenne, and Fermat Numbers” on pages 116-118 through Theorem 53
    and its proof.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Perfect Numbers Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Perfect Numbers
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1, 3, 4, and 5 on pages
    120-121.  
      
     Instructions: After attempting the exercises assigned above,
    discuss your solutions in the course discussion forum. Feel free to
    respond to other students’ postings as well. If you haven’t already
    done so, you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 15 minutes.

**6.5 Building Big Primes** <span id="6.5"></span> 
**6.5.1 Mersenne Primes and Fermat Numbers, or, How to Get Famous by
Making Mistakes** <span id="6.5.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 5.4 Perfect, Mersenne, and Fermat Numbers”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 5.4 Perfect, Mersenne, and Fermat
    Numbers”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Finish reading “Section 5.4: Perfect, Mersenne, and
    Fermat Numbers” on pages 118-120.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Mersenne Primes and Fermat Numbers Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Mersenne Primes and Fermat Numbers
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 7 and 9 on page 121.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**6.6 Euler’s Theorem** <span id="6.6"></span> 
**6.6.1 Sage Lab: Finding Multiplicative Inverses Modulo *n*** <span
id="6.6.1"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Finding
    Multiplicative Inverses Modulo n”**
    Link: The Saylor Foundation’s Sage Lab: [“Finding Multiplicative
    Inverses Modulo
    *n*”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked set of labs. Upload the ninth one
    (6.6.1-SageWS9.sws) to the Sage website where you created an account
    (subunit 1.4.2). Work through the lab carefully.  
      
     Completing this assessment should take approximately 30 minutes.

**6.6.2 Euler’s Theorem** <span id="6.6.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 4.6: Theorems of Fermat, Euler, and
    Wilson”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 4.6: Theorems of Fermat, Euler, and
    Wilson”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Finish reading “Section 4.6: Theorems of Fermat,
    Euler, and Wilson” on pages 97-100.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Theorems of Fermat, Euler, and Wilson Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Theorems of Fermat, Euler, and Wilson
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1, 3, and 6 on page 101.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes.

**6.7 RSA Encryption** <span id="6.7"></span> 
**6.7.1 Public Key Cryptography** <span id="6.7.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 9.1.1: Public Key Cryptography”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 9.1.1: Public Key
    Cryptography”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 9.1.1: Public Key Cryptography” on
    pages 185-186.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

**6.7.2 How the RSA Algorithm Works** <span id="6.7.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 9.1.2: The RSA Algorithm”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 9.1.2: The RSA
    Algorithm”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 9.1.2: The RSA Algorithm” on pages
    186-189.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 20 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - RSA Algorithm Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - RSA Algorithm
    Exercise”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 1 on page 190.  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**6.7.3 Sage Lab: “Demonstration of RSA”** <span id="6.7.3"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Demonstration of
    RSA”**
    Link: The Saylor Foundation’s Sage Lab: [“Demonstration of
    RSA”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (PDF)  
      
     Instructions: Download the linked set of labs. Upload the last one
    (6.7.3-SageWS10.sws) to the Sage website where you created an
    account (subunit 1.4.2). Work through the lab carefully.  
      
     Completing this assignment should take approximately 30 minutes.

**6.7.4 Is the RSA Algorithm Safe?** <span id="6.7.4"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 9.1.3: Is RSA Safe?”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 9.1.3: Is RSA
    Safe?”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
        
     Instructions: Read “Section 9.1.3: Is RSA Safe?” on pages
    190-191.  
        
     Reading this section, taking notes, and studying the examples
    should take approximately 10 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - RSA Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - RSA
    Exercise”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 1 on page 191. It’s not important
    to solve this problem; what’s important is to see how difficult it
    is!  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take approximately 30 minutes.


