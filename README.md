Heavily inspired by [Pascal Pons' solver](https://github.com/PascalPons/connect4) of the game. I decided to take a stab at a similar concept, and it performs... comparably!

Initially, I was benchmarking without using an opening book, but it seems like an opening book is necessary to get lightning-fast results like his solver does. The opening book for every relevant 8-ply board (i.e. board with 8 moves) is in this repo.
