# 24HrChallenge - Anonymous thought - Humza & Sammie

## Description

For this project we were tasked with creating a  place where people can write down their thoughts, whilst remaining anonymous. The following features were required:

* Your app should have a browser client allowing users to write a post with a title, a pseudonym and a body
* No login should be required to create a post or visit a post
* When a user hits 'publish', the post should be stored in a database and the client redirected to a show path
* The user should be able to access their post using that show path even after a server restart
* Edit and delete functionality is not required

This readme will detail how to set-up and install this application, the technologies used as well as the wins and challenges we came across druring this project. 

## Installation & Usage

### Installation

* Clone or download the repo.
* cd into server and run the following:
    * run `docker compose up`
* Then cd into the client side and run either a `http-server` or a `pyhton server`

### Usage

* From the landing page you can Enter a Title, a Pseudonym and Content for your thought
* You can click the `post thought!` button to be directed to a show page viewing your post

## Technologies used

* VScode
* GitHub
* Node
* Docker

## Wins and Challenges

### Wins

* We tackled an issue with acquiring the id of a post by using the title instead.
* using flexbox to lay out the page
* getting the database and docker to work

### Challenges

* Right at the end it was tricky to figure out how to generate a seperate show page as we struggled to find the id that was being produced with the posts.

# Enjoy! 😁
