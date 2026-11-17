# Strategy

The engine reconstructs the board from FEN, generates pseudo-legal moves, filters
moves that expose its king, and searches two plies beyond each candidate with
alpha-beta pruning. Captures are ordered first. Evaluation uses standard piece
values plus a small center bonus. Search depth is fixed, so repeated trials produce
the same moves and replay state.
