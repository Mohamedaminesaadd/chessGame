

### Chess Game (VS Computer)

In this project, developed by **Mohamed Amine**, you will learn how to build a chess game using **JavaScript**. This chess game allows you to play against a computer opponent, flip the board, and set custom positions. The project uses the powerful libraries **chessboard.js** and **chess.js** to handle the visual board and game logic.

---

## FEN Notation

FEN (Forsyth-Edwards Notation) is a standard notation used to represent a particular chessboard position. It provides a concise and human-readable way to describe the placement of chess pieces on the board, as well as other important information about the position. Here's how FEN notation works:

A FEN string consists of six fields separated by spaces:

1. **Piece Placement (8 ranks)**: This field represents the positions of the pieces on the board. Each rank is represented by a series of characters, where:
   - `K` represents a white king.
   - `Q` represents a white queen.
   - `R` represents a white rook.
   - `B` represents a white bishop.
   - `N` represents a white knight.
   - `P` represents a white pawn.
   - `k` represents a black king.
   - `q` represents a black queen.
   - `r` represents a black rook.
   - `b` represents a black bishop.
   - `n` represents a black knight.
   - `p` represents a black pawn.
   - Digits (1-8) represent empty squares, with the number indicating the count of consecutive empty squares.

   Example:
