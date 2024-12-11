README.md has been created.  
.md means MarkDown. Its a syntax that has its own version in github. It helps to play around the text easier such as bold, italicized, etc. Markdown Formatting: GitHub supports rendering Markdown files. When you name a README file with the .md extension, GitHub automatically recognizes the file as a Markdown file and renders it with proper formatting when viewed on the platform. This means headings, links, lists, and other Markdown syntax are displayed as intended, not just as plain text.  
No, Git does not index or track empty folders in your project. Git only tracks files, not directories. However, it does track the presence of a folder as long as it contains files.     
Yes, Does every Git project have a .git folder.    
The .git folder in Git projects is the core directory where Git stores all the metadata and history needed to manage the repository. It is essentially the brain of the Git version control system for a specific project. The presence of this folder allows Git to track changes, manage commits, store configuration, and handle various other version control operations.  
cd - change directory AKA change to home.    
ls- it lists the directory.    
The Linux Bash command pwd stands for "print working directory". It is used to display the current directory in the terminal where the user is working.  
a. working directory b. staging directory  c. .git repository. Working Directory: Where you make changes to files. Staging Area: Where you prepare changes before committing. Repository: Where committed changes are stored as part of the version history.     
A Version Control System (VCS) is a tool that helps manage and track changes to files or code over time. It allows multiple users to collaborate on a project, record modifications, and revert to previous versions if needed. VCS keeps a history of changes, making it easier to identify who made what change, when, and why. This is crucial for software development, document management, and any collaborative work where tracking changes is important.  
a. Each person working on the project has clone of the central repository on their device. b. Each person has a back up of the data. c. Data cannot be loss. d. Can handle large projects with people sharing the data. e. There is less chance of errors. f. Minor/Major changes can be tracked easily so no one gets confused between the different versions.  
a. Local VCS b. Centralized VCS c. Distributed VCS  
Git is a distributed version control software and GitHub is the central remote repository.   
git status lists all new and modified files to be committed.    
git push -all - Stages the modified and deleted files without the newly-created files. It pushes all commits from the local repository to the remote repository, to place them permanently there so that they can be shared to others. 
git pull - It basically pulls the latest updated version from the remote repository to the local repository.  
Markdown is a way to style text on the computer. Basically, it can format the text (bold, italicized etc). It includes text and some non-alphabatical characters such as #,*    
We make the text bold in MarkDown by adding **text**.    
We make the text italic in MarkDown by adding *text*.       
git init  
./ means current, ../ means one time back (previous folder or file from the current one). . refers to the current directory. .. refers to the parent directory (one level up).   
I am able to see the files that I created on README.md folder for my project IDS2024F in DOWNLOADS folder of my computer. DOWNLOADS to IDS2024F to all the folders such as homework, quiz, readme.md etc. I am able to basically push the data from remote repository to the local respository. -rf command illustrates the modification in the data.  
Biomedical, Neuroscience, Cognitive Sciences and Neurobiology.  
Computer, Optimization, Simulations and Bayesian.  
Three major modern pillars of science: Experiment, Theory and Computation + Data  
Machine Learning, Data Analysis and Data Management.  
Coding, Stats, and Domain.  
A Data Scientist is someone who analyzes the data on a large scale with the help of Stats, coding, data represenation, data mining and computer algorithms. They are able to make conclusions out of the collected data and describe the trends as well.   
Absolute File Path. Definition: An absolute file path specifies the full path to a file or directory from the root of the file system.
Characteristics: It starts from the root directory (/ on Linux/Mac or C:\ on Windows). Always points to the same file or directory, regardless of your current location in the file system. Not portable, as it is specific to a particular system.
Relative File Path: Definition: A relative file path specifies the path to a file or directory relative to the current working directory. Characteristics:
Starts from the current directory (or another specified directory). Portable, as it can work in different environments as long as the relative structure remains the same. More flexible in collaborative projects. Which One is More Appropriate for GitHub Projects and Why? Relative File Paths are generally more appropriate for GitHub projects. Here’s why: Portability: GitHub repositories are often cloned by users to different locations on their own systems. A relative path works regardless of where the project is stored on a user's machine because it's always relative to the project directory. Consistency: When collaborators clone or work on a project, relative paths will always point to the correct location as long as the file structure is maintained. Absolute paths, on the other hand, may point to completely different locations on different machines. Collaborative Work: GitHub repositories are designed to be shared. Using relative paths ensures that everyone, regardless of their operating system or where they cloned the repository, will have the same file references.  
git help --all , git status.  
The Linux Bash terminal command cd ~ is used to change the current directory to the user's home directory.  
