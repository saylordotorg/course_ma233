**Unit 3: Congruence, with Applications** <span id="3"></span> 
*If you weren't already convinced of our claim in Unit 1 that the
remainder is more interesting and useful for number theory than
quotients, then this unit will overwhelm you with evidence.
**Congruence** begins as an innocent-looking relationship based on
divisibility, which itself is a property of the remainder. We quickly
show that this superficial simplicity masks a tool of incredible power.
It determines an equivalence relation, and captures the ring properties
of the integers – but not some other properties of the integers! We call
the concomitant equivalence classes **residues**, and show that it
suffices to perform any arithmetic on the residues by... computing the
remainders!*  
  
 *With some theory out of the way, we turn immediately to applications.
Many interesting problems in the real world can be stated in terms of
linear congruence relations, a disguised form of our recently-acquired
friend, linear Diophantine equations. This provides a method for solving
not only linear congruence relation, but also systems of linear
congruence relations. This latter problem is an ancient one, used in
practical situations by both Chinese and Indian mathematicians, and
enjoys a property called the* **Chinese Remainder Theorem***. We prove
this theorem two different ways; unlike the Fundamental Theorem of
Arithmetic, each proof gives us a practical method for solving the
problems.*  
  
 *Finally, we return to the question of primality, studying congruence
in the context of a prime number. In this case, the residues enjoy the
properties not only of a ring, but of a* **field***, which leads to a
tool for primality testing.*

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   compute canonical residues modulo an integer;
-   identify properties of the integers that apply to congruence, and
    properties that do not;
-   explain rules of divisibility by the integers 2, 3, 4, 5, 6, 7, 8,
    9, 11;
-   use the Chinese Remainder Theorem to solve a system of linear
    congruences;
-   determine when a choice of modulus and residue admits a
    multiplicative inverse for the residue with respect to that modulus,
    and compute the inverse; and
-   test for primality using Fermat’s Little Theorem

