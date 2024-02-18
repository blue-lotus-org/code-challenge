## Challenge ID: `#Lotus001`
**Objective**: Develop a Python application to simulate the progression of generations, from parents to children and then to their offspring, across 10 generations, with a focus on genetic diversity and family tree visualization.

**Key Requirements**:

1. **Generation Rules**:
    - Each person can have 0 to 6 children.
    - The probability of having a specific number of children is as follows: 0 children (20%), 1 child (not specified, adjust probabilities accordingly), 2 children (30%), 3 children (25%), 4 and 5 children together (20%), and 6 children (5%).
    - The simulation starts with 10 initial parents.
    - Span 10 generations, with each generation equivalent to 30 years.
    - Children from different families in one generation can pair to become parents in the next generation, ensuring no siblings become a couple.

2. **Application Development**:
    - Utilize **PyQt5** for the UI design, allowing users to input or adjust the starting number of parents, the probabilities of the number of children, and the total number of generations.
    - Incorporate a **network chart** to visualize the family branches.
    - Display a summary table showing the population sum of each generation.

3. **Programming Tasks**:
    - Code must be optimized for performance and adhere to secure coding practices.
    - Utilize a library such as **NetworkX** to manage and visualize family branches effectively.
    - Outputs should include:
        - A table indexed by family and generation.
        - A branches chart showcasing the connections between generations.

**Detailed Guidance**:
- **UI Design**: The interface should be user-friendly, allowing for easy modification of simulation parameters and clear display of results.
- **Data Handling**: Implement an efficient data structure to track family relationships and generations dynamically.
- **Visualization**: Explore effective ways to represent complex family trees and generation data, ensuring clarity and accessibility for users.

**Deliverables**:
- A fully commented Python script that fulfills the above requirements.
- Documentation on how to run the simulation and interpret the results.

**Output Challenge**:
- Branches chart
- Table of details
- save functionality for `.txt` and `.csv`
- Show the complexity of your algorithm

> You can extend functionality as you want. Output can be creative, but with same task.

## Rewards:
- First place 1000 usdc
- Second place 500 usdc
- Third place 500 usdc

## Any questions from:
- https://www.linkedin.com/company/bluelotus-corp

> Challenge is **open**

## Where to send answer:
- clone this `repo`
- push your answer into `https://github.com/blue-lotus-org/code-challenge/tree/main/completed`
- merge request, comment : "**Lotus001**"

![example branches](https://github.com/blue-lotus-org/code-challenge/blob/challenge/src/branch.png)
