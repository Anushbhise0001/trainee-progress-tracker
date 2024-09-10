# Instructions for Using the Trainee Progress Tracker Repository

Welcome to the Trainee Progress Tracker repository! This guide will help you understand how to use this repository, fork it, complete your tasks, and raise a pull request.

## Table of Contents
1. [Repository Structure](#repository-structure)
2. [How to Fork the Repository](#how-to-fork-the-repository)
3. [How to Copy and Modify the Technologies Folder](#how-to-copy-and-modify-the-technologies-folder)
4. [How to Complete Tasks](#how-to-complete-tasks)
5. [How to Raise a Pull Request](#how-to-raise-a-pull-request)
6. [Additional Resources](#additional-resources)

## Repository Structure

### Technologies
- Each technology folder (e.g., `html`, `css`, `javascript`) includes:
  - `EssentialTopics.md` - Key topics for the technology.
  - `assessments.md` - Details of assessments.
  - `projects.md` - Details of projects.

### Students
- `students.md` - List of all trainees with their names, company names, and GitHub repository links.
- `companyname/yourname/technologies/` - Folder where trainees should copy the `technologies` folder and modify it.

### Lectures
- Each day folder (e.g., `day-1`, `day-2`) includes:
  - `lecture-details.md` - Information about what was covered on that day.

## How to Fork the Repository

1. **Go to the Repository:**
   - Visit the [Trainee Progress Tracker Repository](https://github.com/your-repository-link).

2. **Fork the Repository:**
   - Click on the "Fork" button at the top right of the page.
   - This will create a copy of the repository in your GitHub account.

3. **Clone Your Fork:**
   - Open your terminal and run:
     ```bash
     git clone https://github.com/your-username/trainee-progress-tracker.git
     ```
   - Replace `your-username` with your GitHub username.

## How to Copy and Modify the Technologies Folder

1. **Navigate to Your Forked Repository:**
   - Open the cloned repository on your local machine.

2. **Copy the Technologies Folder:**
   - Copy the entire `technologies` folder from the root directory.
   - Create a new folder at `students/companyname/yourname/technologies/` in your forked repository.
   - Paste the `technologies` folder into this new directory.

3. **Modify the Technologies Folder:**
   - Update the `EssentialTopics.md`, `assessments.md`, and `projects.md` files in your copied `technologies` folder according to your tasks and progress.

## How to Complete Tasks

1. **Navigate to the Relevant Day:**
   - Go to the `lectures` folder and open the folder corresponding to the day you are working on (e.g., `day-1`).

2. **Review Lecture Details:**
   - Open `lecture-details.md` to see what was covered during the lecture.

3. **Complete the Assigned Tasks:**
   - Follow the tasks listed in the `tasks.md` file (if applicable).
   - Implement the tasks in your local repository.

4. **Commit Your Changes:**
   - Add your changes to the staging area:
     ```bash
     git add .
     ```
   - Commit your changes with a descriptive message:
     ```bash
     git commit -m "Completed tasks for Day X"
     ```

5. **Push Your Changes:**
   - Push your changes to your forked repository:
     ```bash
     git push origin <branch-name>
     ```
   - Replace `<branch-name>` with a branch name following the format `day-<day-number>-<your-name>`.

## How to Raise a Pull Request

1. **Go to Your Forked Repository:**
   - Navigate to your forked repository on GitHub.

2. **Create a Pull Request:**
   - Click on the "Pull Requests" tab.
   - Click the "New Pull Request" button.
   - Choose the branch you pushed your changes to and compare it with the `main` branch of the original repository.

3. **Submit the Pull Request:**
   - Add a title and description for your pull request.
   - Click the "Create Pull Request" button to submit it.

4. **Review and Merge:**
   - The repository maintainer will review your pull request and provide feedback.
   - Once reviewed, your pull request may be merged into the main repository.

## Additional Resources

- [GitHub Docs - Fork a Repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
- [GitHub Docs - Create a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/creating-a-pull-request)

If you have any questions or encounter issues, please contact us at [your-email@example.com](mailto:your-email@example.com).
