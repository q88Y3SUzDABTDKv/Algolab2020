# Algolab2020
Solutions for problems given in ETH course [Algorithms Lab in Fall 2020](https://www.cadmo.ethz.ch/education/lectures/HS20/algolab/index.html).

The code for these problems is written with the following in mind:
- Readability. It is prevalent in competitive programming to use macros, and extremely dense and unreadable code. I dont find the price for longer names and few more lines too high. I often rewrite the problems to try something new or to see performance gain/loss therefore even I appreciate this.
- Performance. Lot of the problems could be solved with considerably less code. It would pass within the time limits. However, I tried to make the code run fast to a reasonable extent.
- Code quality. I know this is competitive programming and it does not matter much here but I found out I do better when I go a bit slower in terms of writing code and then avoid some of small bugs/issues. This is the main reason why you can see `const` everywhere and special function to load data (to have the loaded data also const).

Should you find some typo, bug, improvement or anything related feel free to message me at my email `simon.hrabec` on gmail.

How to use this repository:
- Copy-paste relevant code snippets to begin your work
- If stuck and gave the problem already some time read the minimal amount of problem solution to get yourself unstuck
- After finishing the task check the solutions for alternative ways to approach it
- Check the code if you just wanna compare the code of your solution and see how other people write C++
## Featured solutions
| Week | Problem of the Week | 1st problem | 2nd problem | 3rd problem | 4th problem |
| --- | --- | --- | --- | --- | --- |
| 3 |  | [Antenna](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Antenna) | [First Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20First%20Hit) | [Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Hit) |  | 
| 5 | [Motorcycles](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20PotW%20-%20Motorcycles) | [Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul) |  |  |  | 
| 6 | [Tracking](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2006%20PotW%20-%20Tracking) |  |  |  |  | 
| 7 |  | [Inball](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Inball) | [Radiation](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Radiation) | [What is the Maximum](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20What%20is%20the%20Maximum) |  | 
| 8 | [Surveillance Photograph](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20PotW%20-%20Surveillance%20Photograph) | [Germs](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20-%20Germs) |  |  |  | 
| 9 | [Legions](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2009%20PotW%20-%20Legions) |  |  |  |  | 
| 10 |  | [Asterix and the Chariot Race](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2010%20-%20Asterix%20and%20the%20Chariot%20Race) | [Asterix in Switzerland](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2010%20-%20Asterix%20in%20Switzerland) | [New York](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2010%20-%20New%20York) |  | 
| 11 | [Fleetrace](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20PotW%20-%20Fleetrace) | [Fighting Pits of Meereen](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Fighting%20Pits%20of%20Meereen) | [Hand](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Hand) | [Lestrade](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Lestrade) | [Return of the Jedi](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Return%20of%20the%20Jedi) | 
| 12 |  | [Car Sharing](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Car%20Sharing) | [Hong Kong](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Hong%20Kong) | [India](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20India) | [Moving Books](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Moving%20Books) | 
| 13 |  | [Evolution](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Evolution) | [Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon) | [Punch](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Punch) | [Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith) | 

## Techniques/algorithms/data structures
- BFS - [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Binary Search - [W05/Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul) [W12/India](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20India) [W12/Moving Books](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Moving%20Books) [W13/Evolution](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Evolution) [W13/Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon) [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Bit Manipulation - [W11/Fighting Pits of Meereen](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Fighting%20Pits%20of%20Meereen)
- CGAL Geometry - [W03/Antenna](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Antenna) [W03/First Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20First%20Hit) [W03/Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Hit)
- CGAL::Gmpz/Gmpz (Arbitrary Precision Types) - [W05/Motorcycles](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20PotW%20-%20Motorcycles) [W07/Radiation](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Radiation)
- DFS - [W05/Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul) [W10/Asterix and the Chariot Race](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2010%20-%20Asterix%20and%20the%20Chariot%20Race) [W10/New York](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2010%20-%20New%20York) [W11/Return of the Jedi](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Return%20of%20the%20Jedi) [W13/Evolution](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Evolution) [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Delaunay Triangulation - [W08/Germs](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20-%20Germs) [W11/Hand](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Hand) [W11/Lestrade](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Lestrade) [W12/Hong Kong](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Hong%20Kong) [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Dijkstra - [W06/Tracking](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2006%20PotW%20-%20Tracking) [W12/Hong Kong](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Hong%20Kong) [W13/Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon)
- Dynamic Programming - [W13/Punch](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Punch)
- Graph Duplication - [W06/Tracking](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2006%20PotW%20-%20Tracking) [W08/Surveillance Photograph](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20PotW%20-%20Surveillance%20Photograph)
- Linear Programming - [W07/Inball](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Inball) [W07/Radiation](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Radiation) [W07/What is the Maximum](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20What%20is%20the%20Maximum) [W09/Legions](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2009%20PotW%20-%20Legions) [W11/Lestrade](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Lestrade)
- Max-Flow-Min-Cost - [W11/Fleetrace](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20PotW%20-%20Fleetrace) [W12/Car Sharing](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Car%20Sharing) [W12/India](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20India) [W13/Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon)
- Maximum Flow - [W08/Surveillance Photograph](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20PotW%20-%20Surveillance%20Photograph) [W10/Asterix in Switzerland](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2010%20-%20Asterix%20in%20Switzerland)
- Minimum Spanning Tree - [W11/Return of the Jedi](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Return%20of%20the%20Jedi)
- Randomization - [W03/Antenna](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Antenna) [W03/First Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20First%20Hit)
- Split and List - [W05/Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul)
- Union-Find - [W11/Hand](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Hand)
## Code snippets
One of the most annoying thing about ALGOLAB (after the hard thinking ^^) is to always copy paste the right definitions for boost graphs, CGAL LP or flow edge adder. For this reason I put together a small set of useful snippets that should cover all your basic needs. It shoud prevent you from always searching the lecture notes or code examples for the relevant lines or going to the CGAL docs for basic syntax. You should find it here at one place. Some of the snippets are in fact the code from lectures or code examples (modified to some extent), some are written from scratch. The all attributions are listed in the code snippet descriptions.
- [Main function - N cases](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#Main-function---N-cases)
- [Main function - 0 terminated](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#Main-function---0-terminated)
- [Kernel conversions](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#Kernel-conversions)
- [CGAL round down](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#CGAL-round-down)
- [CGAL round uo](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#CGAL-round-uo)
- [CGAL intersections](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#CGAL-intersections)
- [Min Circle](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#Min-Circle)
- [Linear programming](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#Linear-programming)
- [Range loop - iterator wrapper](https://github.com/simon-hrabec/Algolab2020/tree/main/code%20snippets#Range-loop---iterator-wrapper)
