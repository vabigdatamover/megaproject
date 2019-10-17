# megaproject

Group Project for Bootcamp

Lydia recommondations for keeping everybody in the same page (same master branch)

1. DO NOT REARANGE THE FOLDER STRUCTURE 
    - All html's should be in templates 
    - Photos, CSS and JS should all be in the Static folder 

2. To test html make sure to launch it from the server 
    - Server html will have different href's and src's then regular html 
    - For refferencing anything in the static folder (css files, js files, or photos's) use this example:
        - {{ url_for('static',filename= './FOLDER NAME HERE/ FILE NAME HERE') }}
    - For referencing another html page put the route in the href, use this example:
        - href="ROUTE URL GOES HERE" (/, /about, /maps, etc...)

3. NEVER WORK ON THE MASTER BRANCH
    - Only work on the branch you created, when you are ready to push changes to the master branch make a pull request on the github repo website (not through your terminal)

4. Everyone needs to make their own branch to work in. Please follow these steps: 
    1a. git checkout -b BRANCH NAME HERE (this creates and takes you to the new branch, to switch between branches git checkout BRANCH NAME )
    2a. git add . && git commit -m "YOUR COMMENTS" && git pull origin master && git push origin BRANCH YOU'RE IN (order of steps to follow in order to push changes to git hub )

5. For pull request on github repo website 
    1a. after pushing changes-- there should be an option to create a pull request
    2a. click the option to create pull request-- this should take you to a new page on git hub; that page should let you know if ther is going to be any merge conflicts -- if there are merge conflicts redo step 4 (step 4 should prevent any merge conflicts). 
    3a. At the bottom of the page there should be a button to create pull requests; click it. 
    4a. This should navigate you to another page where it will ask you to merge pull request to the master. 
    5a. Designate one team member to be in charge of merging pull requests. DO NOT MERGE YOUR OWN PULL REQUESTS
    