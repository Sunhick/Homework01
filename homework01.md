## Homework 1

1. Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.
***

2. Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.

   According to Brooks, Accidental Difficulties arise from the tools, technologies or processes we use in software development and they are not inherent in the nature of the software itself. These difficulties could be removed by improving or changing the processes or tools. Brooks mentioned that the productivity of a software can be increased with the elimination of accidental difficulties. Brooks uses the example of High Level Languages, before their development, the complexity of machine level languages was an accidental difficulty.
    
    **Examples of Accidental Difficulties :**

    1. When the customer requirements were continuously changing in the real world, following waterfall software development model was an accidental difficulty. Whenever there is a change in the customer’s requirements, the software has be redeveloped following the software development life cycle leading to wastage of time, effort and cost. This accidental difficulty could be eliminated by changing the underlying software development model to Agile, where the changes needed in the software can be developed and delivered effectively under the constant supervision of the customer.

    2. The design and architecture of complex systems was cumbersome and not extensible before the creation of object oriented design patterns. Even a minor change in the software needed changes in the design of the entire system when the principles were not applied properly, causing accidental difficulty. When the design principles were strictly followed using object oriented architecture, it has become quite easy to modify. and extend the existing system without causing major design changes, thus less leading to development effort and more stable system.

3. List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.
    
     The four essential difficulties that are described by Brooks are:

     1. **Complexity** – According to Brooks, Software entities are complex. He explains that no two parts are alike and there are contrasts with materials in other domain. According to him large software systems have a huge number of states that is the software has a higher order of magnitude more states than the computer hardware and also he points out that as the size of the system increases there is an exponential increase in the number and types of parts. It is usually not possible to abstract away the complexity of the application domain.
 
     Let us consider some domains such as the air traffic control, international banking or avionics software. Although these domains are complex from within, they can be only visualized when the designers attempt to model the domain. The complexity can also arise from various links between different artefacts such as specifications, documentation, code, test cases and many more.
 
     Brooks also specifies certain problems that are caused due to complexity. Some of the most common issues are difficult team communication, Delays, flaws in the products, unanticipated difficulties and many more.
 
     2. **Conformity** – Brooks explains that a lot of software engineers who face complexity which is very arbitrary. He gives an example of a system that supports an existing business process when a new VP arrives. He explains the situation by considering a condition where the VP decides to change the business process to prove his hold on the company. The employees, no matter what their opinion is, should conform to the new arbitrary changes which might prove to be complex.
 
     He explains some other instances of conformity such as adapting to a pre existing environment which involves integrating ourselves with the legal system, being ready to change the software depending on the changes in the environment. Brooks stresses on the fact that “It is almost impossible to plan for an arbitrary change”.
 
     3. **Changeability** – Brooks states that the software is constantly evolving. In terms of the hardware he explains that once they are manufactured they cannot be changed, but change can happen in the later models like in automobiles, but there is a tradeoff that is required between change and cost in case of hardware components.
    
     Brooks also explains that there is a greater pressure for the software to change. He points out that a change in the software means a change in either one or more of its functionality and hence making it more malleable. He also emphasizes that certain clients do not understand the difficulty of changing the functionality of a software and the rework required in it.
 
     4. **Invisibility** -  Brooks explains that the software is invisible and non visualizable. He explains that it is very difficult to create a software blueprint to help the developers. He explains this difficulty by taking the example of UML diagrams, the different types of diagrams they have and the complexity of using them in all together.  
***

4. Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering.

   As per Brooks _"**Silver bullet**"_ means a standard process/procedure (like a _Golden hammer_) to address the missed project schedules, over budgets, buggy software etc. Something that can make the cost of producing software as low as the cost of manufacturing hardware. There is no single development in either software technology or management process that will guarantee at least order of one magnitude improvement in productivity, reliability, complexity. 

   Although it sounds appealing to look for silver bullet - none exists due to the very nature of software process. Firstly the software development progress is very slow as compared to the computer hardware progress. 

   As per Moore's law - 
   >"The number of transistors in a dense integrated circuit doubles approximately every two years.".

   This means that the hardware is progressing by two-folds every two years.

   secondly, the difficulties inherent in the software technology(essence) and those that attend its production ubt that are not inherent(accidents). Essential difficulties include complexity, conformity,  changeability and Invisibility. Accidental difficulties include high-level languages, time-sharing, and unified programming environments.
***

5. In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.

   Chemists are scientists who research and experiment with chemical substances and their properties. The work of a chemist involves building and testing theories, analyzing various substances and their properties, which results in interesting discoveries about the chemical substance, or create new compounds which can be used in a variety of applications. Chemists look at various problems and try to find new techniques to solve the problems by coming up with theories and successfully experimenting on those theories.
   
   A chemical engineer picks up these successful theories/discoveries and converts them into useful products for human use which induces practical constraints. The constraint maybe, is the technique applicable on a large scale, will it meet the budget constraints, and so on.
   
   In a similar way, computer scientists come up with new ideas/ techniques to search, or a new algorithm in ML, or a new framework for distributed systems. A computer scientist looks at a problem and finds better ways to solve the problem.
   
   Software engineering involves using these ideas/ techniques to build a software with a given set of requirements. A software developer works with computer scientists to design a software with certain specifications. The specifications/ constraints can be relaibility, cost, performance and so on. For example, an algorithm may give the best performance when run on 100-servers, but can the same be achieved using 10-servers. 
***

6. In lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.

    1. **Abstraction** : Using abstraction, software engineers split a bigger problem into a number of smaller sub-problems to such an extent that the smaller problems will be solvable by using abstractions already developed by others. Abstraction plays a very important role in software development as it hides many details from the developer and gives the required output. For example, we can just call a REST Twitter API to get the names of all the followers given the name of the person, the implementation details do not need to be disclosed. Using abstraction, the results can be obtained very quickly as we reuse the objects developed by others.

    2. **Conversation** : This is the key for any successful software. We need conversation with many people throughout the software development life cycle. For example, we need to talk to the users and domain experts to know their requirements and understand the problem. We need to collaborate and have continuous conversations with other development teams and testers to ensure that the software development is progressing properly.

    3. **Specification** : Without Specification, we cannot develop any software. Software engineers specify everything starting from requirements, design, programming languages to be used, test cases, software development models, integration tools and so on. Most of the times, specifications are documented and updated periodically to keep track of everything. Usually, there will be some standards for the specifications based on the company developing the software.

    4. **Translation** : Translation is inherent in the software development life cycle. In every stage, software engineers translate from one abstraction to another, one specification to another and so on. For example, a design can be decomposed and translated into some other design that will be easier to solve.

    5. **Iteration** : The development in software should always be done incrementally, rather than developing all at once. Step by Step execution of the program leads to a bug free and better code. We know that Agile model is proven effective than Waterfall model for most of the projects, where the requirements keep changing. So, Agile software development model can be followed during the software development to deliver the code in iterations, with continuous collaboration with the customer.
