# Lesson 08 - Creating Open Files

Concepts
- A file is open for a rook when none of that rook's own pawns stands on it.
- An enemy pawn on the file does not make it closed; that pawn becomes an objective for the rook.
- A file can be opened peacefully when a centrally posted piece provokes an exchange and a pawn recaptures away from its original file.
- A file can also be opened by assault: an adjacent enemy pawn is attacked so that one's own pawn may capture it and leave its original file.
- A pawn assault is a plan, not a forced sequence. Before beginning it, check whether the target pawn can advance, capture, or otherwise escape.

Strategic question
- How can we cause one of our own pawns to disappear from the file needed by a rook?

Position 1 - Opening a file peacefully

Black to move:

```text
8  ♜ . . ♛ . ♜ ♚ .
7  ♟ ♟ ♟ . . ♟ ♟ ♟
6  . . . ♟ . ♞ . .
5  . . . ♘ . . . .
4  . . . . ♙ . . .
3  . . . . . . . .
2  ♙ ♙ ♙ . . ♙ ♙ ♙
1  ♖ . . ♕ ♖ . ♔ .
   a b c d e f g h
```

Move table

```text
+------+--------+--------+-------------------------------------------+
| Move | Black  | White  | Strategic point                           |
+------+--------+--------+-------------------------------------------+
| 1    | ♞xd5   | ♙exd5  | White's e-pawn leaves the e-file.      |
+------+--------+--------+-------------------------------------------+
```

After `1...Nxd5 2.exd5`:

```text
8  ♜ . . ♛ . ♜ ♚ .
7  ♟ ♟ ♟ . . ♟ ♟ ♟
6  . . . ♟ . . . .
5  . . . ♙ . . . .
4  . . . . . . . .
3  . . . . . . . .
2  ♙ ♙ ♙ . . ♙ ♙ ♙
1  ♖ . . ♕ ♖ . ♔ .
   a b c d e f g h
```

Explanation
- White's centralized knight induced Black to exchange it.
- White's e-pawn recaptured on d5 and thereby left the e-file.
- The rook on e1 now has an open file.
- Nimzowitsch calls this opening a file by peaceful means.

Position 2 - The objective of a pawn assault

This is a static schematic position, not a forced tactical sequence:

```text
8  . . . . . . ♚ .
7  ♟ ♟ . . . ♟ . ♟
6  . . . . . . ♟ .
5  . . . . . . . .
4  . . . . . . . ♙
3  . . . . . ♘ . .
2  ♙ ♙ . . . ♙ ♙ .
1  . . . . . . ♔ ♖
   a b c d e f g h
```

Explanation
- White would like the h-pawn to leave the h-file so the rook on h1 can use it.
- The black pawn on g6 is the potential objective because it stands on the adjacent file.
- The black pawn on h7 cannot be captured diagonally by White's h-pawn.
- No advance is forced in this diagram. The side to move and Black's possible pawn advances or captures must be calculated before White begins the assault.
- If White's h-pawn disappears while Black's h7-pawn remains, the h-file is nevertheless open for White. The h7-pawn then becomes the rook's objective.

Four Knights connection
- The method is not tied to a particular opening.
- A centralized piece may provoke the exchange that causes a pawn to leave a rook's file.
- A wing-pawn assault must be calculated concretely; the desired file does not open merely because an advance is planned.

Exercise
- [x] Identify the file opened after `...Nxd5` and `exd5`.
- [x] Explain why the centralized knight helped open that file.
- [x] Identify the g6-pawn as the potential objective when White wants the h-pawn to leave the h-file.
- [x] Decide whether the h-file is open for White when White has no h-pawn but Black still has a pawn on h7.

Answers
- The e-file opens because White's e-pawn recaptures on d5 and leaves the file.
- The centralized knight provokes an exchange because of its influence from the center.
- The g6-pawn is the adjacent capture target for White's h-pawn.
- The h-file is open for White because no White pawn obstructs White's rook; the black h7-pawn is an objective, not a friendly obstruction.

Observations
- Source: `books/my-system-nimzowitsch-1930.txt`, Chapter II, Sections 1 and 2.
- The student correctly identified both the peacefully opened e-file and the adjacent pawn needed for a possible assault.
- The student correctly applied Nimzowitsch's rook-relative definition of an open file.
- An initial version of Position 2 incorrectly treated a conditional pawn plan as a forced sequence and did not state the side to move. It was withdrawn; the position is retained only as a static illustration of the objective.

