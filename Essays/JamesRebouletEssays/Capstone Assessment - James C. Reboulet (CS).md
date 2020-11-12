# **Capstone Assessment - Debugger Application**
## *James C. Reboulet (CS)*
## **Purpose of Embarking on this Capstone Project**
##### From my academic perspective and all of the time that I have spent in the realm of academia, this senior design project is about taking the theoretical knowledge of how computers work from a mathematical, logical, hardware, and software perspective, and applying that knowledge in the creation of a concrete project, that will also allow me to gain additional skills in potentially learning a new programming language or framework, and will allow me to review previous skills that I have learned throughout the four years that I have been at the University of Cincinnati.  I have learned over my many years in college that I have probably forgotten almost as much as I have learned and the only way to actually learn anything in a math, science, or programming course is to practice, persist, work problems, and to continually review the concepts that have been presented in previous courses, in order to reinforce those concepts and to ensure that they are not completely forgotten.  I hope that this project will also allow me to improve on those concepts in my previous courses that I may have struggled to learn and that may have not made complete sense, except at a level that was required to be successful on a particular assignment or exam, and to reinforce those concepts or to gain a more in-depth knowledge of those concepts.  The purpose of my coursework and my academic preparation, from my perspective, is to hopefully be exposed to enough content in the many areas of computer science and mathematics, so that the theoretical knowledge will allow me to more easily learn the skills that are applicable to my area of employment in the future.  I am sure that when I graduate and apply for a position, there will be many languages and concepts are specific to a given company that are new to me.  Hopefully, since I have been exposed to them throughout my academic experience, I will be able to acquire those skills more rapidly and be able to use that knowledge to excel at my position and successfully contribute to improving a company’s processes and their software.  I hope that this project will be a starting point on that path.
## **Contribution of Collective College Experience to this Project**
##### During my time, studying Computer Science at UC and from my previous experience as a transfer student from Miami University in Computer Science, I have gained a great deal of theoretical and technical skills that I can hopefully apply to this capstone project.  I have had a great deal of experience with object-oriented programming concepts (classes – super and subclasses, inheritance, polymorphism, interfaces, abstract classes, methods, and references/pointers) in the Java-based Abstract-Data Structures course that I took at Miami University (CSE 271) and the Computer Science I course (CS1021C) that I took at UC.  The Data Structures course that I took at Miami University, which was Java based (UC equivalent, CS2028C) also gave me knowledge of linked lists, binary-search trees, stacks, cues, basic recursion, vectors, and generic classes which are applicable to many imperative programming languages and will be applicable to the creation of a debugging application in this project.  The Python programming course (CS2021) not only helped me increase my knowledge of Python, but it also exposed me to some of the unique features in Python such as higher-order functions, easy swapping by using statements such as “a,b = a + b”; which places the previous values of a and (a+b) on the right into the current values of a and b on the left to shorten the number of swapping instructions, and I also gained knowledge of how to use lambda functions and improved my knowledge of writing recursive methods to access embedded linked-lists of unknown size – not to the user, but to the interpreter in Python, such as ([a,b[d,e,[a,b,[c,d,e]]]]).  The course that I took in Software Engineering (EECE3093C) also exposed me to some of the characteristics of Javascript (promises) and I was able to implement a solution which utilized Google Firebase for simple queries and develop a simple iOS geolocation application for filing incident reports in the Cincinnati area, which may aid me in the development of my current project.  I also gained a great deal of experience with C and various operating systems concepts (virtual memory, multiprocessing, forking, paging, cache methodologies, inter-process communication – pipes/dup/dup2, FIFO’s, kernel versus user mode, locks, mmap, etc.), which I hopefully can use in the design of a parallel-processing debugger.  The networking course (CS4065) at UC also taught me basic information about the various layers of the network and their associated protocols which may be useful to the current project.  In addition, the advanced course that I took in Requirements Engineering (CS5127) increased my knowledge of using clustering (nearest-neighbor joining) methods to determine relationships between functional and non-functional requirements, and increased my knowledge of using linear temporal logic to assist in making sure that the specifications of a system matched the requirements in a given environment, which is important to this project.  I also hope the knowledge I gained in better understanding propositional logic in the Math Logic course (CS5121) will assist me in better communicating requirements, and assuring that the software that I create is expressed correctly, to minimize confusion and potential bugs.  I believe that all of this knowledge will directly or indirectly assist me in creating a debugging application that is both user-friendly, meets the user’s requirements, is portable to various operating systems, performs, efficiently and is useful, and may hopefully add features that I would personally want to see in a debugger that I haven’t previously seen.
##
##### I think that my co-op experience at Siemens PLM as a programmer in the Drafting/PMI areas has not only given me the technical skills to work in a large codebase of C++ and Python Code (~200 million lines of code, ~20 million just for the Drafting application of Siemens NX CAD software suite), but it has helped me to improve on many non-technical skills that I have had some difficulty with throughout my life, the principle one being multi-tasking.  I had one experience during my third semester at Siemens PLM on the drafting team when I had achieved adequate progress on solving PRs (Problem/Bug Reports), but I had not made sufficient progress on completing NX user-interface-based functional autotests to ensure that the software was performing correctly with various drawings/functions, since I had dedicated most of my time to working on PRs and the creation of the auto-font-changing-internal-NX tool to optimize productivity on the laborious QA task of changing every single (sometimes 300 fonts) on a part file to a compatible font, so that autotests run in Linux would not fail because of an incompatible font.  I spent 1 hour doing this for a particular autotest, and my software solution could perform this task in a millisecond, which saved QA a great deal of time in creating autotests.  However, although I was great at creating autotests, I did not find this aspect of my work interesting, so I tended to hyperfocus on what I enjoyed the most, which was finding and fixing bugs (which was a never ending task) and working on this font tool, so I did not receive a 3 on my performance evaluation in this area during the midpoint evaluation. However, I became better at multi-tasking by this experience and I improved my score at the final evaluation in this area from a 2 to a 3, which was needed to receive a passing performance evaluation from my managers at Siemens.  I also learned how to properly document my code, and I became better at finding the root cause of issues, rather than trying to fix individual cases.  I think my experience with debugging and thoroughly testing software that I gained at Siemens PLM will help me to be effective in working with other team members on this project.  I was a little older than the other co-ops (I am in my early 40’s now), so I have become proficient in my communication skills, work ethic, working with other team members, showing up on time, being responsible, sticking to commitments, following the rules (mostly), completing projects in a timely manner, not procrastinating too much, not getting too involved in office politics (always listening but not contributing too much), and adhering to deadlines.  I have acquired those skills through life experience (many times in the principals/managers/dean’s office), so that was not an issue working at Siemens.  I think my vast experience will help me make a positive contribution to this project and meet its goals.
## **Motivation/Preliminary Approach to Designing Solution for this Project**
##### I am excited to work on this project, since I want to actually create a debugging application which will hopefully which will not only allow the user to be able to debug more than programming language, but will hopefully be able to give the user advice on how to solve some of the runtime errors which are occurring in their application as well.  Many debuggers are able to assist the user with compiler syntactic and semantic errors, but other than a null-pointer exception, which the Java compiler will detect, without explaining the reason for the error, many of the debuggers that I have seen are not very helpful in presenting the developer with options for how to fix many runtime errors that they are not able to detect without extensive testing and debugging.  Our QAZ compiler at Siemens PLM which I spent many hours (resolving errors and warnings in) would notify the developer about warnings, such as deprecated methods, lengthy if-else statements, etc., but we still had to create thousands of functional autotests in order to detect the almost infinite number of runtime errors; the errors continued, the code became more and more complex, and it seemed like my team was the company depot for all of the crazy errors that no other team wanted to deal with (which is what I enjoyed, anyway).  Potentially, this would involve the use of a potentially simplified version of an AI heuristic or database.  This will be my initial, preliminary approach to designing this project – determining the initial requirements for this project.  I also would like to be able to determine which programming language would be most portable to other operating systems (it seems like Java would be a good start), although other languages such as C++ are more efficient.  I plan to begin by working with my other team members to determine the requirements for the project, determine which language, or combinations of languages and frameworks would be needed, and then proceed to develop a conceptual/functional design of what the application should look like.  From then on, we can determine what the class diagram should look like, which member functions should be included in the various classes, and then eventually, we will be able to embark on creating a prototype of the application.  This semester, I plan on experimenting with some individual languages, frameworks, to hopefully complete a sort of “rough-design” for this project and potentially some working-code by the end of this semester or during the Winter Break.
##
##### I expect that I will accomplish the goals of this project during the two-semester portion of this course and by the end of the Spring Semester.  I hope that we will create a functional project, which meets most or all of the functional and non-functional requirements that we have defined together as a team and that the project will have some enhancements that other debuggers do not natively have.  I will self-evaluate my contributions by the results that I have achieved and by the effort and work that I have placed in this project.  I will know whether I have been successful by how well I am meeting the goals set forth by the team.  The trick is not to make the goals too large (they need to be broken up into small chunks, so that everyone is not overwhelmed and, as a result, will procrastinate on their work and not meet deadlines).  The work also has to be well documented, so that we know who made which change to better assist everyone in the debugging process.  We also have to make sure that we have forks to our master build in Github, and that the final code is not modified until we can be sure that our individual code from team members is free of defects for a given portion of the project.  We had many layers of code verification (within the development team, with QA, and with the final testing that occurred before an update was released to the customer), so we will try to utilize some of these constructs in the development of this project.  I will also know whether I have done a good job by not only my own feeling toward the project, but remarks from my other teammates as well.  It is not too difficult to determine who is not performing up to their potential and who is slacking off (although it is better to work in a positive way to motivate others, rather than being critical).  I have found that being critical makes everyone angry, and then the passive-aggressive personalities start coming through, and nothing ends up getting accomplished.  I have been working with my team for the past week, though, and they do not seem to have difficult personalities, although I have worked with many throughout my life (I have been yelled at so much that it comes in one ear and goes out of the other).  I am glad that I have the opportunity to enhance my learning through this project, and I hope that it will be a great culminating experience to my second-to-last semester at University of Cincinnati.     
