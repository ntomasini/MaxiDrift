# MaxiDrift
A python code to simulate maxicircle drift in a hybrid
We implemented a discrete-generation Monte Carlo approach in which each parasite is represented by a “kinetoplast” containing a fixed number of maxicircles (labeled as “A” or “B,” corresponding to parental origin), and the population evolves for 150 generations. In every generation, each kinetoplast’s maxicircles are duplicated, randomly shuffled, and split into two sets, representing daughter parasites. If this procedure yields more parasites than a specified maximum population size (set to 10,000 parasites), a random subset of 10.000 parasites is chosen to remain in the population. In each generation the number of kinetoplasts that have exclusively “A” or exclusively “B” (indicating fixation) versus those that retain both types (not fixed) were recorded. Different initial proportions of A and B maxicircles (e.g., 50%, 75%) and a range of total maxicircles per parasite (from 8 to 100, in increments of 8) were tested. With each combination ten replicates were generated to capture stochastic variability. The simulation outputs, stored as CSV files, include the proportions of kinetoplasts that are fixed for A, fixed for B, or remain mixed at each generation

Steps
1. click on MaxicircleDriftModel.ipynb
2. click on Open in Colab
3. Connect the virtual machine
4. Select the parameters
5. Run the cells
