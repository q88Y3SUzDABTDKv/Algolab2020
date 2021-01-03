# Algolab2020
Solutions for problems given in ETH course [Algorithms Lab in Fall 2020](https://www.cadmo.ethz.ch/education/lectures/HS20/algolab/index.html).

The code for these problems is written with the following in mind:
- Readability. It is prevalent in competitive programming to use macros, and extremely dense and unreadable code. I dont find the price for longer names and few more lines too high. I often rewrite the problems to try something new or to see performance gain/loss therefore even I appreciate this.
- Performance. Lot of the problems could be solved with considerably less code. It would pass within the time limits. However, I tried to make the code run fast to a reasonable extent.
- Code quality. I know this is competitive programming and it does not matter much here but I found out I do better when I go a bit slower in terms of writing code and then avoid some of small bugs/issues. This is the main reason why you can see `const` everywhere and special function to load data (to have the loaded data also const).

Should you find some typo, bug, improvement or anything related feel free to message me at my email `simon.hrabec` on gmail.

## Featured solutions
| Week | Problem of the Week | 1st problem | 2nd problem | 3rd problem | 4th problem |
| --- | --- | --- | --- | --- | --- |
| 3 |  | [Antenna](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Antenna) | [First Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20First%20Hit) | [Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Hit) |  | 
| 5 | [Motorcycles](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20PotW%20-%20Motorcycles) | [Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul) |  |  |  | 
| 7 |  | [Radiation](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Radiation) |  |  |  | 
| 8 |  | [Germs](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20-%20Germs) |  |  |  | 
| 11 |  | [Hand](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Hand) |  |  |  | 
| 12 |  | [India](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20India) | [Moving Books](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Moving%20Books) |  |  | 
| 13 |  | [Evolution](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Evolution) | [Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon) | [Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith) |  | 

## Techniques/algorithms/data structures
- BFS - [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Binary Search - [W05/Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul) [W12/India](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20India) [W12/Moving Books](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20Moving%20Books) [W13/Evolution](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Evolution) [W13/Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon) [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- CGAL Geometry - [W03/Antenna](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Antenna) [W03/First Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20First%20Hit) [W03/Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Hit)
- CGAL::Gmpz/Gmpz (Arbitrary Precision Types) - [W05/Motorcycles](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20PotW%20-%20Motorcycles) [W07/Radiation](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Radiation)
- DFS - [W05/Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul) [W13/Evolution](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Evolution) [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Delaunay Triangulation - [W08/Germs](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2008%20-%20Germs) [W11/Hand](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Hand) [W13/Sith](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Sith)
- Dijkstra - [W13/Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon)
- Linear Programming - [W07/Radiation](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2007%20-%20Radiation)
- Max-Flow-Min-Cost - [W12/India](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2012%20-%20India) [W13/Marathon](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2013%20-%20Marathon)
- Randomization - [W03/Antenna](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20Antenna) [W03/First Hit](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2003%20-%20First%20Hit)
- Split and List - [W05/Asterix the Gaul](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2005%20-%20Asterix%20the%20Gaul)
- Union-Find - [W11/Hand](https://github.com/simon-hrabec/Algolab2020/tree/main/Week%2011%20-%20Hand)
