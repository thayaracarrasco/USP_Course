# Day 5

## Make sure your MorphoCloud instance is active (unshelved) before you start with the course evaluation!!!
To unshelve the instance go to your github issue page, and add the comment `/unshelve` at the very end of the existing comments (do not forget to hit the comment button to submit your issue). 

## Course Evaluations (15 minutes)
Please go to the https://forms.gle/fFJHzeFcLKW75vKE9 and fill the course evaluation.

## Git and Github tutorial (you will need your MorphoCloud instance running for this)
### Setting up the environment on MorphoCloud
Login to your instance, open the Firefox browser, and from there navigate to the Day 5 link of the course website. You should continue to the rest of the tutorial using the Firefox browser inside your instance. You will copy and paste code, and it is harder to the if you use the web browser in your own computer. 

In the Morphocloud, proceed to open a terminal (command line) and type this command:
```
gh auth login
```
Accept all the questions and then when the web browser pops up please enter the github credentials you have created for the course. It will ask you to enter the 8-digit code displayed in the terminal window into the web browser (code looks like something AE1B-3SSC. Make sure you enter the unique code generated for you.)

When pops up, you should authorize the GH to access your account. If all went well, you should see a message that says: 
`Congratulations, you are all set!`

### Working with github.
* Go to the course website on github (https://github.com/muratmaga/USP_Course). Find the button that says `Fork` on the right hand side of the window, and hit it. In the next page, do not change anything, simply click the `Create fork` button.  Congratulations you makde your first "fork" (a copy of the repository at its then current state under your account). 

* Now click the `+` button between the `go to file` and `<> Code` buttons. This will start creating a file under your fork. 
* In the field that says "Name your file", type a file name using this convention `YourFullName.txt`, and enter some text (perhaps some notes about how you are using Github?)
* When finished entering, click the green `Commit changes` button. Do not change anything in the window that pops up, simply click the `COmmit changes` button. 

* Congratulations you now made your first change to your own fork. Your fork is now different than the original course website (think of it as a way acquiring a novel character after a cladogenetic event). To contribute back your change to the **UPSTREAM** repository (aka the main course repository that I have created) click the `Contribute` button, and then click the green `Open pull request` button (more lingo: With the commit above, you have **PUSHED** changes to own repository. Now with the PR (Pull Request), you are asking me to "PULL" these changes and integrate into my own repository. You can only push to the repositories that you have created, or have been given right permission. Everything else, you send a PR to the original repository owner. That's up to them whether they want to integrate the change or not). 

* In the next window, keep the title the same (it should says something like `Creating YourFUllName.txt`) but in the `Description` field, enter the following text:
```
I have made some changes to your content, please review and if you agree kindly merge them
```
Then proceed to click the green 'Create Pull Request` button. 

* Congratulations you have done your first PR. This will trigger an email to me, notifying your changes and once I review them, I will accept and merge the changes. Alternatively, I may request some changes to your edits. In that change I will provide some information about what i want it to be change, and change the status of your PR to **DRAFT** (meaning, send it back to you). 

* 




