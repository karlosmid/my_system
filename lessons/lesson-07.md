# Lesson 07 - Avoiding Pawn Hunting

Concepts
- Mobilizing the pieces is the most important opening task.
- Hunting a harmless wing pawn while development is unfinished usually wastes time.
- A gambit pawn should often be declined when accepting it lets the opponent drive a developed piece around.
- A central pawn is Nimzowitsch's exception: capturing it can weaken the opponent's center and create room for expansion.
- The purpose of taking a central pawn is positional conquest of the center, not merely material gain.

Strategic question
- When is winning a pawn worth interrupting development?

Position 1
After `1.e4 e5 2.Nf3 Nc6 3.Bc4 Bc5 4.b4`:

```text
8  ♜ . ♝ ♛ ♚ . ♞ ♜
7  ♟ ♟ ♟ ♟ . ♟ ♟ ♟
6  . . ♞ . . . . .
5  . . ♝ . ♟ . . .
4  . ♙ ♗ . ♙ . . .
3  . . . . . ♘ . .
2  ♙ . ♙ ♙ . ♙ ♙ ♙
1  ♖ ♘ ♗ ♕ ♔ . . ♖
   a b c d e f g h
```

Move table

```text
+------+--------+--------+------------------------------------------+
| Move | White  | Black  | Strategic point                          |
+------+--------+--------+------------------------------------------+
| 1    | ♙e4    | ♟e5    | Both sides occupy the center.            |
| 2    | ♘f3    | ♞c6    | Both sides begin development.            |
| 3    | ♗c4    | ♝c5    | The bishops enter active positions.       |
| 4    | ♙b4    | ♝b6    | Black declines the wing pawn securely.    |
+------+--------+--------+------------------------------------------+
```

Explanation
- After `4...Bxb4`, White can play `5.c3`, attack the bishop, and prepare central expansion with `d4`.
- Black would have to move the bishop again and lose time.
- With `4...Bb6`, Black avoids being driven around.
- White's `b4` does not itself develop a piece or support the center, so it does not give White a development advantage when Black declines the pawn.

Position 2
After `1.e4 e5 2.Nf3 Nc6 3.Bc4 Nf6 4.c3?`:

```text
8  ♜ . ♝ ♛ ♚ ♝ . ♜
7  ♟ ♟ ♟ ♟ . ♟ ♟ ♟
6  . . ♞ . . ♞ . .
5  . . . . ♟ . . .
4  . . ♗ . ♙ . . .
3  . . ♙ . . ♘ . .
2  ♙ ♙ . ♙ . ♙ ♙ ♙
1  ♖ ♘ ♗ ♕ ♔ . . ♖
   a b c d e f g h
```

After `4...Nxe4`:

```text
8  ♜ . ♝ ♛ ♚ ♝ . ♜
7  ♟ ♟ ♟ ♟ . ♟ ♟ ♟
6  . . ♞ . . . . .
5  . . . . ♟ . . .
4  . . ♗ . ♞ . . .
3  . . ♙ . . ♘ . .
2  ♙ ♙ . ♙ . ♙ ♙ ♙
1  ♖ ♘ ♗ ♕ ♔ . . ♖
   a b c d e f g h
```

Move table

```text
+------+--------+--------+------------------------------------------+
| Move | White  | Black  | Strategic point                          |
+------+--------+--------+------------------------------------------+
| 1    | ♙e4    | ♟e5    | Both sides occupy the center.            |
| 2    | ♘f3    | ♞c6    | Both sides develop.                      |
| 3    | ♗c4    | ♞f6    | Black develops and attacks the e4 pawn.  |
| 4    | ♙c3?   | ♞xe4   | Black captures a central pawn.           |
+------+--------+--------+------------------------------------------+
```

Explanation
- `4...Nxe4` is justified because the captured pawn is central.
- Black weakens White's center and gains room for central expansion.
- The strategic value is more important than simply being one pawn ahead.

Four Knights connection
- Early pawn captures should be judged by their effect on development and the center.
- A wing pawn is rarely worth repeated moves by an already-developed piece.
- A safely captured central pawn can be worth a tempo because it changes control of the most important opening area.

Exercise
- [x] Choose between `4...Bxb4` and `4...Bb6` in the Evans Gambit example and explain the choice.
- [x] Decide whether `4...Nxe4` in Position 2 is unjustified pawn hunting.

Answers
- The student chose `4...Bb6`, securing the bishop and avoiding further loss of time.
- The student correctly judged `4...Nxe4` to be justified because it weakens White's center.

Observations
- Source: `books/my-system-nimzowitsch-1930.txt`, Chapter I, Sections 7 and 7a.
- The student distinguished a distracting wing-pawn hunt from a strategically useful capture in the center.
- The central-pawn exception should be remembered as a positional idea: central conquest and elbow room are the aims, not material alone.
