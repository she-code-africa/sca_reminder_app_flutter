# sca_reminder_app_flutter
![ezgif com-gif-maker](https://user-images.githubusercontent.com/32166619/115328615-c2c13c00-a188-11eb-91fb-6b9037f97211.png)

## About the application
The reminder application is a type of time management application that is designed to alert the user of schedules that have been added to the application. The application currently uses the notification alert type technique, other suggested technique might be added later in the future.

This application offer robust features to become productive and organize, both personal and professional life, in an efficient manner. Users can set reminders notifications by creating a task and setting its due dates, notifications automatically pops up on the due date and few hours before the due date. 

## Folder Structure

### src

Since the main.dart file is out of src and we will only write the application codes in the src package. When main.dart will executex as root file, it would be redirected to the src\app.dart file which will contain all the MaterialApp/CupertinoApp components of the project.

business_logic: All the logical parts of the project will be located in this package.

    blocs: If you are following the BLoC pattern then you can keep your blocs here.
    models: Models/Pojo classes.
    services: There are three types of services - api_services, database_services, shared_prefs_services. You will put your specific types of codes in the specific type of service packages.
    utils: This package contains all the constants files.

### views

We will put our User Interface codes insides our views package.

    ui: All the User Interface code files.
    utils: This package contains the reusable widgets files and the constants value files.

# Contributor's Guide

'HOW TO CONTRIBUTE TO OPEN SOURCE' accepts PR's (pull requests) from **newbies**
only, this is to help **newbies** get familiar with the contribution processes.

Issues can be submitted by anyone - seasoned developers or newbies.

**Contents**

- [Getting Started](#getting-started)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Adding to the Main README](#adding-to-the-main-readme)
- [Adding to Non-English README](#adding-to-non-english-readme)
- [Helpful Resources](#helpful-resources)

### Getting Started

1.  If you are new to Git and GitHub, it is advisable that you go through
    [GitHub For Beginners](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
    **before** moving to Step 2.

2.  Fork the project on GitHub.
    [Help Guide to Fork a Repository](https://help.github.com/en/articles/fork-a-repo/).

    ![Illustration for How to Fork a Repository](https://hisham.hm/img/posts/github-fork.png)

3.  Clone the project.
    [Help Guide to Clone a Repository](https://help.github.com/en/articles/cloning-a-repository)

4.  Create a branch specific to the issue you are working on.

    ```shell
    git checkout -b update-readme-file
    ```

    For clarity, name
    your branch `update-xxx` or `fix-xxx`. The `xxx` is a short
    description of the changes you're making. Examples include `update-readme` or
    `fix-typo-on-contribution-md`.

5.  Open up the project in your favorite text editor, select the file you want
    to contribute to, and make your changes.

    If you are making changes to the `README.md` file, you would need to have
    Markdown knowledge. Visit
    [here to read about GitHub Markdown](https://guides.github.com/features/mastering-markdown/)
    and
    [here to practice](http://www.markdowntutorial.com/).

    *   If you are adding a new project/organisation to the README, make sure
        it's listed in alphabetical order.
    *   If you are adding a new organisation, make sure you add an organisation
        label to the organisation name. This would help distinguish projects
        from organisation projects.

6.  Add your modified
    files to git, [How to Add, Commit, Push, and Go](http://readwrite.com/2013/10/02/github-for-beginners-part-2/).

    ```shell
    git add path/to/filename.ext
    ```

    You can also add all unstaged files using:

    ```shell
    git add .
    ```

    **Note:** using a `git add .` will automatically add all files. You can do a
    `git status` to see your changes, but do it **before** `git add`.

6.  Commit your changes using a descriptive commit message.

    ```shell
    git commit -m "Brief Description of Commit"
    ```

7.  Push your commits to your GitHub Fork:

    ```shell
    git push -u origin branch-name
    ```

8.  Submit a pull request.

    Within GitHub, visit this main repository and you should see a banner
    suggesting to make a pull request. While you're writing up the pull
    request, you can add `Closes #XXX` in the message body where `#XXX` is the
    issue you're fixing. So an example would be `Closes #42` would close issue
    `#42`.

### Submitting a Pull Request

[What is a Pull Request?](https://yangsu.github.io/pull-request-tutorial/)

If you decide to fix an issue, it's advisable to check the comment thread to see if there's somebody already working on a fix. If no one is working on it, kindly leave a comment stating that you intend to work on it. That way
other people don't accidentally duplicate your effort.

In a situation whereby somebody decides to fix an issue but doesn't follow up
for a particular period of time, say 2-3 weeks, it's acceptable to still pick
up the issue but make sure to leave a comment.

*Note*: Every open-source project has a **CONTRIBUTING.md** file, please make
sure to read this before you open up a pull request, otherwise it may be
rejected. However, if you do not see any CONTRIBUTING.md file, you can send a
pull request but do it in a descriptive manner.

### Adding to the Main README

The
[main `README.md` file](https://github.com/freeCodeCamp/how-to-contribute-to-open-source/blob/master/README.md)
contains a list of useful resources for beginners who want to contribute to
open source.

You can contribute to this page by adding a Markdown formatted link.

It should look similar to this below.

```
- [Title of the page](www.applink.com/slug-name-here) - Add description of why I should look at this app
```

When in doubt, take a look at the current list items to get an idea of how you should format your contribution.

When adding your contribution to the list, please add your link to the most appropriate section. If you are unsure, feel free to ask in your pull requst or comment in an issue asking for guidance.

### Adding to Non-English README

The main `README.md` file is written in English. That file will be the template for all the other languages.

This repository is about contributing to open source and generally, translation is important to reaching diverse audiences. It is recommended that you provide language specific resources links instead of the Engligh resource links.

The non-English README files are named `README-XX.md`, where `xx` is the
[two letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
for the language.

You can contribute to the non-English README files by taking links that are in the English README but are not in the language of your choosing. When making a pull request with these changes, please tag someone who can verify your language contribution by adding `@` in front of their GitHub username to the pull request.

If your language does not exist yet, feel free to start it yourself. If you decide to do this, please add more than just the title. If you do not have the time to create one, feel free to
[create an issue](https://github.com/freeCodeCamp/how-to-contribute-to-open-source/issues/new/choose)
to crowdsource help.

Last, we want to link to beginner friendly labels. These are typically `Good First Issue` or something similar.

### Helpful Resources

- [Pro GIT Book](https://git-scm.com/book/en/v2)

- [Try Git](https://try.github.io/)

- [Git/ Git Hub on Windows](https://www.youtube.com/watch?v=J_Clau1bYco)
