# team9-project1

Database
currentlty have two models
1. Default django user model
2. profile model(one to one relationship with user model..i.e one user is entitled to one profile)

admin details
username = 'admin'
password = 'admin1234'

we have four apps
1. magazine
2. blog
3. users
4. search

Magazine
This app has the basic templates and views
home page,  url = ''
about page,  url = '/about'
contact page,  url = '/contact'

Blog
just the blog page
blog home page, url = '/blog'

users
has the whole user registration and login forms and authentication with the user profile and edit user profile

registration page, url = 'users/register'....redirect to magazine home page if already logged in
login page, url = 'users/login'....redirect to magazine home page if already logged in
profile page, url = 'users/profile'....need to be logged in
edit profile page, url = 'users/edit_profile'....need to be logged in

search
untouched

NB: the templates and styling for the pages are still going to be edited...these are just dummy templates
Any questions can be asked on the group chat