# Your Personal Journal 

## Executive Summary

This document is to explain the details and design of a web app designed to funciton as a personal Journal/Diary that will allow you to create an account with personal information that you will be able to login and out of from any computer that has an internet connection. You will be able to leave journal entries and read past journal entries, you will also be able to place each journal entry into several key catagories for easy searching in the future when looking for specific entries that you may have forgottent the date.

## Business Objectives

I beleive this project is important as it will allow individuals the ability to easily log organized experiences in a safe place for future viewing, and will also allow for each user to search and review past moments in life that may have just faded into the past. A goal for this project is to create a user friendly and secure journal to leave memories, experiences and for some users to simply vent about their stresses of the day to "Dear Diary" and have all there most intimate feelings in a secure place away from prying eyes. Main goals are to create a user login with credentials, a user friendly input system that logs written text with catagory labels to be applied to each entry. As well as a review page used to review past journal entries using a dynamic search bar to search entries by labels, emotion felt at time of journal entry, physical location at time of journal entry, date of journal entry, Emotion, Location, Date. The option to review and alter past journal entries, for those of us who want to change the past.

## Background

This project is being planned as a final project for my coding boot camp.

## Scope

Is included, ability to create account using required: custom username and password as well as email, optional real name and age. A home page to display most recent journal entry, a navbar with Home, New Entry, Review Past Entries and User Preferences. New entry will have a dynamic text entry system which logs the entries to a Database. Review entries will be a dynamic search option to search for past entries by label name. User preferences will be used for account infomation changes, username, password, and future developments.

## Functional requirements

First: Welcome page with User "Create account" button, that displays form fields to input new user information (Username, email, Password, Optional: Name(first and last), age. Also a submit form button to submit new user information. A confirmation email should be sent to the emial used to activate the account, once activated the user will be rederected to the home page.
Second: Home page will have the most recent journal entry displayed, if no entry can be displayed a button will be in its place named "Leave Journal Entry". On the home page will be a responsive Navbar at the top of the screen, with Home, Leave Journal Entry, Reveiw Journal Entries and User Preferences.
Third: Leave Journal Entry page will have a dynamic text inpu system with an current date and time that will be logged to the database with the log entry as a key to search by, there will also be an input to enter the emotion the user is feeling at time they leave the entry (requred to leave entry), as well as an input to leave the location the user is at when leaving the entry (optional for the user), and lastly a large text field for the journal entry itself, with a "Submit Entry" button right below the journal entry text field.
Fourth: Reveiw Journal Entries should have a search input with placeholder "Search" and a "Search" button beside it. The user will be able to search past entries using the Emotion, Location, Date key labels as well as exact phrases of 3 words or more. The page will dynamically show all entries with the corresponding label or matching phrase, if there are more than 10 results the page will display a "Next page" link which will take the user the the next 10 results, ect.... until the user gets to the end of the list, Once on the "Next Page" a "Previous Page" link will also be displayed. 
Fith: User Preferences will have the option to change username, password, or email, it will also allow the user to choose a color scheme for there account.


## Personnel requirements

I will need two experienced JavaScript programers, as well as a developer to work on the HTML elements and CSS options that the user will be allowed to choose from. Also a database handler to set up the mongoDB database where the Journal entries, credentials for secure login, and user account info will be stored.

## Delivery schedule

First phase will be HTML elements laid out in a responsive design, second phase will be adding the CSS to the bare HTML pages, third Phase will be working Javascript, Fourth phase will be server side and client side communication established, and the fith and final phase will be debugging any possible errors.

## Other requirements

The web app will be fully responsive, as to be functional on any device of any size, with breakpoints and working media queries.

## Assumptions

All libraries if any will be CDN's.

## Limitations

The only limitation on this project is time frame, the project must be completed within 80 hours (20 hours a week, four weeks) 

## Risks

Possible risks are, may be short staffed, which will mean overtime for developers present and an increase in cost, or a postponed deadline with an increase in time. The scope should remain unchanged. 
