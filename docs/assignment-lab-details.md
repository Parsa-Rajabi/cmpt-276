# Assignments & Labs

We are using GitHub Classroom to deliver the assignment and labs for this course. You will first need to create a GitHub account, and then you can accept each Class Activity. Once the assignment/lab is ready, the link will become active, and you will be able to accept the lab in your [GitHub.com](https://github.com/) account.

Once you click the link, a repository will automatically be created for you with instructions. You can then work on the assignments and labs, make commits, and push them to GitHub as often as you please. Once the deadline has passed, you will no longer be able to push any changes.

This the tentative schedule for all course assignments and labs, which is subject to change without notice. Please check on a regular basis for the most up-to-date schedule.
## Assignments

| Assignment | Due Date |     Link to Accept      |
| :--------: | :------: | :---------------------: |
|     A1     | Sept. 19 | [Accept A1 on Github]() |
|     A2     | Sept. 26 |                         |
|     -      |    -     |            -            |
|     A3     | Oct. 24  |                         |
|     A4     |  Nov. 7  |                         |

## Labs

| Labs  | Due Date |           Link           |
| :---: | :------: | :----------------------: |
| Lab 1 | Sept. 21 | [Accept Lab on Github]() |
| Lab 2 | Sept. 28 |                          |
| Lab 3 |  Oct. 5  |                          |
| Lab 4 | Oct. 12  |                          |
|   -   |    -     |            -             |
| Lab 5 | Oct. 26  |                          |
| Lab 6 |  Nov. 2  |                          |
| Lab 7 |  Nov. 9  |                          |
| Lab 8 | Nov. 16  |                          |
| Lab 9 | Nov. 23  |                          |

## Submission

### Canvas

All course content include assignments, labs etc. will need to be submitted on Canvas via the [assignment tab](https://canvas.sfu.ca/courses/79650/assignments). Not submitting on Canvas will be considered as a missed assignment/lab, which will result in a 0 grade for that assignment/lab. Follow the instructions below to understand how to use GitHub classroom.

### Github Classroom

Here are some instructions on how to start working on assignments/labs that are available on Github classrrom.

- Step 1: Accept assignment/lab with link above, and open a Terminal
- Step 2: Clone the repo on your local computer [View Tutorial / Common errors](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
  - `git clone https://...`
- Step 3: Navigate to that directory 
  - `cd /path/to/where/you/cloned/repo/`
- Step 4: Try to navigate the files and folders (if any) in your repo using the Terminal
- Step 5: Making changes based on instructions 
- Step 6: Commit your changes to the repository 
  - `git add -A or git add .`
  - `git commit -m "Insert your commit message here i.e. Updated file X"`
  - You can commit changes to your repository **as many times as you like before the deadline** (any commits after the deadline will be ignored)
- Step 7: Pushing the changes above
  - `git push` 
- Step 8: Copy your repository link and submit the link to [Canvas assignment](https://canvas.sfu.ca/courses/79650/assignments). After the deadline, we will begin marking submitted assignments.
    - The link will look something like this: `https://github.com/cmpt-276-fall-2023/cmpt-276-assignment-#-[YOUR GITHUB USERNAME]` for example, for A1, it will be `https://github.com/cmpt-276-fall-2023/cmpt-276-assignment-1-Parsa-Rajabi`

### Working with Git

1. Add file: `git add filename.format`
        e.g. `git add example.txt` (to add a text file named example)
    1b. You can commit all files in your directory by using either:
     - `git add .`
     - `git add -A`
2. Commit changes with a message: `git commit -m "type commit message here"` (make sure the commit message is meaningful)
3. Push changes: `git push`