# Student Performance Prediction

## Overview

This project focuses on predicting the performance of high school students in mathematics based on various factors, such as demographic information and educational background. The dataset used in this project contains information collected from three high schools in the United States.

## Motivation

The motivation behind this project is to explore the relationship between various factors and student performance. This project also aims to build a model that can predict the performance of a student based on these factors.

## Dependencies

- [Python 3.8.5](https://www.python.org/downloads/release/python-385/)
- [Jupyter Notebook](https://jupyter.org/install)
- [NumPy](https://numpy.org/install/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [Matplotlib](https://matplotlib.org/stable/users/installing.html)
- [Seaborn](https://seaborn.pydata.org/installing.html)
- [scikit-learn](https://scikit-learn.org/stable/install.html)


## Dataset

The dataset used in this project is named `exams.csv` and is located in the `data/` directory. It contains the following columns:

- `Gender`: The gender of the student (male/female)
- `Race/ethnicity`: The student's racial or ethnic background (Asian, African-American, Hispanic, etc.)
- `Parental level of education`: The highest level of education attained by the student's parent(s) or guardian(s)
- `Lunch`: Whether the student receives free or reduced-price lunch (yes/no)
- `Test preparation course`: Whether the student completed a test preparation course (yes/no)
- `Math score`: The student's score on a standardized mathematics test
- `Reading score`: The student's score on a standardized reading test
- `Writing score`: The student's score on a standardized writing test

## Project Structure

The project follows the following directory structure:

```
student-performance-prediction/
├── data/
│   └── exams.csv
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   └── model_training.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Usage

1. Start by cloning the repository:

```bash
git clone https://github.com/your-username/student-performance-prediction.git
cd student-performance-prediction
```

2. Create a virtual environment and activate it:

```bash
python3 -m venv env
source env/bin/activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Start the Jupyter server:

```bash
jupyter notebook
```

5. Open the `notebooks/` directory and run the notebooks in order.

## Contributing

Contributions to this project are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
```