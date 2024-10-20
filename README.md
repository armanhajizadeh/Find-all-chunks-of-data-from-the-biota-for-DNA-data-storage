# Find all chunks of data from the-biota for DNA data storage

I wrote a code that processes the whole genome sequence and extracts chunks of nucleotides from the entire genome. The code calculates how many organisms are needed to satisfy all combinations of ACTG sequences. For example, if we extract a sequence of 8 nucleotides, 
4
8
4 
8
  combinations are needed to cover 100% of the possible sequences. The code also provides information on the number of organisms required to cover different percentages of these combinations. For instance, it calculates how many organisms are needed to cover 50% of the combinations. It should be noted that the code generates a random whole genome sequence, and sometimes I may generate shorter sequences that do not exist in nature due to computational limitations. Additionally, the code accounts for the differing percentages of C-G and A-T base pairs, as these vary between species.
