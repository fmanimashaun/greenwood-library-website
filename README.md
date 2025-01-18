# Darey.io | CapStone Project - Git

## Enhancing a Community Library Website

**Background Scenario**

I'm part of a development team tasked with enhancing the website for the "**Greenwood Community Library**." 
The website aims to be more engaging and informative for its visitors. It currently includes basic sections: 
Home, About Us, Events, and Contact Us. Your team decides to add a "Book Reviews" section and update the "Events" 
page to feature upcoming community events.
I will simulate the roles of two contributors: "**Morgan**" and "**Jamie**". Morgan will focus on adding the "Book 
Reviews" section, while Jamie will update the "Events" page with new community events.

### Objectives

* Practice cloning a repository and working with branches in Git.

* Gain experience in staging, committing, and pushing changes from both developers.

* Create pull requests and merge them after resolving any potential conflicts.


### Setup

1. Create a Repository on GitHub:
Name it website-greenwood-library
Initialize it with a README.md file and clone it to your local machine.

### Tasks

1. In the main branch, using Visual Studio Code editor ensure there are files for each of the web pages.

* home.html

* about_us.html

* events.html

* contact_us.html

2. Add any random content into each of the files.

3. Stage, commit and push the changes directly to the main branch. (This is a simulation of the team's existing code base for the website)

The following commands were used to stage, commit and push:

`git add . `

![created-files](images/created-html-files.png)

![added-files](images/Added-files.png)


`git commit -m "main branch commited"`

![commited-files](images/commited-files.png)


`git push -u origin main`

![alt text](images/Pushed-files.png)


**Morgan's Work: Adding Book Reviews**

1. From the main branch I Created a Branch for Morgan: 
Add-book-reviews

2. I Switch to a new branch named add-book-reviews. 

Below command was used:

git branch

git checkout -b Add-book-reviews

![morgan-branch](images/morgan-branch.png)


3. I Added a new file book_reviews.html to represent the Book Reviews Section:

![added-bookreview-file](images/added-bookreview-file.png)


4. I Added a random text content into the file. (Have a thorough review)

5. Stage, Commit, and Push Changes with a message like "Add book reviews section."

6. Push the add-book-reviews branch to GitHub.
 
Below commands was used: 

`git add .`

`git commit -m "Add-book-reviews branch"`

`git push -u origin Add-book-reviews`

7. I Raised a PR for Morgan's work

![morgan-PR1](images/morgan-PR1.png)


8. Merged Morgan's work to the main branch

![morgan-merged-PR](images/morgan-merged-PR.png)


Jamie's Work: Updating Events Page
Repeat the same flow for Jamie's work on Events Page. Ensure Jamie's work is in update-events branch.

1. From the main branch I created a Branch for Jamie: update-events and pushed 

2. I switched to a new branch named update-events

Below commands was used:


` git checkout -b uodate-events`

![jamie-branch](images/jamie-branch.png)

3. I added a new file book_reviews to represent the Book Reviews section:

[book_review](book_review.html)

4. I added a random text content into the file.

5. Stage, Commit and Push Changes with a message like  "Added reviews section"

6. Push the update-events Branch to Github.

Below commands was used:

`git add .`

`git commit -m "update-events branch"`

`git push -u origin update-events`

![jamie-branch-pushed](images/jamie-branch-pushed.png)


7. I Raised a PR for Jamie's work


8. Merged Jamie's work
