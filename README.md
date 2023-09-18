# challenge_portfolio_DorStr

This a portfolio created during Dare IT Challenge - "Zostań testerem manualnym".

## TASK 1
### Subtask 1
My test score: 8/10
### Subtask 3
My name is Dorota. I passed the ISTQB Foundation Level exam in June. I would like to broaden my knowledge and gain a more practical approach to testing. I joined this project to build a complete portfolio and become capable of working in my dream job!
### Subtask 4

#### General purpose

Scouts Panel is an application for football scouts to track players, games and their statistics. It enables adding new players and games and generating reports after logging in.

#### Functionalities

 - log in/log out
 - list players
 - add player
 - wiev players' matches
 - download list of players (.csv file)
 - filter players 
 - search players/matches/positions/clubs

The application allows to change language between Polish and English.

#### Interface

The app interface is very simplistic, with minimal formatting. Some functionalities, such as 'add player,' should be relocated to the left-hand menu instead of being the sole option in the 'Shortcuts' section at the center of the page. The placement of the logo above the 'dev team contact' button is somewhat unconventional. The app's current design lacks intuitiveness, and it should offer more user-friendly navigation. The 'Statistics' panel, which may not be as crucial, could potentially be moved to the footer of the page for a more balanced layout.


#### Bugs found in the application

* Login Issues:
Difficulty logging in using Mozilla Firefox and Google Chrome with valid usernames and passwords. (Correct login in Chrome using incognito mode).

* Form Validation Issues:
Input validation issues, such as allowing special characters in player names, future dates of birth, and accepting negative numbers as weight.

* "Edit Player" Page:
The "Submit" button in the "Edit Player" page can sometimes undo successfully submitted changes.

* Language Display Issue:
The "Submit" and "Clear" buttons in the "Edit Player" page continue to display in English after changing the language to Polish.

* Autofill Attribute Missing:
The "e-mail," "name," and "surname" forms lack the autocomplete attribute, which can affect browser autofill functionality.

 * "Remind Password" Page:
On the "Remind Password" page, the "Message sent successfully" notification appears even without entering any characters in the "e-mail" form.

#### Overall opinion

Main functionalities work, so the application is usable. However, it could be more intuitive and user friendly. Correcting types of date that can be put into forms would certanly improve the using the application.

## TASK 2

### Subtask 1
Test cases based on User Stories - [Google Drive Document](https://docs.google.com/spreadsheets/d/18KRhJNuf7G2CwXaZG6rypxzqSSqxzQfxxIP56fwFskw/edit#gid=0)

### Subtask 2
Test cases - exploratory testing - [Google Drive Document](https://docs.google.com/spreadsheets/d/1zPPDsfIzF4ZiUUsAtWzGJgTkTW75ugP_xaIP0v2w1a0/edit#gid=0)

### Subtask 3

Why is writing test cases important?

The purpose of writing test cases is to document different functionalities in an application or module. After a series of tests is complete, test cases are used for creating test reports. A good test cases coverage ensures that all important functionalities were tested. Test cases are also a source for acceptance testing.




