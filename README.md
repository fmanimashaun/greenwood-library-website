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
    - home.html
    - about_us.html
    - events.html
    - contact_us.html

2. Add any random content into each of the files.

3. Stage, commit and push the changes directly to the main branch. (This is a simulation of the team's existing code base for the website)

**Morgan's Work: Adding Book Revviews**
1. Create a Branch for Morgan:
2. Switch to a new branch named **add-book-reviews**.
3. Add a new file **book_review.html** to represent the Book Reviews Section.
4. Add a random text content into the file.
5. Stage, Commit, and Push Changes with a message like "**Add book reviews section.**"
6. Push the **add-book-reviews** branch to GitHub.
7. Raise a PR for Morgan's work
8. Merge Morgan's work to the **main** branch

**Jamie's Work: Updating Events Page**

Repeat the same flow for Jamie's work on Events Page. Ensure Jamie's work is in **update-events** branch.
- Pull the latest changes from tge main branch into **update-events** before raising the PR.

### Solutions

#### 1. Create the HTML files with random content:

- In your VS Code, I created the following HTML files:

##### `home.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
</head>
<body>
    <h1>Welcome to Our Website!</h1>
    <p>This is the homepage.</p>
</body>
</html>
```

##### `about_us.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
</head>
<body>
    <h1>About Us</h1>
    <p>Learn more about our company and what we do.</p>
</body>
</html>
```

##### `events.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Events</title>
</head>
<body>
    <h1>Upcoming Events</h1>
    <p>Join us at our next event!</p>
</body>
</html>
```

##### `contact_us.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
</head>
<body>
    <h1>Contact Us</h1>
    <p>Get in touch with us for any inquiries.</p>
</body>
</html>
```

#### 2. Stage, commit, and push the changes:

After creating these files in the project, I use Git commands in the terminal (integrated in VS Code) to stage, commit, and push the changes to the main branch.

```bash
git add home.html about_us.html events.html contact_us.html
git commit -m "Add HTML files for homepage, about us, events, and contact us"
git push origin main
```

These commands will:

- `git add`: Stage the files for committing.
- `git commit -m "message"`: Commit the staged files with a message.
- `git push origin main`: Push the commit to the `main` branch on the remote repository.

#### 3. Create a new branch named add-book-reviews:

First, I make sure I am on the main branch, then create and switch to the new branch:

```bash
git checkout main          # Ensure you're on the main branch
git pull origin main       # Make sure your local branch is up-to-date
git checkout -b add-book-reviews  # Create and switch to the new branch
```

#### 4. Create the `book_reviews.html` file with random content:

In the newly created branch, I create the `book_reviews.html` file and add some random content.

##### `book_reviews.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Reviews</title>
</head>
<body>
    <h1>Book Reviews</h1>
    <p>Welcome to the Book Reviews section! Here you will find insightful reviews of various books.</p>
    <p>Stay tuned for more updates and reviews.</p>
</body>
</html>
```

#### 5. Stage, commit, and push the changes:

Now that I have added the `book_reviews.html` file, stage, commit, and push mjy changes to the `add-book-reviews` branch.

```bash
git add book_reviews.html   # Stage the new file
git commit -m "Add book reviews section"  # Commit the changes
git push origin add-book-reviews  # Push the new branch to GitHub
```

#### 6. Push the `add-book-reviews` branch to GitHub:

By running the above `git push` command, Il pushed the `add-book-reviews` branch to GitHub, where I can create a Pull Request (PR) if required.