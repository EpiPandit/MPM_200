## Step 1: Download and Install Anaconda
### Substep 1.1: Go to the Anaconda Download Page
- Open your web browser and navigate to the [Anaconda download page](https://www.anaconda.com/products/distribution).
- You should see a page similar to the one below:

### Substep 1.2: Select the Correct Version
- Choose the appropriate version of Anaconda for your operating system (Windows, macOS, or Linux).
- Select the **Python 3** version, as it is the recommended version for this course.

### Substep 1.3: Download the Installer
- Click on the download link to start the download process.
- Wait for the download to complete.

### Substep 1.4: Install Anaconda
- Run the downloaded installer.
- Follow the installation instructions. Here are some key steps:
  - Accept the terms of the license agreement.
  - Choose the installation location.
  - Decide whether to add Anaconda to your PATH (recommended for ease of use).
  - Complete the installation.

## Step 2: Install R Kernel
### Substep 2.0: Open Anaconda Navigator or Command Line
- After installing Anaconda, open Anaconda Navigator or your command line interface.

### Substep 2.1: Create a new R-related environment in Anaconda
- ```bash
  conda create r_env
  ```
- before we move ahead, activate the new `R_env` before moving ahead
- ```bash
  conda activate r_env
  ```
### In this new environment install R
```bash
  conda install c conda-forge r-base
  ```

### Connect this with Jupyter 
In the same environment 
```bash
  conda install jupyter
  ```
#### Start R console in the r_env
```bash
  R
  ```
```bash
  install.packages('IRkernel')
  IRkernel::installspec()
  ```

```bash
  q()
  ```
## Step 4: Start a New Jupyter Notebook
### Substep 4.1: Launch Jupyter Notebook
- Open Anaconda Navigator and click on the "Launch" button under the Jupyter Notebook section.
- Alternatively, you can open a terminal or command prompt and run:
  ```bash
  jupyter notebook
  ```
- This will start the Jupyter Notebook server, and you can access it through your web browser.

### Substep 4.2: Create a New Notebook
- In the Jupyter Notebook interface, click on the "New" button to create a new notebook.
- Select the R kernel from the dropdown menu.

## Step 5: Solve the Exercise
### Substep 5.1: Load Necessary Packages
```R
# Install necessary packages if not already installed
install.packages('beepr', type = 'binary')
install.packages('tidyverse', type = 'binary')
install.packages('ggplot2', type = 'binary')
install.packages('dplyr', type = 'binary')

# Load the packages
library(beepr)
library(tidyverse)
library(ggplot2)
library(dplyr)
```

## Getting ready with GitHub for upcoming classes.
## Step 4: Create a GitHub Account and Follow Relevant Pages
### Substep 3.1: Create a GitHub Account
- Open your web browser and navigate to the [GitHub sign-up page](https://github.com/join).
- Fill in the required information:
  - Username
  - Email address: use uc davis email id, so as to make sure that you get the _pro_ account.
  - Password
  - Verification code (if prompted)
- Complete the sign-up process.

 GitHub Sign-up Page

### Substep 3.2: Follow EpiPandit Lab and Pranav Pandit GitHub Pages
- Navigate to the [GitHub page of EpiPandit Lab](https://github.com/EpiPandit).
- Click the "Follow" button to follow the EpiPandit Lab.

 Follow EpiPandit Lab

- Navigate to the [Pranav Pandit's GitHub page](https://github.com/PanditPranav).
- Click the "Follow" button to follow Pranav Pandit.

 Follow Pranav Pandit

### Substep 3.3: Follow the Course-Specific GitHub Repository
- Navigate to the GitHub repository specific for the course ([MPM-200](https://github.com/EpiPandit/MPM_200/tree/main)).
- Click the "Watch" or "Star" button to follow the repository.

 Follow Course Repository

