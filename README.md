🐦 TweetBox - A Simple Django Tweeting App
TweetBox is a minimalistic Twitter-like web app built using Django. Registered users can post tweets, and they can edit or delete only their own tweets. Other users can view all tweets but must register to post, edit, or delete tweets.

✨ Features
📝 User Registration & Login

🐦 Create Tweets using Django Forms

✏️ Edit/Delete only your own tweets

👀 View all tweets (publicly visible)

🔐 Authentication-protected tweet management

🛠️ Tech Stack
Backend: Django (Python)

Frontend: HTML, CSS (Bootstrap )

Database: SQLite (default with Django)

Forms: Django Forms (no third-party form libraries)

Home Page showing tweets

Registration Page

Tweet creation form

Edit/Delete buttons only for the tweet owner


⚙️ Key Functionalities
Registration & Login: Handled using Django’s built-in authentication.

Tweet Model: Stores tweet content and user (ForeignKey).

Permissions: Only tweet owners can see "Edit" and "Delete" options.

Forms: Django Forms used for tweet creation and editing.
