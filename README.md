# README

# Database (DB)
## ERP (Entity Relationship Diagram)
![erd database](/docs/images/erd.png)

# DB Tables
I made 3 tables for my app, User, Tweet and Profile. User stories the user information like password etc. Tweet stores the information message that a user tweets and the profile table stores information about the user. Each user has one Profile and many Tweets.

## User
    - email
    - password

## Profile
    - avatar
    - first_name
    - last_name
    - country (belongs_to)

## Tweet
    - message
    - user_id (belongs_to)
# Pages
## homepage
    - tweets on page
    - login/ log out

## tweet show page
    - see tweet
    - edit tweet (if logged in)

## profile page
    - first_name, last_name
    - tweet count
    - avatar
    - country
    - edit ability