# Short Response Questions

1. If you are collaborating with a classmate what is the first thing that each of the team members needs to do? Why is it important to do this step?

> The team members all must **create a branch and work on branch** in their own respective codespace. We must avoid putting our work on main or else we can't merge our work together. Since main is the *base workspace*, the whole group's version is supposed to be the same version, no changes.

2. Why do developers use branches.

> Developers use branches in order to **perform bugfixes, add files, and experiment with code**. This can also apply to *collaboratives projects* where when you do a pull request, the *branch's name* **tells the other members what new information is being added or fixed**.

3. What is git? Whatis github? How does gitand github work together?

> Git is a *open source control system* that is **accessible in computers or any electronic device**. You can write lines of codes in git in order to **branch and/or merge your work**. Github is a *website* that is more **lenient and more user friendly way of working with git**. Github is based off of the git language and by following the same logic, you can easily make your passion projects by yourself or with others.

4. What is wrong with the following command sequence? What should be the correct command sequence?

```
git commit -m "saving work"
git add .
git push
```

> The command sequence is wrong. The developer got the last command placement right ,but `git add .` is supposed to be in front of `git commit` or else the **rest of the saving process fails**. This is because "git add ." adds a file for you to stage/lets "git commit" happen in the first place. without "git add ." being first, git commit would be adding a message to nothing and git push would be sending no update to the repositories.

This is the **correct sequence**:

```
git add .
git commit -m "saving work"
git push
```
