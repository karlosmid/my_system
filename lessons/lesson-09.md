# Lesson 09 - Occupying Open Files

Concepts
- Occupying an open file is only the first step; a rook may still be blocked from penetrating by an enemy pawn or piece.
- An enemy pawn on an open file is an objective, not a reason to call the file closed.
- The attacker should bring additional force to the file and establish a preponderance against the objective.
- Doubling rooks allows the rear rook to support and replace the leading rook after an exchange.
- After the resistance is removed, penetration into the enemy position becomes possible. Nimzowitsch identifies eventual entry onto the seventh or eighth rank as the ideal goal of file play.

Strategic question
- Once an open file has been created, how can it be occupied and exploited when an enemy pawn blocks a rook's advance?

Position 1 - Choosing a useful open file

White to move:

```text
8  . . . ♜ . . ♚ .
7  ♟ ♟ . ♟ . ♟ ♟ ♟
6  . . . . . . . .
5  . . . . . . . .
4  . . . . . . . .
3  . . . . . . . .
2  ♙ ♙ . . . ♙ ♙ ♙
1  ♖ . . . . . ♔ .
   a b c d e f g h
```

Explanation
- The c-, d-, and e-files are all open for White because no White pawn stands on any of them.
- The d-file has the clearest immediate objective: Black's pawn on d7.
- A rook on d1 would occupy the file and attack the pawn, but the pawn would also block the rook's advance.
- The rook would be blocked, not locked: it could still leave the file sideways.
- Occupation alone would therefore not conquer the file. White needs additional force.

Candidate-move table

```text
+------+-----------------------------+
| Move | Strategic purpose           |
+------+-----------------------------+
| ♖c1  | Occupies an empty file      |
| ♖d1  | Pressures the pawn on d7    |
| ♖e1  | Occupies an empty file      |
+------+-----------------------------+
```

Position 2 - Doubling against the objective

```text
8  . . . ♜ . . ♚ .
7  ♟ ♟ . ♟ . ♟ ♟ ♟
6  . . . . . . . .
5  . . . . . . . .
4  . . . . . . . .
3  . . . . . . . .
2  ♙ ♙ . ♖ . ♙ ♙ ♙
1  . . . ♖ . . ♔ .
   a b c d e f g h
```

Move table

```text
+------+----------+----------+----------------------------------------------+
| Move | White    | Black    | Strategic point                              |
+------+----------+----------+----------------------------------------------+
| 1    | ♖d2xd7   | ♜d8xd7   | The leading rook removes the blocking pawn.  |
| 2    | ♖d1xd7   |          | The rear rook replaces it on the 7th rank.   |
+------+----------+----------+----------------------------------------------+
```

After `1. R2xd7 R8xd7`:

```text
8  . . . . . . ♚ .
7  ♟ ♟ . ♜ . ♟ ♟ ♟
6  . . . . . . . .
5  . . . . . . . .
4  . . . . . . . .
3  . . . . . . . .
2  ♙ ♙ . . . ♙ ♙ ♙
1  . . . ♖ . . ♔ .
   a b c d e f g h
```

After `2. R1xd7`:

```text
8  . . . . . . ♚ .
7  ♟ ♟ . ♖ . ♟ ♟ ♟
6  . . . . . . . .
5  . . . . . . . .
4  . . . . . . . .
3  . . . . . . . .
2  ♙ ♙ . . . ♙ ♙ ♙
1  . . . . . . ♔ .
   a b c d e f g h
```

Explanation
- Black's rook could defend the pawn against one rook.
- With doubled rooks, White can exchange the leading rook for Black's pawn and rook.
- The rear rook then recaptures on d7, so White wins the pawn, removes Black's resistance, and penetrates to the seventh rank.
- This schematic tactic works because no additional defender or counter-tactic exists in the position.

Four Knights connection
- The principle is not tied to a particular opening.
- If central exchanges open a file, placing one rook on it may create pressure, but a second heavy piece may be needed to overcome a defended objective.
- Concrete calculation remains necessary before doubling or exchanging on the file.

Exercise
- [x] Notice that the c- and e-files are also open for White.
- [x] Explain that a rook on d1 is blocked from penetrating by the pawn on d7.
- [x] Identify a second rook as the additional force needed on the d-file.
- [x] Calculate that doubled rooks can win the d7-pawn in the schematic position.

Observations
- Source: `books/my-system-nimzowitsch-1930.txt`, Chapter II, Sections 1 and 3.
- The student correctly challenged the implication that the d-file was the only open file; the c- and e-files are open too.
- The student correctly distinguished occupation from penetration by noting that the White rook would be blocked by the pawn on d7.
- The student correctly chose a second rook to establish a preponderance on the file.
- The student correctly calculated that the doubled rooks win the d7-pawn in the schematic position.
