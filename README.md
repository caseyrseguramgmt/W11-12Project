# W11-12Project

## Objective

The objective of this project is to create a suite of test cases using Selenium and Python for a specific website. These test cases will validate the functionality and performance of the website. Additionally, this project will leverage SQL to retrieve and manipulate data related to the tests, enabling a comprehensive analysis of the website's behavior under different scenarios.

## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Usage](#usage)
3. [Progress](#progress)
4. [Automation Structure](#automation-structure)
4. [Elements Being Tested](#elements-being-tested)


## Technologies Used
- Python
- Selenium
- SQL

## Usage
Usage of this would be to see functionality of zippia site and get salary / location data?

## Progress
    05/06
    1. Continuation of trying to fix the pytest.mark to be used. 
    2. Attemped to make a class for the check state salaries which would include methods inside to test for mini instances of the code to make sure they are properly running.
    3. Error with Pycharm not wanting to identify the code as a test with pytest still. Solution yet to be found.

    05/03
    1. Looking at udemy documentation for how to add multiple test cases to be tested seperately
    2. Looking at previous project that this was done in to try and replicate.
    3. Blocker, trying to isolate the tests using pytest.mark in order to only be able to run tests when the marker is called. Problem at hand is the code is not running when being called upon.

    05/02
    1. Fixed all blockers from previous day
    2. Can successfully web scrap the data chart from the next page
    3. The data is then placed in a db file
    4. MVP finished, continuing with doing more test cases

    05/01
    1. Solution for the captcha was found with using an input() for the user to solve the captcha manually. The problem with this is that if I planned to run the script more then once it would have to be manually done many times. Currently looking for a work around, will proceed. (May switch site?) Also captcha after being solved once does not populate everytime.
    2. Blocker of trying to webscrap data off website due to the site having more then one data chart with graph with same class.
    3. Looking at information online with to find the specific graph I want.
    4. Still stuck on isolating the chart.
    5. Looking at udemy course documentation to continue on how to get data printed to the terminal in order to make a db.

    04/30
    1. Found website to work with that does not require sign in to view data for salaries and other potential data
    2. Ran into blocker with pop up from chrome, found a solution by disabling notifications
    3. Find search bar and look up automation tester position
    4. 2nd blocker of the day working with captcha trying to find best solution for work around
    5. Worked on other test example sites to find solution

    04/29
    1. Make repo and invite Kat and Michael.
    2. Set up local python interpreter for pycharm to use python and selenium.
    3. Basic start up of opening browser and opening up a webpage.
    4. Look at different types of websites to finalize what will be used for webscrapping.
    5. Use example files to test the use of SQL for data
    6.Narrowing down most productive showcase of project type, 
        - Amazon alike demo
        - Practice form demo
        - smash characters demo with pulling special move?

## Automation Structure
(Will be started after tests are made, currently only finding elements)

1. 
2. 
3. 

## Elements Being Tested
1. browser
2. webpage
3. find search bar
4. waits
5. dropdown visivility
6. clicking
7. SQL
8. DB
9. 
10. 

