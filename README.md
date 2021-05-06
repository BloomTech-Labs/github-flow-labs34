# Labs Github Flow

- The following is a guided project that will help you understand the git work flow that we use in Lambda Labs.

## Description

- Throughout your Lambda School experience thus far you have learned how to work with Git/GitHub and have had practice using the basic commands for staging, commiting, pushing and publishing your commits to a fork. Learning now, the rest of what you need in order to work as a productive member of a product organization will set you up for success not only in labs, but give you insight into what how the product teams work in the real world.

## Purpose

- Knowing a team work flow using Git/GitHub is absolutely vital for you to succeed as a tech professional. That is the purpose of this exercise.

## Objectives

- By the end of this guided project you will have demonstrated the following:
  - You will be able to create a _branch_ off of the **main** branch of a repository.
  - You will be able to submit a _pull-request_ from your feature branch onto the **main** branch.
  - You will be able to _merge_ the **main** branch onto your feature branch.
  - You will be able to resolve any _merge conflicts_ that come up.
  - You will be able to delete a feature branch.

## Introduction

The following is a list of steps and instructions on how to complete this guided project.

- **Step 1️⃣:** Clone this repository by clicking the green **Clone or Download** button in the top right.
  ![Clone/Download](https://tk-assets.lambdaschool.com/054e5ad4-75cd-4b98-b929-7bf453bc8263_ScreenShot2020-04-13at7.31.05AM.png)
- **Step 2️⃣:** CD into the repository and create a branch off of the main branch.
  - Name the branch **"feature/add-name"** `git checkout -b 'feature/add-name`
  - **note**: this is the naming convention you will use in Lambda Labs.
  - Once the branch is created run `git branch` to ensure that you've switched to the new branch. (You should be in the habit of doing this by the end of your first week in labs).
- **Step 3️⃣:** Now that you have created your branch you're ready to work on the repo. Our task for the day is to have you add your name to the list below (**note** the semantically chosen branch name you created coincides with the task at hand) the `### Your name` heading in this README.md file.
- **Step 4️⃣:** Run your typical staging, commit and publish commands:
  - `git status` , `git add <file-name>` , `git commit -m 'your message'` , `git push origin <branch-name>`.
  - 💥**note:** you're pushing to your branch NOT to the main branch. (!!VERY IMPORTANT!!)💥
- **Step 5️⃣:** Pull down the main branch onto your branch. The easiest way to do this is to simply run `git pull origin main` **but make sure you're on your branch first** `git branch`.
- **Step 6️⃣:** Resolve any merge conflicts.
  - You may see a merge conflict that looks something like this:
    ![merge conflict](https://tk-assets.lambdaschool.com/dd45683f-788d-4bd9-832e-ed901151615f_ScreenShot2020-04-13at8.38.36AM.png)
  - To resolve this, you need to go into that file (could be many files depending on how well you and your team are communicating) and remove the `<<<<<<< HEAD -stuff- ======= -stuff- >>>>>>> commit id` code and decide which lines of code to remove/keep.
  - `💡Pro Tip: Once you've done this a few times manually, VSCode has an amazing built in Merge Conflict extension that will step you through the process.`
  - **Repeat step 4️⃣**: At this point you have a _dirty_ commit history once again and you need to run your typical staging, commit and publish commands but update your message to say something about 'resolving merge conflicts'.
- **Step 7️⃣:** Open up your **Pull-request**. Now that you've resolved merge conflict and you're sure that your feature branch is up to date with main open up a pull-request:
  - ![pull-request1](https://tk-assets.lambdaschool.com/f7b3593f-00ab-4de6-a988-6afac8b49b25_ScreenShot2020-04-13at9.19.33AM.png)
  - ![pull-request2](https://tk-assets.lambdaschool.com/476e30e8-031a-43dd-9a75-bfec86b9b301_ScreenShot2020-04-13at9.19.49AM.png)
  - Be sure to add **reviewers** and follow the Pull-request template. (You will be getting trained/critiqued on pull-requests later on)

### Bernie Durfee
