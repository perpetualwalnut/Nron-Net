# Nron-Net
An experimental 3,000 neuron Neural Network. Can be expandable with some work. Needs performance improvments.

I haven't tested this system with any real data yet. Currently testing this system with some dynamic data. Try it! watch the first six outputs count to the supervise inputs.

You can change how many simulated neurons their are by changing the parameters at the top of the source AND header files. It's messy in there, don't get lost.
The number of neurons needs to be a multiple of the number of inputs and you need to make sure that layers is equal to that 
multiple. It is threaded, but make sure the number of neurons and inputs are both evenly divisible with the number of threads
created or bad things might happen. It's a work in progress. Enjoy.
