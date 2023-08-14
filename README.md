# optical_complex_reservoir_computing
Here I simulated an optical complex reservoir computing from a paper https://www.researchgate.net/publication/261067692_Experimental_demonstration_of_reservoir_computing_on_a_silicon_photonics_chip and checked if a proposed optical reservoir with one layer Neural Network can solve a temporal XOR problem.
The work is structured this way:
1. The input, delay line and optical reservoir system are modelled.
2. Then the input in correct form for a one layer NN is made from this reservoir simulation.
3. The model is trained with the use of K-Folds cross-validator.
4. The model is evaluated on separatly prepared inputs.

The conclusion is that the temporal XOR task can be solved with assistance of an optical complex reservoir computing with nonlinear nodes only on the photodetectors.
The reservoir is made genericly and in the paper it is shown that it may be used for solving other tasks, such as header and spoken digits recognition.
Thus, the reservoir as it is now may be used as a mixing signal black box, that simplfies NN models. It also can be more complex with added nonlinearity and weights training on the chip.
It is a promising structure able to solve some complex tasks in ML.
