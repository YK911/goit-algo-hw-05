## Unveiling the Swiftness: A Glimpse into the Performance of Search Algorithms

### Introduction:

In the realm of computer science, the efficiency of search algorithms is a topic of paramount importance. These algorithms, designed to locate specific elements within datasets, fuel the core functionality of information retrieval systems. This essay provides a brief exploration into the performance metrics of three prominent search algorithms: KMP search, Boyer-Moore search, and Rabin-Karp search.

### Algorithmic Showdown:

The table below presents a snapshot of the performance of each algorithm, measured in terms of speed:

✅ Approach 1

|   Algorithm types   |  Speed   |
|---------------------|----------| 
| kmp_search          |  0.17304 |
| boyer_moore_search  |  0.05837 |
| rabin_karp_search   |  0.34747 |

Fastest search algorithm ***with matches***: boyer_moore_search with total time: 0.05837 sec

|   Algorithm types   |  Speed   |
|---------------------|----------| 
| kmp_search          |  0.14996 |
| boyer_moore_search  |  0.06317 |
| rabin_karp_search   |  0.36774 |

Fastest search algorithm ***without matches***: boyer_moore_search with total time: 0.06317 sec

✅ Approach 2

|   Algorithm types   |  Speed   |
|--------------------|----------| 
| kmp_search          |  0.19312 |
| boyer_moore_search  |  0.07385 |
| rabin_karp_search   |  0.47427 |

Fastest search algorithm ***with matches***: boyer_moore_search with total time: 0.07385 sec

|   Algorithm types   |  Speed   |
|--------------------|----------| 
| kmp_search          |  0.22357 |
| boyer_moore_search  |  0.10547 |
| rabin_karp_search   |  0.54985 |

Fastest search algorithm ***without matches***: boyer_moore_search with total time: 0.10547 sec

**Fastest Algorithm:**

From the presented data, it is evident that the Boyer-Moore search algorithm stands out as the fastest, boasting an impressive total execution time of *0.05837* and *0.07385* seconds.

At the same time, the position (at the beginning, in the middle, at the end) of the substring for the search does not have a significant effect on the results

## Factors Influencing Speed:

Several factors contribute to the speed of search algorithms:

- ***Pattern Matching Techniques:*** Each algorithm employs unique pattern matching techniques. Boyer-Moore, known for its efficient character comparisons and jump heuristics, showcases superior speed in certain scenarios.

- ***Algorithmic Complexity:*** The time complexity of an algorithm, often expressed in Big O notation, provides insights into its efficiency. Boyer-Moore's linear time complexity makes it highly performant, especially for larger datasets.

- ***Adaptability:*** The adaptability of an algorithm to different types of data influences its overall speed. Boyer-Moore's adaptability to varying patterns contributes to its consistent performance across diverse datasets.