# a1: Basic Tools I
### Preparation
1. Please read: (1) Freeman and Ross(2019), Chapters 1-4 and (2) O’Neil (2016), Introduction (pp. 1-14).
1. Download and install [Atom](https://atom.io/) or other text editor (if you prefer).
2. Download and install [Git](https://git-scm.com/).
3. Sign-up for a [GitHub](https://github.com/) user account.
4. Download and install [R](https://cran.r-project.org/) (optional for this assignment).
5. Download and install [RStudio](https://www.rstudio.com/) (optional for this assignment)

### Objectives
**Please note:** This assignment should be completed _individually_.

1. Demonstrate how to navigate the file system from the command line and manage files, with these and similar commands (see F&R, chap. 2)
```
pwd             # print working directory
cd <PATH>       # change directory to <path>
cd ..           # change to parent directory (go up)
ls              # list files of current directory
ls -las         # list files (show some details)

 mkdir <PATH>         # make a directory
rm <PATH>            # remove a file or directory
cp <PATH1> <PATH2>   # copy a file or directory
cat <FILENAME>       # display the contents of a file
```
2. Describe the purpose of git and GitHub (see F&R, chap. 3)
3. Demonstrate how to manage a project using git and GitHub, with these and similar commands (see F&R, chap. 3):
```
# Setting up basic identifying information
git config --global user.name <YOUR FULL NAME>
git config --global user.email <YOUR EMAIL ADDRESS>

 git clone <REPO_URL>             # Copy a repo to your machine
git status                       # Check the status of a repo
git add <FILENAME>               # Add file to staging area
git add .                        # Add all files in current directory to  staging area
git git commit -m "<A MESSAGE>"  # Make changes s
git push
```
4. Use markdown syntax to format document (see F&R, chap. 4)
5. Consider how data science can be both a **tool** and a **weapon**.

## Part I: The Command line
In the root directory you will find a file named ``Git-commands.md``. The purpose of this file is for you to demonstrate your knowledge of working with the terminal (because we can't otherwise know which commands you entered in the terminal). Think of it as a way to document the code that you used in the terminal to perform the assignment.

**Your work**: Following each prompt in the file ``Git-commands.md``, write the line of code that you would (did) use on the terminal to accomplish the task. You can then use this file as a reference for your own work. Make sure to save this file in your text editor, then add, commit, and push the changes to GitHub.

## Part II: Working with Markdown
### Background
Please read the following obituaries. Each of these people were extraordinary coders, thinkers, and innovators. As your read, consider their personal lives and their professional accomplishments:

* [Ada Lovelace](https://www.nytimes.com/interactive/2018/obituaries/overlooked-ada-lovelace.html)
* [Alan Turning](https://www.nytimes.com/2019/06/05/obituaries/alan-turing-overlooked.html)
* [Karen Spärck Jones](https://www.nytimes.com/2019/01/02/obituaries/karen-sparck-jones-overlooked.html)
* [Douglas Engelbart](https://www.nytimes.com/2013/07/04/technology/douglas-c-engelbart-inventor-of-the-computer-mouse-dies-at-88.html)

### Requirements
Now that you have read their obituaries, write a single-page markdown document that meets the following requirements.

1. **Content requirements**. Choose *two* of these extraordinary people and summarize their lives with the following information:
  * Full name
  * Photograph
  * Date of birth and death and age at death
  * Main area of research
  * Two key facts about their personal lives
  * Two key professional contributions
  * A key quotation from the obituary
  * A reflective paragraph. If you could, what question would you ask Lovelace, Turning, Spärck Jones, or Engelbart? Give your question and explain why you would ask it? (30-50 words)
  * A link to the obituary
  * A link to a Wikipedia entry.
1. **Presentation requirements.**
  * _Consistency_. Format each entry in the same manner.
  * _Simplicity_. Seek a simple, clear, even elegant presentation.
1. **Coding requirements**. To present the above information, _for each person_, use the following markdown elements:
  * A top-level heading
  * An unordered list
  * **Bold** and _italics_ for emphasis
  * An image tag to present a photograph (include the `ALT` tag and descriptive text for screen reader accessibility)
  * A blockquote to format the key quotation
  * A paragraph to present your reflective paragraph
  * Hypertext links to the obituary and to a Wikipedia entry.
1. **Filenames and directories requirements.**
  * Create two directories in `\images\photographs\people`, one directory for each person. Name the directories by the person's last name.
  * Put the two photographs into the respective directories
  * Your document should be named `README.md`, located in the root directory of your repository.
  * Once you are finished, add, commit, and push all changes to GitHub.

**Notes on Professional Practice**: (1) If you find a requirement _ambiguous_, that is, unclear ask your Teaching Assistant or post a question on Teams. Requirements should be _unambiguous_. Always resolve ambiguous requirements before designing and implementing solutions by **communicating directly** with your project manager or team member. (2) Before starting to code, read all of the requirements, draw a **hand-sketch** of your page design, and create a **todo list** of the steps you need to follow. It is almost always a good idea to do a bit of planning before starting to code.

## Part III: Data Science: Tool for Good or Weapon?
A. Data science can be weapon, a tool that harms human beings. As we shall see, O'Neil (2016) presents a devastating critique of data science. We'll explore her arguments in some detail, but to start please answer these two questions from pages 1-14:
  1. By quoting from O'Neil (2016), define "Weapon of Math Destruction" (30-50 words).
  2. Give an example of a WMD (30-50 words).

B. Data science can also, of course, also be a tool for good. It can, for example, be used to make discovers about our social and natural worlds. One recent discovery made possible by data science is found in the paper by Wang, Stanovsky, Weihs, & Etzioni (2019). Please browse this paper but please note: We do not expect you to understand the full paper in detail. Now, answer this question:
1. What research question did Wang et al. (2019) ask and what did they find? (about 50 words)

**Submission requirements.** Please create a file, named `data_science.md`, located the root directory of your repository. Write your answers with markdown in that file. Please format your answers neatly. Once you are finished, add, commit, and push all changes to GitHub.

Wang, L. L., Stanovsky, G., Weihs, L., & Etzioni, O. (2019). Gender trends in computer science authorship. CoRR, abs/1906.07883. Retrieved from http://arxiv.org/abs/1906.07883




![An figure with a blue square and green circle.](/images/example1.png "Example")

Figure 1. This is an example figure, with caption and credit. (Credit: INFO-201 Course materials.)
