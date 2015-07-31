# How to read the Nodepad

nodepad, is a one type of flowchart.

nodepad, is our artificial intelligence tool GUI. But the AI features ( to automatically make nodes == think ) is now suppressed in this use case. Just look at the node field ( the chart )  as a flowchart.

The direction, the things flow in nodepad, is opposite to standard ways in flowcharts. Usually it goes from  top to bottom, but in nodepad we write to have the flow from the bottom to top.

as in many UML charts and also flow charts, we should be careful for the granularity. like Use Cases are sometimes used to describe the flowchart. it is higher level compared to flowcharts, while both can write flow of each function steps. 

in nodepad, there is functionality, to link the internal node field, to a node. by clicking the red link (string) of each node, you can open the node field which has the nodes. and you can write the nodes there. 

Mapping the levels to this functionality, we use nodepad to describe our service flow to cover whole granularity. 

so in the Highest level flow chart of the product, you cau see the use case level ones. or maybe in the huge development we have more meta  ( higher level ) flowchart, and many granularity levels == many fields might be there. 

* if you don’t know the word “node” then check the “graph” data structure.


## storyteller style and regarding code generation

the reason why we don’t use UML, or some charts easy to write and common ones, is that this makes us possible to code gen. we can use our own code gen tool storyteller by writing things in this style using nodepad. 
in the flow chart you saw, you can find strings ( node contents ) written in formatted to our original style.
It’s to some extent human readable And similar to the natural language ( english ),  but more similar to naming conventions of programming. especially like in Java class naming, or Ruby on rails naming conventions.

each node contents  are called Sentence.
Using  storyteller, we can generate models and codes, from this Sentences. 

e.g. PostUser means we gonna have a form interface in web, and server side code to create it. by this we can generate the codes  of rails, spring mvc and boot, php, html and js angular, etc. 

other verbs we have, is like “Updates, post, indexes, roses, list, batches,”.

so the flowchart in nodepad, written to follow storyteller style  are at one side a flowchart to describe and show the higher and lower systems flow to developers understands the requirements, but also the code generetaion input. MDA source. 



