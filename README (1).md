# Probability Distributions Analysis

## Project Overview
This project demonstrates the use of probability distributions in Python through simulations and visualizations. It uses examples related to student placements, job offers, student marks, waiting times, and random values.

The analysis is implemented in the Jupyter Notebook `Probability_Distributions_Analysis.ipynb`.

## Distributions Covered

1. **Bernoulli Distribution – Student Placement**
   - Simulates the placement status of 1,000 students.
   - Uses a probability of placement of `0.39`.
   - Calculates the number of placed and not-placed students, along with the placement percentage.
   - Displays the outcomes in a histogram.

2. **Binomial Distribution – Student Placements**
   - Simulates the number of students placed across 100 trials.
   - Uses `n = 500` and placement probability `p = 0.55`.
   - Visualizes the simulated results with a histogram.

3. **Poisson Distribution – Job Offers**
   - Simulates the number of job offers using an average rate (`mu`) of 3.
   - Generates 100 random observations and plots their frequency.

4. **Normal Distribution – Student Marks**
   - Simulates student marks using a mean of 70 and standard deviation of 10.
   - Displays the distribution using a density histogram.
   - The notebook contains two visualizations of this same normal-distribution setup.

5. **Exponential Distribution – Waiting Time**
   - Simulates waiting times using a scale parameter of 5.
   - Generates 100 observations and plots their density.

6. **Uniform Distribution – Random Values**
   - Generates 100 random values between 0 and 100.
   - Displays the values using a density histogram.

## Technologies and Libraries
- **Python** – programming language
- **NumPy** – numerical operations and calculations
- **Matplotlib** – data visualization and histograms
- **SciPy** – probability distributions and random sampling
- **Jupyter Notebook** – interactive environment for running the analysis

## Installation

Make sure Python is installed. Install the required libraries with:

```bash
pip install numpy matplotlib scipy jupyter
```

## How to Run

1. Download or clone this project.
2. Open a terminal in the project folder.
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Probability_Distributions_Analysis.ipynb`.
5. Run the notebook cells in order.

## Project Structure

```text
.
├── Probability_Distributions_Analysis.ipynb
└── README.md
```

## Output
Running the notebook produces printed placement statistics and histograms for the probability-distribution simulations.

## Note
The notebook uses random sampling. Therefore, the exact simulated counts and histogram shapes may vary each time the cells are executed.

## Author
Add your name and academic details here.
