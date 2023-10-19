Intro to Git- https://generalassembly.instructure.com/courses/161/pages/intro-to-git?module_item_id=2745

Git is a Version Control System (VCS) that records changes that are made to files over time.
    If something goes awry, this allows us to revert to previous states, which makes it much easier to work in teams as each member can make their own changes without affecting the main code, which can later be merged into the main code should no issues arise with those changes.

Git Vocabulary
    Repository- A copy of the projeft, that holds information about the who, what, and when of the project. Allows devs to track changes over time and revert to previous versions if necessary.

    Branch- An independent line of development within a repository, allowing different devs to work on different bugs and features all at the same time without affecting the main code.

    Remotes- A reference to a repository

Local Commands
    git init - initializes a new repository by creating a hidden .git directory within the current directory

    git add . - Adds all the files and folders in the current directory to the staging area, which is where they will be added to the next commit

    git commit -m "commit message" - provides a checkpoint where all the changes to the code can be saved. the -m allows us to add a message to the commit within quotes to provide a brief summary of the changes that were made

    git status - tells us what is happening in a local repository at any given moment

    git push origin main- pushes the commited changes back up to the github repository

Intro to GitHub- https://generalassembly.instructure.com/courses/161/pages/intro-to-github?module_item_id=2746

GitHub is the most prominent online storage space for collaborative work.
    Utilizes git to keep track of versions, issues, and requests for changes
    Also has the critical role of a cloud-based backup system

Difference between Git and GitHub
    Git provides a local repo on our computers
    GitHub provides a remote repo in the cloud

Forking, Cloning, and Pulling
    On GitHub click on the fork icon and then click on generate fork
    To Clone, click on the arrow in the code box, copy the HTTPS address, and then in the terminal type: git clone [paste copied https address here]
    To Pull, click pull requests on the nav bar and click on "New Pull Request" and then click "Create pull request". In the title, enter "[Your Name] | complete/incomplete" and in the comment box you can enter the difficulty of the assignment and talk about what difficulties were faced while doing the assignment, as well as a more detailed status of the assignment if incomplete. Then click "Create Pull Request" again at the bottom of the screen.
        Alternatively you can click on "Contribute" and then "Open pull request"
