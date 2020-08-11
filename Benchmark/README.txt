This is a work in progress to implement a benchmarking tool for random number generators (RNGs). 
This benchmarking tool uses the maching learning algorithm presented in the previous code.

The user inputs a binary file containing the bits generated from the RNG.
We take the first 80,000,000 bits and split these bits for training, validation and testing.
After the testing process, the algorithm outputs a lower bound on the guessing probability of the RNG.

As mentioned, this is a preliminary work and we are still working on many areas for improvement.
For example, both the train-validate-test splitting ratio and the input bit length could be changed to user-input variables as well.

If you have any comments or suggestions, please do not hesitate to contact us and let us know.
