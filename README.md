# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

#What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
GitHub is a platform that provides hosting for software development and version control using Git.It allows very many developers to work on projects collaboratively and be able to track what is changed by others and also manage the code well
PRIMARY FUNCTIONS AND FEATURES:
Version Control,has a distributed version control system that is able to track changes made in code.Devs will have different versions of their code and also work on different branches.
Repo which stores projects and contains all the files and history which can be seen by everyone.
Pul Requests which is a way devs use to make changes to the repository.In other cases it can be reviewed,discussde and approve changes before being merged
Project Management which GitHub allows teams to track bugs,tasks using something called Issues.Where auser can assign issues to someone to link them to specific commits
Continuous Intergration and Continuous Development which github intergrates with various tools that would build,test and ddeploy code changes automatically
HOW IT SUPPORTS  COLLABORATIVE DEVELOPMENT:It enables teams to work together well,manage complicated codebases and maintain high quality software.

#Repository in GitHub:
#What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.
A GitHub repository is a storage space where the code is kept.Where each repo contains project files and hisory.
HOW TO CREATE A NEW REPOSITORY AND ELEMENTS:
1.Sign into account at GtHub.com
2.click + icon top roght of page then select new repository
3.Fill in the repo details which include:Rpository name,description about the project which is optional,choose whether the repo should be public or private,initialize README and click box if you want that,add.gitignore which tells GiHub which files to ignore in project,once done click CREATE REPOSITORY
ESSENTIALS OF A REPO:Establish a very clear branching strategy to manage different versions ande features aof your project.
Issues and Pull request which can be created to to help contributors with relevant information whenchanges are reported.
LICENSSE which is import if one wants others to use,modify or contribute to your code coz it defines terms under which code can be used.
.gitignorefile that will specify file Git should ignore so as to prevent sensitive information being tracked.
README.md which is what one sees the moment they visit your repository.

#Version Control with Git:
#Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
It is the process of managing and tracking changes to a file and project.It also allows different devlopers to coolaborateon a projectefficiently.
WHY IT IS IMPORTANT:Collaboration as it allows many people to work on the same project without overwritting each others chabges
Backup:The  entire project history is stored in version contril system that will act as backup ,even if locally lost it can be restored remotely
Developers can create branches to experiment new features without affecting the mmain code base and if it works it could be murged to main branch.

#Branching and Merging in GitHub:
#What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches in Git are separate lene of development.Where one can create a branch to work on features,fix bugs or even do individual experiment.
IMPORTANCE: They allow developers to work on a new featurefrom main codebase which mean the ongoing development is not affected
Collaboration where many developers can work on different branches simultaneously,enabling parallel development of different taks which in the end improves team work.
Allows for pull requests where developers can submitt changes for review if they pull request from their branch to the main one
It improves code stability coz by using branchesthe main one remains stable and production ready.Beacuse new features are normally merged after being tested properly.
It makes it easy to undo changes safely if something goes wrong after merging because it allows one to revert the marge.
PROCESS OF CREATING BRANCH,MAKING CHANGES AND MERGING:
1.git checkout main which switches to main main branch
2.Git pull origin master to fetch latest changes from remote repoand merge with local main
3.git checkout -b feature-branch-name which creates and switches to new branch
4.git add .stages modified files
5.git commit -m "Initial commit" which commits all staged changes with the message
6.git push origin feature-branch-name which pushes branch to remte repository under branch name
7.To pull request you go to GitHub and get yor repo and click create pull request which changes get merged with main branch.
8.git merge main which intergrate latest changes from main branch
9.git commit -m "Resolved merge conflicts"
10.git checkout main
11.git pull origin main
12.git merge feature-branch-name

Pull Requests and Code Reviews:

#What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
It is a feature that allows other developers to notify team about changes made in a branch,requesting if they could be rev9iewed and merged with main.
WHY IT IS IMPORTANT:
1.Collaboration: They enable collaboration among team members, making it easier to discuss and refine code before it’s merged.
2.Transparency: Pull requests provide a clear history of what changes were made, why, and by whom, which is crucial for project documentation and accountability.
3.Automated Testing: Integration with CI/CD tools allows automatic testing of changes, reducing the risk of introducing bugs into the main codebase.
In summary, pull requests in GitHub are a vital part of collaborative development, 
Steps to create and review a pull request
git checkout -b feature-branch to make changes to your code
git add .
git commit -m "Changes to be made"
git push origin feature-branch
Visit GitHub and navigate to my repository
Click the pull request option 
Create pull request to ask that your changes to be merged into the main branch and provide a small description of the changes and important information

