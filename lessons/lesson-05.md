# Lesson 05 - Development With Purpose

Concepts
- Development means bringing the whole army into play, not moving one piece repeatedly.
- A pawn move is not development by itself. In the opening it should help build, support, or attack the center.
- A piece move has purpose when it helps the collective development of the position.
- A piece move is suspect when it ignores the center and lets enemy central pawns drive it away.

Strategic question
- If White develops pieces but does not build a center, what can Black's central pawns do to those pieces?

Position
After `1.♘f3 ♞c6 2.e3 e5`:

```
8  ♜ . ♝ ♛ ♚ ♝ ♞ ♜
7  ♟ ♟ ♟ ♟ . ♟ ♟ ♟
6  . . ♞ . . . . .
5  . . . . ♟ . . .
4  . . . . . . . .
3  . . . . ♙ ♘ . .
2  ♙ ♙ ♙ ♙ . ♙ ♙ ♙
1  ♖ ♘ ♗ ♕ ♔ ♗ . ♖
   a b c d e f g h
```

After `3.♘c3 ♞f6 4.♗c4 d5`:

```
8  ♜ . ♝ ♛ ♚ ♝ . ♜
7  ♟ ♟ ♟ . . ♟ ♟ ♟
6  . . ♞ . . ♞ . .
5  . . . ♟ ♟ . . .
4  . . ♗ . . . . .
3  . . ♘ . ♙ ♘ . .
2  ♙ ♙ ♙ ♙ . ♙ ♙ ♙
1  ♖ . ♗ ♕ ♔ . . ♖
   a b c d e f g h
```

After `5.♗b3 d4`:

```
8  ♜ . ♝ ♛ ♚ ♝ . ♜
7  ♟ ♟ ♟ . . ♟ ♟ ♟
6  . . ♞ . . ♞ . .
5  . . . . ♟ . . .
4  . . . ♟ . . . .
3  . ♗ ♘ . ♙ ♘ . .
2  ♙ ♙ ♙ ♙ . ♙ ♙ ♙
1  ♖ . ♗ ♕ ♔ . . ♖
   a b c d e f g h
```

Strategic questions
- Which White moves develop pieces?
- Which White pawn move helps the center, and which central pawn move is missing?
- Why does Black's `...d5-d4` make White's development look awkward?
- Which White piece has already lost time?

Explanation
- White has moved both knights and the king bishop, but the development is not secure because White has not built a real pawn center.
- The move `e3` opens the bishop, but it does not occupy the center with a pawn on `e4` or `d4`.
- Black's `...e5` and `...d5-d4` use central pawns to gain space and push White's pieces away from useful squares.
- White's bishop has already moved from `f1` to `c4` and then to `b3`. That repeated movement is a loss of time during the development stage.
- Nimzowitsch's rule is not "never move pawns." His rule is stricter: in open games, pawn moves should help build, support, or attack the center.

Move table

```
+-------+---------+---------+------------------------------------------------+
| Move  | White   | Black   | Strategic point                                |
+-------+---------+---------+------------------------------------------------+
| 1     | ♘f3     | ♞c6     | Both sides develop a knight.                   |
| 2     | ♙e3     | ♟e5     | White opens a bishop; Black occupies center.   |
| 3     | ♘c3     | ♞f6     | White develops, but the center is still thin.  |
| 4     | ♗c4     | ♟d5     | Black's center pawn attacks the bishop.        |
| 5     | ♗b3     | ♟d4     | White loses time; Black's center gains space.  |
+-------+---------+---------+------------------------------------------------+
```

Four Knights connection
- In the Four Knights, both sides usually develop quickly with `♘f3`, `♞c6`, `♘c3`, and `♞f6`.
- The lesson is that those knight moves are not enough by themselves. The central pawn structure still decides whether the pieces can stand actively or get driven back.
- A move like `d4` or `...d5` should be judged by its central purpose: does it occupy, support, attack, or liquidate the center?

Exercise
- [x] In the final diagram, name White's repeated piece move and explain why Black's `...d4` is a developing-stage success.

Answer
- White's repeated piece move is the bishop move `♗c4-b3`, forced by Black's `...d5`.
- Black's `...d4` is a good development-stage move because the pawn enters White's half of the board, attacks the knight on `c3`, and forces White to spend time moving a developed piece instead of developing another unit.

Observations
- Source: `books/my-system-nimzowitsch-1930.txt`, Chapter I, Sections 1-2.
- Nimzowitsch defines development as a collective process: one or two developed pieces do not mean the whole position is developed.
- He treats pawn moves as aids to development, not as developing moves by themselves.
- His warning for open games is severe: every pawn move costs time unless it helps build, support, or attack the center.
- The example shows a "pawn-less" or center-light development being punished by the demobilizing force of Black's central pawns.
- Chat lesson completed: the student identified that `...d5` attacks the bishop and costs White a tempo, and that `...d4` forces a developed White piece to move instead of letting White continue development.
