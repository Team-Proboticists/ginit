# GINIT - Your First Introduction to GitHub!

This repository is an initial introduction to GitHub! Let's get started with some basics!

## What is Github?

GitHub is a tool for code storage and management. You can use GitHub by creating an account. It's free but unfortunately not Open Source, it's built on top of Git, the FOSS tool. To put it simply, GitHub lets you store your projects online, track changes to your code, and collaborate with others. It also provides features like repositories, branches, issues, and pull requests to make managing projects easier.

## Getting started!

To download Git, use the following links:

- [Git for Windows](https://git-scm.com/install/windows)
- **Unix/Linux:** Git is usually available through your system's package manager.

Then configure Git with:

```sh
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### SSH setup (Optional but Highly Recommended!)

For setting up SSH, please follow the steps given in [SSH setup](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

## Cloning a Repository

First, clone this repository locally:

```sh
git clone git@github.com:Team-Proboticists/ginit.git
```

SSH is the preferred method.

# Your First Git Workflow

## Switch to the Intros Branch

Switch to the branch used for collecting introductions:

```sh
git switch intros
```

## Add Your Introduction

Create a folder with your name.

Example:

```text
John_Doe
├── README.md
└── image.jpg
```

Inside `README.md`, write a short introduction about yourself. Include:

- Your name
- Your department/year
- Your interests
- Your hobbies
- Your favourite programming language
- Anything else interesting about yourself

Also add your image inside your folder. This will be used for our socials!

## Check Your Changes

Before committing, check your changes:

```sh
git diff
```

`git diff` shows the changes made since your last commit.

## Commit Your Changes

Add your folder:

```sh
git add Your_Name/
```

Create a commit:

```sh
git commit -m "Add my introduction"
```

A commit is a snapshot of your project at a particular point in time.

## Pull Latest Changes

Before pushing, update your local branch:

```sh
git pull origin intros
```

This helps prevent conflicts when multiple people are contributing.

## Push Your Changes

Upload your commit to GitHub:

```sh
git push origin intros
```

Your introduction should now be visible on GitHub!

# Your Task

1. Clone this repository.
2. Switch to the `intros` branch.
3. Create a folder with your name.
4. Add a `README.md` with a short introduction.
5. Add your image inside the folder.
6. Use `git diff` to inspect your changes.
7. Add and commit your changes.
8. Pull the latest version of `intros`.
9. Push your changes to GitHub.
10. Verify that your introduction is visible.

### Bonus

Edit your introduction and repeat:

**diff → add → commit → pull → push**

Don't worry if something goes wrong. That's part of learning Git. Git is basically a time machine for your code. 
