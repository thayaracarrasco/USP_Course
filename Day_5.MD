# Day 5

## Make sure your MorphoCloud instance is active (unshelved) before you start with the course evaluation!!!
To unshelve the instance go to your github issue page, and add the comment `/unshelve` at the very end of the existing comments (do not forget to hit the comment button to submit your issue). 

## Course Evaluations (15 minutes)
Please go to the https://forms.gle/fFJHzeFcLKW75vKE9 and fill the course evaluation.

## Git and Github tutorial (you will need your MorphoCloud instance to run everything from this point on. You cannot do this in your own computer. If MorphoCloud doesn't work for you, please find a partner.)
### Setting up the environment on MorphoCloud
Login to your instance, open the Firefox browser, and from there navigate to the Day 5 link of the course website. You should continue to the rest of the tutorial using the Firefox browser inside your instance. You will copy and paste code, and it is harder to the if you use the web browser in your own computer. 

In the Morphocloud, proceed to open a terminal (command line) and type this command:
```
gh auth login
```
Accept all the questions (you will need to hit `ENTER` key a few times until the browser pops up) and then when the web browser pops up please login to GitHub. Once you logged in, GitHub  will ask you to enter the 8-digit code displayed in the terminal window into the web browser (code looks like something **AE1B-3SSC**. Make sure you enter the unique code generated for you, not this one. You can highlight the code in the terminal windows with mouse, right-mouse click and copy and and then right-click in the browser windows to paste)

In the next window you should authorize the GH to access your account. If all went well, you should see a message that says: 
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

### Running MorphoDepot 
* Open the Firefox window, and go to https://github.com/muratmaga/pinecone/issues/new
* As the issue title enter your **FullName**, and as the description provide this following text:
`My first MorphoDepot assignment. Will segment a pine cone scale.`

This will create a specific issue for you, github will ping me, and I will assign it to you to start with MorphoDepot. (When you submit the issue, please come to me and let me know. I might be doing other things at the time and my not see the notification). 

* Launch  Slicer application, go to the extension catalog, search for `MorphoDepot` and install the extension. Restart for changes to take effect. 
* After the restart search for the `MorphoDepot` module in Slicer. And hit the Refresh Github button. This should list your specific issue (this will take up to a minute, be patient). When the issue appears, double-click it to download into the slicer (say YES to the popup about closing the scene and loading the issue). It may take another couple minutes for the pine cone image to appear in Slicer and it automatically switch to Segment Editor. At this point you are ready to segment. Just pick up a random scale and paint it with sphere brush. If you have come this far, you are ready to submit your assignment. 

**NOTE:** If you clicked the `Refresh Github` button and waited for a while and nothing happened, chances are I didn't see your issue and assign it back to you.  Come see me, and bring your computer too.

* When done with segmentation, go back to the MorphoDepot module. Find the text field that says `Commit message:` and type 
```
First attempt
```
and then hit `Commit and Push` button, this will do two things: (1.) Locally commmit the changes to the repository, and (2.) Push those changes to your fork of the pine cone repository (i.e., your own fork will have these changes). This is equivalent of saving files. With MorphoDepot we will **NEVER** use the regular save, export as functions. 

* You are now ready to submit your assignment to be reviewed. Simply click `Request PR Review` and then come see me (with your computer). 








