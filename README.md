# ZeeTech Public Website

To contribute, you can use Netbeans or any other HTML/CSS/Javascript editor that supports Git versioning system. It is recommended to use Netbeans, so here's the URL:
https://netbeans.org/downloads/start.html?platform=windows&lang=en&option=all

# Connecting to Github

If you're using Netbeans, here's the steps to connect your local machine to this repo.

1. On Netbeans, click on Team > Git > Clone...
2. Enter "https://github.com/ZeetechUOW/public-web.git" to the repo URL and fill in your GitHub credentials on the appropriate fields
3. Click next through all prompts, you can change your project directories, but please don't change the project name / folder name
4. If prompted to create a project, select not to
5. Your zeetech project should be listed on the Projects tab in Netbeans
6. Right click that project and select Git > Remote > Pull
7. Enter your credentials, and select the origin/master branch when prompted
8. Done

# Committing and Pushing

You can edit them htmls and view your changes locally on your machine by opening index.html on your browser of choice.
To have your changes be updated to zeetech.ml, you'd need to commit and push the changes. Here's the steps:

1. If you added more files (images, js, etc) to the project that you want to upload to the repo, select all the added files or directories in the Projects tab and right click > Git > Add
2. Right click edited files and select Git > Commit
3. Enter a commit message if necessary, and commit
4. Then, upload the changes by right click the edited files > Git > Remote > Push
5. Enter your and the repo credentials, select the origin/master branch, and push
6. If push fails for whatever reasons, you might need to pull your project again to sync them
7. Select merge when prompted, and then try to push again
8. If merging fails, then you have conflicting changes! discuss with the team before proceeding.

It is recommended to pull the repo before you start editing changes to avoid changes conflict. Especially if you know that someone else had been working on the repo.
