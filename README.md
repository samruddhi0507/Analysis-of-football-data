# Author : Samruddhi Randive

## Task : Analysis of Football data 

[player_2020.CSV](https://github.com/samruddhi0507/Analysis-of-football-data/files/6526874/player_2020.CSV)

### Technical stack : Pandas, Matplotlib, seaborns

####  step 1: Reading the data from source


{
 "metadata": {
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.3-final"
  },
  "orig_nbformat": 2,
  "kernelspec": {
   "name": "Python 3.8.3 64-bit ('base': conda)",
   "display_name": "Python 3.8.3 64-bit ('base': conda)",
   "metadata": {
    "interpreter": {
     "hash": "bdff06bd94e17c36ce62dbd42a532c4255a44c9d38880a633082aa091992cee7"
    }
   }
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2,
 "cells": [
  {
   "source": [
    "# Author : Samruddhi Randive\n",
    "\n",
    "## Task 1 : Analysis of football data\n",
   
    "\n",
    "## Technical Stack  : Sikit Learn, Numpy Array, Pandas, Matplotlib"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Importing the required libraries\n",
    "from sklearn.model_selection import train_test_split \n",
    "from sklearn.linear_model import LinearRegression\n",
    "import matplotlib.pyplot as plt\n",
    "import pandas as pd\n",
    "import numpy as np  "
   ]
  },
  {
