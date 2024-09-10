# Trainee Progress Tracker

Welcome to the Trainee Progress Tracker repository! This repository is designed to help you manage and track your progress throughout your training program. Follow the instructions below to get started.

## Table of Contents

- [Repository Structure](#repository-structure)
- [How to Use This Repository](#how-to-use-this-repository)
- [How to Fork and Submit a Pull Request](#how-to-fork-and-submit-a-pull-request)
- [Managing Daily Tasks](#managing-daily-tasks)
- [Resources](#resources)

## Repository Structure

Here’s a breakdown of the repository structure:

- **technologies/**: Contains folders for each technology with essential topics, assessments, and projects.
  - **html/**, **css/**, **javascript/**, **git-github/**, **nodejs/**, **expressjs/**, **mongodb/**, **reactjs/**, **nextjs/**
    - `EssentialTopics.md`: List of essential topics.
    - `assessments.md`: Details of assessments.
    - `projects.md`: Details of projects.
- **students/**: Contains information about students and their work.
  - **students.md**: List of all students, their companies, and links to their repositories.
  - **companyname/yourname/technologies/**: Folder for each student's work with modified essential topics, assessments, and projects.
- **lectures/**: Contains details of daily lectures.
  - **day-1/**, **day-2/**, **day-3/**, etc.
    - `lecture-details.md`: Details of what was covered on that day.
- **README.md**: This file.
- **instructions.md**: Instructions for using the repository.

## How to Use This Repository

1. **Fork the Repository**:
   - Click on the "Fork" button at the top right of this page to create your own copy of this repository.

2. **Clone Your Fork**:
   - Use the following command to clone your fork to your local machine:
     ```bash
     git clone https://github.com/your-username/trainee-progress-tracker.git
     ```
   - Replace `your-username` with your GitHub username.

3. **Create a Branch**:
   - Create a new branch for your work:
     ```bash
     git checkout -b companyname/yourname
     ```
   - Replace `companyname` and `yourname` with your company's name and your own name.

4. **Copy and Modify the Technologies Folder**:
   - Copy the `technologies` folder to your student folder:
     ```bash
     cp -r technologies students/companyname/yourname/technologies
     ```
   - Modify the contents of the `technologies` folder in your student directory as needed.

5. **Make Your Changes**:
   - Add or modify content in the `EssentialTopics.md`, `assessments.md`, and `projects.md` files.

6. **Commit and Push Your Changes**:
   - Commit your changes with a meaningful message:
     ```bash
     git add .
     git commit -m "Completed tasks for day X"
     ```
   - Push your changes to your fork:
     ```bash
     git push origin companyname/yourname
     ```

7. **Create a Pull Request**:
   - Go to the GitHub page of your fork and click on "New Pull Request".
   - Select your branch and create a pull request to the `main` branch of the original repository.

## Managing Daily Tasks

Each day's work should be tracked under the corresponding day folder in the `lectures` directory. For details of daily tasks, refer to the `lecture-details.md` files for each day.

## Resources

- [GitHub Documentation](https://docs.github.com/)
- [Markdown Guide](https://www.markdownguide.org/)

Feel free to reach out if you have any questions or need assistance!

Happy coding!

