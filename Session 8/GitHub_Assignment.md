# GitHub Workflow and Hummingbird Data Analysis

## Part 1: Setting Up Your GitHub Account

* Step 1: Create a GitHub Account

1If you don’t already have a GitHub account, go to and create one.

What is GitHub? GitHub is a platform where developers and data scientists store, share, and collaborate on code and projects.

* Step 2: Follow the Instructor’s Repository and Account

Why? Following ensures you're connected to your instructor’s resources and updates.

After creating your account, perform these actions:

Follow this Repository:

Follow your Instructor’s Account: PanditPranav

## Part 2: Creating and Setting Up Your Repository

* Step 3: Use a Template to Create Your Own Repository

Navigate to this template repository:

Click on the green "Use this template" button and name your repository as: `MPM_200_<YourLastName>`.

Example: If your last name is Sharma, name your repository *MPM_200_Sharma*.

* Step 4: Invite Your Instructor

Go to Settings > Collaborators in your repository.

Add PanditPranav as a collaborator.

## Part 3: Understanding GitHub Operations

Commit: Saves changes to your local repository.

Push: Uploads committed changes from your local repository to the remote repository on GitHub.

Pull: Downloads updates from the remote repository to your local repository.

## Part 4: First Commit and Repository Setup

* Step 5: Edit and Commit Your `README.md` File

What is `README.md`? It’s a markdown file that provides a summary of your project.

Open the README.md file in your repository.

Write a 5-sentence summary about your first assignment on hummingbird data:

- What does your code do?

- What are the main features and functionalities?

- What outputs does the code generate?

After editing, commit your changes:

- Use a meaningful commit message, such as `Initial commit` with a project summary.

* Step 6: Organize Repository Structure

Folders in the Repository:

- Data: Upload your data files (e.g., .csv or .xlsx).

- Code: Place your analysis scripts here (e.g., .R or .ipynb files).

- Outputs: Store any results or plots generated by your code.

Upload the files and commit your changes. Use a descriptive message like:

- Uploaded data, code, and output files.

## Part 5: Updating and Analyzing Code

* Step 7: Modify Code for Visualization

Task: Update your code to create a timeline plot of monthly hummingbird admissions.

Differentiate between species groups using the *Species_group* column.

Your plot should show admissions for two distinct species groups over time.

* Step 8: Push Your Changes to GitHub

After completing the code changes:

- Save and commit your updated code locally with a message like:

- Added timeline plot of monthly admissions.

- Push the changes to your remote GitHub repository.

## Part 6: Syncing Updates from the Instructor

* Step 9: Pull Changes from Your Instructor

Your instructor will push new code for Backward Selection Analysis to your repository.

Use the Pull feature in GitHub Desktop to download and merge these updates into your local repository.

Why Pull? This ensures your local repository stays synchronized with the instructor's updates.

## Part 7: Exploring and Interpreting the GLM Model

* Step 10: Explore Model Properties

Use this command to view the properties of the fitted model:

```R

names(backward_model)

```

Q1: How many model properties are available?

* Step 11: Calculate Odds Ratios

Calculate odds ratios manually or use this command for a summary:

```R

library(sjPlot)

tab_model(backward_model)

```

Answer these questions:

- Q2: Which variable has the highest odds ratio for survival?

- Q3: Do the calculated odds ratios match the values provided by sjPlot?

Total Points: 30
