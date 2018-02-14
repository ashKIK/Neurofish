# Neurofish
Integrating backpropagation neural network in Stockfish.

About :

Replacing stockfish static evaluation with backpropagation neural network(s) trained using a custom program.

Engine Modes : [UCI - Parameter]

0 - Logging SF evaluation(s).
    Log files can be processed by a custom position trainer program to train and test networks.

1 - Training. The original Stockfish eval is used to train the network specified by the "Neural Network File" whose evaluation is actually used for playing.

2 - Neural network specified by "Neural Network File" is used for evaluation (again not fully specified network or missing network file is also allowed but it will be freshly initialized and thus playing randomly).
    Parallel mode is on.
    
3 - Default Stockfish.

Engine Strength :

Neural Network trained on 1 million postions can play decent FM level chess.
