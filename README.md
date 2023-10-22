# Orange, A Xiangqi Chinese Chess Engine

Authors: Daniel Tan, Xiaofan Sun

This Xiangqi Chinese Chess Engine is named after the famous ancient Chinese manual "Secret of the Orange".
This project has both a Xiangqi Graphical User Interface and a UCCI (Universal Chinese Chess Interface)
protocol complaint Xiangqi Engine. This project supports Windows, Mac, and Linux.

## Graphical User Interface Features
* Drag and Drop to move pieces
* Click to move pieces
* Psuedo Legal Move Generation
* Implements UCI (Universal Chess Interface) Protocol as well as UCCI (Universal Chinese Chess Interface)
* Can do human vs computer, computer vs computer
* Parse and load FEN strings
* Multi engine support
* UCI/UCCI Engine Options
* Windows, Mac, and Linux support
* Chess Clock with Increment
* Blindfold Mode
* Drawing Arrows with Right Click
* Display Engine Lines

## Xiangqi Artificial Intelligence Engine
* UCCI Protocol

### Board Representation
* 90 square board
* Psuedo Legal Move Generation
* Staged Move Generation

### Search
* Negamax Search with Alpha Beta Pruning
* Principle Variation Search
* Iterative Deepening
* Aspiration Window Search

### Pruning
* Reverse Futility Pruning
* Null Move Pruning w/ Endgame Verification
* Delta Pruning
* Razoring
* Mate Distance Pruning

### Extensions
* Singular Search Extensions
* Check Extensions

### Transposition Table
* 16-byte transposition table hash entries
* Zobrist Hashing with Incremental Update
* Prefetch Transposition Table Entries
* Depth Preferred + Random Replacement Scheme

### Move Ordering
* Principle Variation Move Ordering
* MVV-LVA (Most Valuable Victim, Least Valuable Attacker)
* Killer Move Ordering
* Countermove Move Ordering
* History Move Ordering
* Countermove History Move Ordering

### Evaluation
* Efficiently Updatable Neural Networks with Incremental Update
* 2 Hidden Layers
* Supports AVX2, SSE, and CPU without SIMD
* Handcrafted Evaluation with Piece Square Tables



