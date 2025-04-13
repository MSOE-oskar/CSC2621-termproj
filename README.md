# CSC2621-termproj
Term Project for Data Science Class
## Collection
Collected by Malin Morris from the daily New York Times Games Spelling Bee puzzle using the hint line from the hints page. The dataset contains 612 puzzles and 40 features<br>
Spelling bee game: https://www.nytimes.com/puzzles/spelling-bee
## Variables
1. Center Letter: the letter at the center of the puzzle that must be included in every word (most of the 26 letters appears at least once)
2. Letters 1-6: the other letters in the puzzle, usually listed alphabetically (Each of the 26 letters appears at least once)
3. Points: The number of points in the puzzle (4 letter words are 1 point, 5+ letters is 1 point per letter, pangrams are worth an additional 7)
4. Words: the number of words in the puzzle solution
5. Pangrams: the number of words that use every letter at least once (every puzzle has at least one)
6. Perfect Pangrams: the number of words that use every letter exactly once
7. Bingo: 1 if every letter begins at least one word, otherwise 0
8. Date: the date of that puzzle (8/1/23-4/3/25)
9. Non-perfect Pangrams: pangrams - perfect pangrams
10. Number of Vowels: number of vowels (A, E, I, O, U, Y) in the puzzle
11. ING, OUGH, TION, ED, UN, ABLE, IGHT, LY: whether or not the prefix or suffix exists in the puzzle. 1 if it is there, 0 otherwise
12. NONE: if there are no prefixes or suffixes in the puzzle
13. PPW: points per word (points / words) as a decimal number
14. J, Q, V, W, X, Y, Z Bingo: whether there is bingo if one of the weird letters is in the puzzle
15. C and K: whether C and K exist together in the puzzle
16. C, K: used to calculate if C and K are (separately) in the puzzle
17. Letters as a word: concatenates the letters together
18. Word: alphabetizes the letters in the word to look for repeat pangrams
19. Repeat Pangram: 1 if the pangram has appeared before 0 if not (if the entry in Word column appears more than once)
20. Vowels as a Word: alphabetized vowels appearing in the puzzle
## Notes
Editor Sam Ezersky is noted as saying there will never be an S in a puzzle, but the 2,500th puzzle on 3/12/25 did contain an S for the very first time