> [!caution] This page contained a drawing which was not converted.   

Episode 27:  
-@6:20  
-can calculate the number of pathways in the problem space by the formula FD  
-F = # of operators applying at any stage  
-D = # of stages you go through
 
-Keith Holyoak gave a very famous example of this ([https://en.wikipedia.org/wiki/Keith_Holyoak](https://en.wikipedia.org/wiki/Keith_Holyoak))  
-he is a psychologist who was instrumental in doing important work on the psychology of problem solving
 
-scenario: game of chess  
-on average, number of operations you can perform on any turn is 30 - i.e. there are 30 legal moves you could make each turn  
-many of these are stupid, or bad moves, but that's not the point  
-on average, there are 60 turns
 
-therefore FD = 3060  
-this is the number of pathways that are in the problem space  
**-this is combinatorial explosion**
 
-this ^ is a vast number  
-in scientific notation, something like 4.29 x 1088
 
-brain has, on average, 1010 neurons  
-brain has, on average, 5 x 1015 synaptic connections between neurons
 
-this 3060 # is actually greater than the estimated number of atomic particles in the universe  
-this is literally bigger than the universe
 
-this means **you can't search the whole space**  
-for very very many problems
 
-you don’t have time, machinery, or resources to search it all
 
-you somehow zero in on only a very small subsection of that whole space, you search in there and you **often find a solution**
 
-you somehow zero in on the relevant information, and make it effective in your cognition - this is what he calls relevance realisation
 
-how do you do this?
 
-even the fastest chess playing computers don’t check the whole space - they can't, they're not powerful or fast enough  
-{_back up for this claim here:_ [https://www.linkedin.com/pulse/machine-learning-ai-case-studies-part-2-heuristic-chess-hirani-msc/](https://www.linkedin.com/pulse/machine-learning-ai-case-studies-part-2-heuristic-chess-hirani-msc/) }  
-actually provides some sources for the 3060 number here  
_-& here:_ [https://medium.com/@SereneBiologist/the-anatomy-of-a-chess-ai-2087d0d565](https://medium.com/@SereneBiologist/the-anatomy-of-a-chess-ai-2087d0d565)_}_
   

**-so it turns out that "one of the things that makes you crucially intelligent is your ability to zero in on relevant information" in order to avoid combinatorial explosion**
 
-experiencing that in 2 related ways  
-generation of obviousness - which happens automatically & seamlessly  
-how things are salient to you - how they stand out to you, grab your attention
 
-these two things are not static, because what was obvious and salient to you was wrong, and you have the ability to **dynamically restructure what you find relevant**
 
-

"Shannon worked out that the average game can have 40 moves, or 80 plies for both players. This makes the total number of games at a gargantuan 30^80 or approximately 10^120. This number is 10 with 120 zeroes in front of it! An extremely massive number but just an estimate! Since the actual number of games possible is unknown given how no one is likely to invest the effort, mathematicians have worked out the possible number of games after 5 rounds (or 10 plies). **After each player has moved a piece 5 times each there are exactly 69,352,859,712,417 possible games that could have been played (or 69.3 trillion games!).** Note that using a Monte Carlo simulation, that number is dangerously more massive, ranging from **10^29241 to 10^34082** - this massively dwarfs the conservative estimate for atoms in the observable universe, which is estimated at a tiny **10^80** atoms.

> From <[https://www.linkedin.com/pulse/machine-learning-ai-case-studies-part-2-heuristic-chess-hirani-msc/](https://www.linkedin.com/pulse/machine-learning-ai-case-studies-part-2-heuristic-chess-hirani-msc/)>  

"

-the mathematician, Claude Shannon

-**I have found a source from Holyoak that discusses this - in my projects OneDrive sources folder**
 
**-found a source on Holyoak talking about combinatorial explosion, that JV references in his paper "Relevance Realisation and the Emerging Framework in Cognitive Science", here:** [https://studylib.net/doc/18715289/an-invitation-to-cognitive-science---2nd-edition](https://studylib.net/doc/18715289/an-invitation-to-cognitive-science---2nd-edition)  
-here's the reference: K. J. Holyoak. Problem Solving. _An Invitation to Cognitive Science: Thinking_, E. S. Edward and N. O. Daniel, eds, Chapter 8, 2nd edn, pp. 267–295. MIT Press, 1995.

-this 2nd source is REALLY good  
-mentions this "some heuristic search methods are very general and can be applied to virtually any problem; others are much more specific and depend on detailed knowledge of a particular problem domain. As we will see, **the development of expertise is largely the acquisition of knowledge that** **restricts the need for extensive search**"
 
-says that heuristics aren't much use in "best-solution" problems - an example of which is the **traveling-salesman problem**  
-according to the Wiki entry on the traveling-salesman problem, "_even though the problem is computationally difficult, many_ _heuristics_ _and_ _exact algorithms_ _are known, so that some instances with tens of thousands of cities can be solved completely and even problems with millions of cities can be approximated within a small fraction of 1%_" - **this may be evidence against the 'unbounded complexity' idea**  
￼-_edit_ welp maybe not: ￼-"_Computer scientists_ **have not found any algorithm that can solve this problem in polynomial time, and therefore rely on approximation algorithms** _to try numerous permutations and select the shortest route with the minimum cost_.
 
_The main problem can be solved by calculating every permutation using a brute force approach and selecting the optimal solution. However, as the number of destinations increases, the corresponding number of roundtrips grows exponentially and surpasses the capabilities of even the fastest computers. With 10 destinations, there can be more than 300,000 roundtrip permutations. With 15 destinations, the number of possible routes could exceed 87 billion._
 
_For larger real-world travelling salesman problems…businesses rely on approximate solutions that are sufficiently optimized by using fast tsp algorithms that rely on heuristics. Finding the exact optimal solution using dynamic programming is usually not practical for large problems.__￼__￼_{REGARDING SOLUTIONS TO THE PROBLEM}  
_1. The brute-force approach_  
_The Brute Force approach, also known as the Naive Approach, calculates and compares all possible permutations of routes or paths to determine the shortest unique solution. To solve the TSP using the Brute-Force approach, you must calculate the total number of routes and then draw and list all the possible routes. Calculate the distance of each route and then choose the shortest one—this is the optimal solution._
 
**This is only feasible for small problems, rarely useful beyond theoretical computer science tutorials**_._" ￼([https://blog.routific.com/blog/travelling-salesman-problem](https://blog.routific.com/blog/travelling-salesman-problem))
 
-this appears to be an instance of a "P versus NP problem" ([https://en.wikipedia.org/wiki/P_versus_NP_problem](https://en.wikipedia.org/wiki/P_versus_NP_problem))