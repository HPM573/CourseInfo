# Basic GitHub Operations

Watch this [short video](https://git-scm.com/video/what-is-version-control)
 to learn about the basics of Git and version control.

### To download a repository from GitHub:

1. Launch PyCharm, and if a project is open, closet it.
2. In the Welcome window, select **Project** from the left menu, and click on **Get from VCS** 
and select "Git" for Version control. 
3. Go to the main page of the GitHub repository you want to download and 
click on **Clone** button. Copy the link appeared next. It should be something like:
https://github.com/HPM573-S-24/hw_00-myname.
4. Go back to PyCharm, and paste the repository link into the URL text box.
5. Select the directory where you want the repository to be downloaded to a
nd click **Clone**. 
6. If prompted to 'Log In to Github', select **User Token...** and then click on **Generate...**.
7. Leave all default settings unchanged and click on **Generate token** at the bottom of the page. 
8. Copy the generated token (should be a long string of numbers and letters) and go back to PyCharm to enter it. 
7. Click **Log In** to open the project.

### To push the latest version of your project to GitHub:

1. Open your project in PyCharm, select **Git -> Commit** from the top menu. 
2. Make sure the folder that ends in "\.idea" is unchecked (this prevents GitHub from tracking user-specific settings; this is important when collaborating with others). 
3. Write your commit message (e.g., "implemented the function to calculate n!"), 
click on **Commit and Push**.
