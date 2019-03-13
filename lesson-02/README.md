<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>

# Github Desktop, Github Pages

GitHub is the largest code host on the planet with over 11.9 million repositories. Git is a distributed revision control and source code management (SCM) system with an emphasis on speed.

Gaining an understanding of its features opens to developers a new and liberating approach to source code management. The surest path to mastering Git is to immerse oneself in its utilities and operations, to experience it first-hand.

## What are we doing today?

-   Github Desktop
-   Github Pages
-   Task: Make your very first website!

## Github Desktop

### Normal Git commands

Normally, to use Git and Github, we would need to use the _terminal_ on our computers to save our code in the cloud. Here's what it looks like:

Initializing a repository

```bash
git init
```

Cloning a repository

```bash
git clone https://github.com/wes-chen/build-a-website.git
```

Pulling the most recent changes from your repository

```bash
git pull
```

Committing some changes in your local machine

```bash
git commit
```

Pushing your changes to the **internet** (Github)

```bash
git push origin [branch-name]
```

![Git Workflow](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/gitLocalWorkflow.png)

### Github Desktop to the rescue!

Fortunately, you don't have to learn this terminal stuff until you get to college.

Github Desktop makes it easy for us to do all of these operations with the click of a few buttons!

Let's try to pull our repository from last week, edit some files, commit our changes, then push it back to Github!

If you weren't here last week, no worries! [Here](https://wes-chen.github.io/build-a-website/lesson-01) is last week's lesson. Please [create a Github account](https://github.com/join) and follow [this guide](https://guides.github.com/activities/hello-world/) to make your very first repository!

1.  Sign in to Github Desktop

![Github Desktop Login](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-first-screen.png)

Sign into Github Desktop with your user credentials.

2.  Clone your repository from the cloud.

Select a repository to clone from Github. In this case it should be your hello-world repository that you made last week.
![Github Desktop Clone Step 1](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-no-repos.png)

Clone your repository into your local machine wherever you want to store your files.
![Github Desktop Clone Step 2](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-clone-a-repo.png)

Congrats! You've successfully cloned your repository from the cloud.
![Github Desktop Clone Step 3](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-repo-view.png)

3.  Make a few edits!

![Editing my files original](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/text-editor-original-text.png)
This is what I originally have in my README.

![Editing my files edited](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/text-editor-edited-text.png)
I've edited my text!

4.  Commit your changes to git.

![Github Desktop Commit](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-view-changes.png)
Remember to write a meaningful [commit message](https://chris.beams.io/posts/git-commit/).

5.  Push your changes to the repository.

![Github Desktop Ready to Push](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-ready-to-push.png)
Now that I've committed something, I'm ready to push to the internet!

![Github Desktop Pushed](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-pushed.png)
I've pushed!

![See changes on Github](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-my-changed-repo.png)
And now I can see my changes reflected on github.

## Github Pages

Github has a cool feature where you can host your own website! All you need to do is create a repository named [your username here].github.io and it'll automatically host your website at [your username].github.io. Isn't that cool?

[This tutorial](https://www.thinkful.com/learn/a-guide-to-using-github-pages/) runs through the basic workflow of using Github Pages. However, instead of the terminal stuff, follow these steps:

1.  TODO

TODO add info about Github Pages

## Next Time

Next time, we learn about HTML. If you are a proactive student, please run through this [codecademy tutorial](https://www.codecademy.com/learn/learn-html) at your own pace before the next lesson.
