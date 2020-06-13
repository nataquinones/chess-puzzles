# chess-puzzles
Beginner level chess puzzles

## Puzzles
### day-puzzles
- Puzzles:
    - [day-puzzles.ipynb](day-puzzles.ipynb)
- Solutions
    - [dp_solutions_NQO.ipynb](solutions/dp-solutions_NQO.ipynb)
    - [dp_solutions_MGM.ipynb](solutions/dp-solutions_MGM.ipynb)

## Requirements
- [python-chess](https://python-chess.readthedocs.io/en/latest/)

## Formats

### Forsyth–Edwards Notation `.fen` 
from [Wikipedia: Forsyth–Edwards Notation](https://en.wikipedia.org/wiki/Forsyth–Edwards_Notation)
> A FEN record contains six fields. The separator between fields is a space. The fields are:

> 1. Piece placement (from White's perspective). Each rank is described, starting with rank 8 and ending with rank 1; within each rank, the contents of each square are described from file "a" through file "h". Following the Standard Algebraic Notation (SAN), each piece is identified by a single letter taken from the standard English names (pawn = "P", knight = "N", bishop = "B", rook = "R", queen = "Q" and king = "K").[1] White pieces are designated using upper-case letters ("PNBRQK") while black pieces use lowercase ("pnbrqk"). Empty squares are noted using digits 1 through 8 (the number of empty squares), and "/" separates ranks.
> 2. Active color. "w" means White moves next, "b" means Black moves next.
> 3. Castling availability. If neither side can castle, this is "-". Otherwise, this has one or more letters: "K" (White can castle kingside), "Q" (White can castle queenside), "k" (Black can castle kingside), and/or "q" (Black can castle queenside). A move that temporarily prevents castling does not negate this notation.
> 4. En passant target square in algebraic notation. If there's no en passant target square, this is "-". If a pawn has just made a two-square move, this is the position "behind" the pawn. This is recorded regardless of whether there is a pawn in position to make an en passant capture.[2]
> 5. Halfmove clock: This is the number of halfmoves since the last capture or pawn advance. This is used to determine if a draw can be claimed under the fifty-move rule.
> 6. Fullmove number: The number of the full move. It starts at 1, and is incremented after Black's move.


### Portable Game Notation `.pgn`
from [Wikipedia: Portable Game Notation](https://en.wikipedia.org/wiki/Portable_Game_Notation)