**3.1 Congruence** <span id="3.1"></span> 
**3.1.1 Definition, Examples, and Ring Properties of Congruence** <span
id="3.1.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 4.1: Introduction to Congruences”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 4.1: Introduction to
    Congruences”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 4.1: Introduction to Congruences” on
    pages 77–81, through “Example 29.” Stop when you get to “Theorem
    25.”  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Congruence Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Congruence
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1-4 and 6-11 on page 83.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**3.1.2 Review of Equivalence Relations** <span id="3.1.2"></span> 
-   **Reading: Elias Zakon’s “Mathematical Analysis: Volume I”**
    Link: Elias Zakon’s [“Mathematical Analysis: Volume
    I”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Read pages 12-14, starting from the heading
    “Definition 4.”  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Elias Zakon’s “Mathematical Analysis: Volume I -
    Equivalence Relation Exercise”**
    Link: Elias Zakon’s [“Mathematical Analysis: Volume I - Equivalence
    Relation
    Exercise”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Real-Analysis-I-Zakon-1-30-11-OTC.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 8 on page 15.  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take from 15 minutes to 1 hour,
    depending on your comfort level with the material.

**3.1.3 Congruence as an Equivalence Relation** <span
id="3.1.3"></span> 
-   **Assessment: The Saylor Foundation's “Justification that Congruence
    Is a Symmetric Relation”**
    Link: The Saylor Foundation's [“Justification that Congruence Is a
    Symmetric
    Relation”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/3.1.3-Confluence-PartialSolution-FINAL.pdf)
    (PDF)  
      
     Instructions: (1) Show that congruence is an equivalence relation,
    by showing that it satisfies the reflexive, symmetric, and
    transitive properties. (2) Explain what Theorem 2 of Elias Zakon’s
    “Mathematical Analysis: Volume I” implies about congruence
    classes.  
      
     Completing this assessment should take approximately 30 minutes.

**3.1.4 Familiar Properties *Not* Satisfied by Congruence** <span
id="3.1.4"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read pages 81-82, starting immediately after “Example
    29.”  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

**3.1.5 Residue Systems** <span id="3.1.5"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 4.2.1: Residue Systems”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 4.2.1: Residue
    Systems”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 4.2.1 Residue Systems on pages 84-85.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Residue Systems Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Residue Systems
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1 and 2 on page 86.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 15 minutes.

**3.1.6 Sage Lab: “Residue Arithmetic”** <span id="3.1.6"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Residue
    Arithmetic”**
    Link: The Saylor Foundation’s Sage Lab: [“Residue
    Arithmetic”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked set of labs. Upload the third one
    (3.1.7-SageWS3.sws) to the Sage website where you created an account
    (subunit 1.4.2). Work through the lab carefully.  
      
     Completing this assignment should take approximately 30 minutes.

**3.1.7 The Secret Life of Linear Congruence Relations (Linear
Diophantine Equations)** <span id="3.1.7"></span> 
*A* **linear congruence relation** *has the form* ax ≡ b (mod m)*,
where* a*and* b*are known constants, while* x*is the unknown variable.
By the definitions of congruence and divisibility, we must be able to
find an integer* q*such that* ax – b = mq*. Let* y = -q*, and we can
rewrite this equation as*  
  
 ax + my = b  
  
 *called a* **Diophantine equation***. (The variables* x*and* y*are to
the first degree, so we call it a* **linear** **Diophantine
equation***.) Diophantine equations have a long, storied history in
number theory, and some of number theories most important problems have
been Diophantine equations. We would like to solve these sorts of
equations, in part because, for now, we should like to solve linear
congruence relations, but later there will be other applications, as
well. As you will see,* *you already knowhow to solve these equations!*

-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 2.6: Linear Diophantine Equations”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 2.6: Linear Diophantine
    Equations”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Reread “Section 2.6 Linear Diophantine Equations on
    pages 49–51. If you are still familiar with this material, you can
    skip to the next reading.  
      
     Rereading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Linear Congruences”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Linear
    Congruences”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 4.3 Linear Congruences” on pages
    81-82.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Linear Congruence Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Linear Congruence
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1-4 on pages 88-89.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 1 hour.

**3.2 The *Other* Sun Tzu’s “Art of War”** <span id="3.2"></span> 
**3.2.1 The Chinese Remainder Theorem** <span id="3.2.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Introduction to Section 4.4: The Chinese Remainder
    Theorem and Section 4.4.1: Direct Solution”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Introduction to Section 4.4: The Chinese Remainder Theorem
    and Section 4.4.1: Direct
    Solution”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read the introduction to “Section 4.4: The Chinese
    Remainder Theorem” and all of “Section 4.4.1: Direct Solution” on
    pages 89-91.  
      
     Reading these sections, taking notes, and studying the examples
    should take approximately 30 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Coursein Elementary
    Number Theory - Chinese Remainder Theorem Direct Solution
    Exercises”**
    Link: Wissam Raji’s [“An Introductory Coursein Elementary Number
    Theory - Chinese Remainder Theorem Direct Solution
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1-3 on page 91.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes.

**3.2.2 Incremental Solution** <span id="3.2.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 4.4.2: Incremental Solution”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 4.4.2: Incremental
    Solution”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 4.4.2: Incremental Solution” on pages
    91-92.  
      
     Reading this section, taking notes, and studying the examples
    should take approximately 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Chinese Remainder Theorem Incremental Solution
    Exercises”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Chinese Remainder Theorem Incremental Solution
    Exercises”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercises 1-3 on page 92.  
      
     After attempting the exercises assigned above, discuss your
    solutions in the course discussion forum. Feel free to respond to
    other students’ postings as well. If you haven’t already done so,
    you will need to create a free account at the link above to
    participate in the discussions.  
      
     Completing this assessment should take approximately 30 minutes.

**3.2.3 Sage Lab: “Chinese Remainders and Polynomial Factorization”**
<span id="3.2.3"></span> 
-   **Web Media: The Saylor Foundation’s Sage Lab: “Chinese Remainders
    and Polynomial Factorization”**
    Link: The Saylor Foundation’s Sage Lab: [“Chinese Remainders and
    Polynomial
    Factorization”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/MA233-SageWorksheets.zip)
    (Sage)  
      
     Instructions: Download the linked lab. Upload the fourth one
    (3.2.3-SageWS4.sws) it to the Sage website where you created an
    account (subunit 1.4.2). Work through the lab carefully.  
      
     Completing this assignment should take approximately 30 minutes.

**3.3 Primality Testing and Fermat’s Little Theorem** <span
id="3.3"></span> 
**3.3.1 Field Properties of Congruence Modulo *p*** <span
id="3.3.1"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Introduction to Section 4.5: Field Properties of
    Residues Modulo a Prime, and a Primality Test and Section 4.5.1:
    When Is a System of Residues a Field?”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Introduction to Section 4.5: Field Properties of Residues
    Modulo a Prime, and a Primality Test and Section 4.5.1: When Is a
    System of Residues a
    Field?”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read the introduction to “Section 4.5: Field
    Properties of Residues Modulo a Prime, and a Primality Test” and all
    of “Section 4.5.1: When Is a System of Residues a Field? on pages
    93-96.  
      
     Reading these sections, taking notes, and studying the examples
    should take approximately 30 minutes.

**3.3.2 Fermat’s Little Theorem as a Test for Primality** <span
id="3.3.2"></span> 
-   **Reading: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Section 4.5.2: Fermat’s Little Theorem as a
    Primality Test”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Section 4.5.2: Fermat’s Little Theorem as a Primality
    Test”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Read “Section 4.5.2: Fermat’s Little Theorem as a
    Primality Test” on page 96.  
      
     Reading this section, taking notes, and studying the examples
    should take less than 15 minutes.

-   **Assessment: Wissam Raji’s “An Introductory Course in Elementary
    Number Theory - Fermat’s Little Theorem Exercise”**
    Link: Wissam Raji’s [“An Introductory Course in Elementary Number
    Theory - Fermat’s Little Theorem
    Exercise”](https://resources.saylor.org/archived/wp-content/uploads/2014/05/An-Introductory-Course-in-Elementary-Number-Theory.pdf)
    (PDF)  
      
     Instructions: Try to do Exercise 1 on page 96.  
      
     After attempting the exercise assigned above, discuss your solution
    in the course discussion forum. Feel free to respond to other
    students’ postings as well. If you haven’t already done so, you will
    need to create a free account at the link above to participate in
    the discussions.  
      
     Completing this assessment should take approximately 15 minutes.


