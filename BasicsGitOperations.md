# Basic GitHub Operations

Watch this [short video](https://git-scm.com/video/what-is-version-control)
 to learn about the basics of Git and version control. 

### To download a repository from GitHub:

1. Launch PyCharm, and if a project is open, closet it.
2. In the Welcome window, click on **"Check out from Version Control"** 
and select "Git". 
3. Go to the main page of the GitHub repository you want to download and 
click on **"Clone or download"** button. Copy the link appeared next.
4. Go back to PyCharm, and paste the repository link into the URL text box.
5. Select the directory where you want the repository to be downloaded to a
nd click Clone. 
6. Click Yes on the next window to open the project.

### To push the latest version of your project to GitHub:

1. Open your project in PyCharm, select **VCS -> Commit**. 
2. Make sure the folder that ends in "\.idea" is unchecked. 
3. Write your commit message (e.g. "implemented the function to calculate n!"), 
click on the arrow next to the Commit button and select **Commit and Push**.

### To create a GitHub repository from a PyCharm project: 

1. Create a **new PyCharm project**.
2. From the menu select 
**VCS > Import into Version Control > Share Project on GitHub**.
3. Give your repository a name and click **Share**. 
4. On the next window, make sure to **uncheck** the folder that ends in **"\.idea"** 
(this prevents GitHub from tracking user-specific settings; 
this is important when collaborating with others).
5. You may leave the **Commit Message** unchanged and click **OK**. 