GitHub Actions:

#Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
Introduction to Visual Studio:

#What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual Studio is an IDE that used by developers to create applications that include mobile,web apps using languages such as Python and JavaScript
Has a comprehensive IDE hat has everything one will need to write,debug code icluding compilers and debuggers
Builtin Git intergration that allows developers to manage repositories,commit and push changes from it
Has tools that can be used for team collaboration that supports continous development and deployment
Visual Studio is good for large and complex projects that might require IDE with deep compatibility into ecosystem of Microsoft while Visual Studio Code is for developers who look for light editor that can be customized to ones prefference.
Visual Studio is for large projects and has very good features that include debugging tools,database intergration  and supports heavy languages while Visual Studio Code can run across all platforms making it versatile for developers working on different opertaing systems

Integrating GitHub with Visual Studio:
#Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Debugging in Visual Studio:

#Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Edit and Continue which allows one to make changes to code while debugging without stopping.Since you can modify the code,recompile it with the changes taking place immediately
IntelliTrace which actually records events and photos of the code as it runs.One can go back to see how the application changed when a certain line of code was added hence,making easier to find the issues
Exeption Helper window always provide detailed information about it ,type and message making it easier to fix exceptions(Visual Studio)
Locals window available in Visual Studio code shows varriables under the current scope with theircurrent values and it updates the code as you continue coding.
Step Over which can be executed by using F10 carry out the next line of code without interferring with methods.It normally skips over method calls when keeping attention to how the inner will work hence saving time
So the tools will help identify and resolve issues quickly improving the quality of code
Collaborative Development using GitHub and Visual Studio:

#Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
Collaborative Development where both Visual Studio allows one to create and switch branches easily meaning devlopers can work on different features without damanging another persons work.Here one can use Git menu in Visual Studio to create a new branch,make changes and localluy commit and when ready to push you just create a PR directly using GitHub web interface
For code reviewing and Pull Requests where the pull request feature combine both GitHub and Visual Studio to support that.When the pull request is made ,team members can go through changes, leave their view and request for modifications.Visual Studio can also be configured to notify developers to allow them respond directly from the IDE
Deployments which Visual Studio intergrate with Azure to allow developers to easily deploy applications directly from the IDE to Azure.In return the GitHub Actions can be used to automate the deployments ensuring smooth delivery of project processs.
(From VS Code Docummentation)
GitHub Pages and Wikis can be used to host project docummentation which can easily be updated from Visual Studio(Github Wiki documentation)
Visual Studio Live Share allows developers to share their codding sessions with others in real time advocating for pair programming and also debugging(From VS code Live Share Document in Google)
REAL WORLD EXAMPLE:(CASE STUDY)
A mama mboga sells her fresh fruits and vegetables in a kisok wants to expand her business by creating an online platform since she has realised,most university syudents like shopping online to avoid the hustle of looking for the goods manually.The platform is to help her reach more customers,provide delivery services and manage orders efficiently.A developer team has been tasked to build her this platform using GitHub and Visual Studio for collaboration
1.Team gathers information from her kiosk.Features of the app are like online catalog,shopping cart,payment intergration delivery system and inventory for the managemnt of her stock
2.Creation of a repository to host project and divided into directories such as frontend,backend and documentation
3.Wireframes and Mockups are created by the design team and then shared to GitHub repo for review
4.Branches for the Backend and Fronend teams created to allow the team work on different parts of the project at a go
5.The Frontend team will set up structure using HTM.CSS and JavaScript with React as framework.They will use Visual Studio Live Share to collaborate in real time, allowing them to refine the UI.Afterwords the code is pushed to GitHub and team members will reviewit,give feedback and suggest on improvements before being merged to main branch
6.The Backend team will work on APIs to handle use authentification,product management e.t.c.MySQL database will be set to store product details,customer information,orders,Database scripts are version and stored in GitHub repository.Then they are conffigured to run backend tests automatically when pull request is created to ensure APIs are working
7.Testing is done with trusted customers who will give feedback and changes made.It is then deployed to AWS.Here team will need CICD using GitHub Actionsso that future updates are tested and deployed automatically

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
