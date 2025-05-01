# Bridge Hand Probability Analyzer

![Bridge Point Distribution](bridge_point_distribution.png)

This Python script calculates and visualizes the probability distribution of point values in a 13-card bridge hand according to standard bridge point counting rules.

## Point Counting System

The script uses the standard bridge point count:
- Ace = 4 points
- King = 3 points
- Queen = 2 points
- Jack = 1 point

## Features

- Calculates all possible 13-card combinations from a 52-card deck
- Determines the point value for each possible hand
- Computes the exact probability for each point total
- Generates a clean formatted table of results
- Creates a visual representation of the probability distribution

## Usage

1. Ensure you have Python 3 installed
2. Install required dependencies:

pip install matplotlib

3. Run the script:

python bridge_hand_analyzer.ipynb


## Output

The script will:
- Print a detailed table showing each point total, the number of combinations, and the probability
- Generate a PNG image of the probability distribution chart
- Highlight the most common point value

## Mathematical Basis

The calculation uses combinatorics to determine:
- The number of ways to get each combination of honors (Aces, Kings, Queens, Jacks)
- The number of ways to fill the remaining cards with non-honor cards
- The total number of possible 13-card hands (comb(52, 13) = 635,013,559,600)
