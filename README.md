# Pandas Workout — 200 Exercises

My personal solutions to the 200 exercises from the Manning book:

> **Pandas Workout: 200 exercises to make you a stronger data analyst**
> *Reuven M. Lerner* · April 2024 · ISBN 9781617299728 · 440 pages

---

## About the Book

*Pandas Workout* hones pandas skills to a professional level through 200 exercises,
each designed to strengthen data-analysis abilities. The exercises use realistic
data from many sources: New York taxi fleet, Olympic athletes, SAT scores, oil
prices, and more. Each can be completed in ten minutes or less.

**Topics covered:**

- Clean data with less manual labor
- Retrieve and assign data using rows and columns
- Handle indexes, including hierarchical indexes
- Read and write CSV, JSON, and other common formats
- Process and manipulate textual data
- Work with dates and times
- Perform aggregate calculations on selected data subsets
- Produce attractive, useful visualizations

---

## Repository Structure

```
Pandas-Workout/
├── chapter_01_series/               # 7 exercises
├── chapter_02_data_frames/          # exercises
├── chapter_03_importing_exporting/  # exercises
├── chapter_04_indexes/              # exercises
├── chapter_05_cleaning_data/        # exercises
├── chapter_06_grouping_joining_sorting/         # exercises
├── chapter_07_advanced_grouping_joining_sorting/ # exercises
├── chapter_08_midway_project/       # project
├── chapter_09_strings/              # exercises
├── chapter_10_dates_and_times/      # exercises
├── chapter_11_visualization/        # exercises
├── chapter_12_performance/          # exercises
└── chapter_13_final_project/        # project
```

Each notebook follows the pattern:
- **Exercise** — problem statement and hints
- **Solution** — working pandas solution with explanation
- **Beyond the exercise** — further exploration

---

## Progress

| Chapter | Title | Exercises | Status |
|---------|-------|-----------|--------|
| 1 | Series | 7 | ✅ In progress |
| 2 | Data Frames | — | ⬜ Todo |
| 3 | Importing and Exporting Data | — | ⬜ Todo |
| 4 | Indexes | — | ⬜ Todo |
| 5 | Cleaning Data | — | ⬜ Todo |
| 6 | Grouping, Joining, and Sorting | — | ⬜ Todo |
| 7 | Advanced Grouping, Joining, and Sorting | — | ⬜ Todo |
| 8 | Midway Project | — | ⬜ Todo |
| 9 | Strings | — | ⬜ Todo |
| 10 | Dates and Times | — | ⬜ Todo |
| 11 | Visualization | — | ⬜ Todo |
| 12 | Performance | — | ⬜ Todo |
| 13 | Final Project | — | ⬜ Todo |

---

## Setup

```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate        # macOS / Linux
.venv\Scripts\activate           # Windows

# Install dependencies
pip install pandas numpy matplotlib jupyter

# Launch Jupyter
jupyter notebook
```

---

## Chapter 1 — Series

| Exercise | Topic |
|----------|-------|
| [Exercise 1](chapter_01_series/exercise_01_test_scores.ipynb) | Test scores |
| [Exercise 2](chapter_01_series/exercise_02_scaling_test_scores.ipynb) | Scaling test scores |
| [Exercise 3](chapter_01_series/exercise_03_counting_tens_digits.ipynb) | Counting tens digits |
| [Exercise 4](chapter_01_series/exercise_04_descriptive_statistics.ipynb) | Descriptive statistics |
| [Exercise 5](chapter_01_series/exercise_05_monday_temperatures.ipynb) | Monday temperatures |
| [Exercise 6](chapter_01_series/exercise_06_passenger_frequency.ipynb) | Passenger frequency |
| [Exercise 7](chapter_01_series/exercise_07_taxi_ride_lengths.ipynb) | Long, medium, and short taxi rides |

---

## References

- [Pandas documentation](https://pandas.pydata.org/docs/)
- [Manning book page](https://www.manning.com/books/pandas-workout)
- [Reuven Lerner's website](https://lerner.co.il/)
