# MVC Tech Blog

## Overview
Tech Blog CMS is a CMS-style blog site where tech-savvy developers can share their insights, articles, and thoughts about the ever-evolving tech world. This project is built from scratch, follows the MVC architectural pattern, and is deployed on Heroku.

## User Story
As a developer who loves to write about tech:
- I wanted a CMS-style blog site
- So that I can effortlessly publish my tech-related articles and thoughts

## Acceptance Criteria
When using the Tech Blog CMS, here's what you can do:
- As a first-time visitor, you'll see the homepage with existing blog posts (if any), navigation links for the homepage and dashboard, and the option to log in.
- Clicking the homepage option takes you to the homepage.
- Clicking other navigation links prompts you to sign up or sign in.
- Sign up by creating your username and password. Click the sign-up button to save your credentials and log in.
- Returning users can sign in by entering their username and password.
- When signed in, you'll find navigation links for the homepage, dashboard, and the option to log out.
- Clicking the homepage option in the navigation takes you to the homepage, displaying existing blog posts with post titles and creation dates.
- Clicking on an existing blog post displays the post title, content, post creator's username, and creation date. You can also leave comments.
- Submit your comments, and they'll be saved. The post updates to show the comment, the comment creator's username, and the date created.
- In the dashboard, you can view your existing blog posts and add new ones.
- Adding a new blog post is a breeze; provide a title and content.
- Create your new blog post, and it's saved. You'll be redirected to an updated dashboard.
- Manage your existing posts in the dashboard, whether it's deleting or updating them.
- The navigation provides a log-out option for you to sign out.
- If you're idle for an extended period, you can still view posts and comments, but to add, update, or delete posts, simply log in again.

## Mock-Up
![Tech Blog CMS Mock-Up](mockup.png)

## Getting Started
To run this application, follow these steps:
1. Ensure the folder structure adheres to the MVC paradigm.
2. Utilize the `express-handlebars` package for Views.
3. Leverage `MySQL2` and `Sequelize` to connect to a MySQL database for Models.
4. Implement the `dotenv` package for environment variables.
5. Safeguard passwords with the `bcrypt` package.
6. Add authentication with `express-session` and `connect-session-sequelize`.
7. Finally, deploy the application to Heroku.

## Submission
I'm proud to share the completed Tech Blog CMS with you:
1. [Link to the deployed application](https://your-heroku-app-url.com)
2. [Link to the GitHub repository](https://github.com/Aliviahhilliard/MVC-Tech-Blog)

Feel free to explore the world of tech blogging with the Tech Blog CMS! Happy writing!
