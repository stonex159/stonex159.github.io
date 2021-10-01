# My Info
Braxton Madara |
[My email](mailto:stonex@udel.edu) |
[This portfolio's repository](https://github.com/stonex159/stonex159.github.io) |
[My playground](https://stonex159.github.io/My-Playground/)

# Portfolio
Week 1

 I learned the basics of HTML and CSS by reading all the information on this website: [Markdown](https://marksheet.io/).

 I implemented a lot of that information to make a small website with a prototype portfolio that I was going to use as the main portfolio. But I want to now make that website a playground to link to other projects for Javascript and React. As well as showcase the HTML and CSS tricks I learn along the way. The Website is located in "My Info". I wanted the website to have two columns of info, but the positioning knowledge for that kept alluding me. 

 On Sept. 9 I went to an ACM meeting at the behest of my Lab TA, Noah. There we were told the basics of HTML and CSS then some info on APIs and flexboxes. Flexboxes seemed exactly like what would solve my problem of positioning on my website, since I didn't want to just use a table format. Here is a recording of the [zoom meeting](https://drive.google.com/file/d/1ZVD_rT8q0kRqZYIcIqI7DgunETMVr2oM/view?usp=sharing) and the [source code](https://drive.google.com/file/d/1ZVD_rT8q0kRqZYIcIqI7DgunETMVr2oM/view?usp=sharing) for the bitcoin price finder they walked through during it.

 In my playground I created a flexbox in my footer. I used this website to learn about [flexboxes](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

 I've started this bootstrap [tutorial](https://www.w3schools.com/bootstrap4/bootstrap_get_started.asp).

Week 2  

 I went through the introduction and tutorial for React [here](https://reactjs.org/tutorial/tutorial.html). When I have access to a personal computer I will start making Chess.

 I followed the tutorial for [tic-tac-toe](https://reactjs.org/tutorial/tutorial.html) and I want to use some of the features such as move history and history shifting in the chess game I am working on. I'm not sure how to deploy it yeat, without using Netlify, but here is the [repository](https://github.com/stonex159/Tic-Tac-Toe)
 
 As of Sept. 14th I have remained forced to use github editor as my only editor as my computer has been decomissioned, not at my behest. This will be solved by Sept. 15th, but setting it up left me with only sept. 16th to do work. I will not have little to show next week.
 
 I want to make predictions appear depending on the piece you are currently controlling (have picked up) in the chess game. Implementing an ai opponent wil be too difficult for now, unless I find one for free use online. Looking at cursor manipulation and hover selectors should be the way. I found a page that can help [here](https://www.pluralsight.com/guides/create-a-hover-button-in-a-react-app).
 
 In my one of my casual clubs I am an officer. I was talking with the other officers and the e-board about a better method of administrtion than leaving someone outisde to reord names and check marks. We decided on a google form, but I want to make a website because I think it will be fun and interesting since it is a bit more officila in capacity and must look presentable yet not formal. I'm having trouble with my commits from vscode not appearing in the git reposity for it. I think I'm missing a step, but it all seems right.
 
 I want to implement bootstrap throughout the club site but I am having trouble installing it through the terminal, unlike when I used a url in my playground site.
 
 I tried to create the chess game repository through the terminal but something went wrong and I think it corrupted. So I will have to make a new one, I will use vscode this time.
 
Week 3  

 I changed my club website into a react app, here is the [repo](https://github.com/stonex159/CVGC-Site) and the website is coming. Watching Dr. Bart's video on craeting a the TA Trainer was very informative and helpful as I setup the club app. I am trying to expand upon what I saw since my app is decidely different in application. I want people to input their name email and the status of their daily health check then submit that through a button. That info will them be stored and displayed in a table below that information collection column. When a new day passes that information will be moved over to the history page to be documented and referencable if contact tracing or attendance rate wants to be investigated.
 
 ~~Currently I having difficulties figuring how to make the form work as I am unfamiliar with forms in javascript. I've read some tutorials for them, like this [react/forms](https://reactjs.org/docs/forms.html) and this [Data Tables in React](https://shopify.engineering/building-data-table-component-react) but the structure of my app is so different that I need to think about how I can implement them cleanly, or how to reorder my app.
 
 I have implemented a bootstrap form into my app, to gandle the collection of the information input.
 
 ~~Deploying the app to github pages is proving troublesome. I have followed [this](https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f) article on how to, but I keep running into trouble at the "deploy": "gh-pages -d build" part. My code refuse to use that with my app's name.
 
 I completed Phase 1 of my club app. It can take a form and send the data to the dynamic table below to keep track of attendees. I still want to put a history page so that we can more accurately track the data in case we need to do contact tracing. Other features like alerts for yellow marks along with a message to advise the person on how to get a green mark would be good. I want this app to be usable even after I leave, so adding statistics or at least an frfamework to implement them would be awesome. Not sure if that would require a database though...
 
Week 4

I made an editModal that allows the user to edit the table to correct mistakes made during submission. I also added precautions for possible errors and allowed it to fill in the table with data found at the row number, for easy changes. This took me way longer than I expected. About 8 hours from start to finsih just for the Form. The modal itself was easy to make after looking up some attributes.
 
I made alerts for the case of attendees not having met the health check requirements along with advisements for them. I also added the banner for the club with some slight styling to make it presentable. I'm not all that satisfied with it yet, so I am thinking of making my own banner for the club and using that. I also want to work more with custom css since I only had a small taste so far. 

The TA's helped a lot with some of the crucial problems I ran into. Thank you very much Noah and Josh.

In adding the alerts I learned a bit more about react hooks while troubleshooting, specifically useEffect. I haven't utilized that knowledge yet but it would be interesting to look into down the line.

I still want to make the history page, but instead of a page I will make it a modal, also I want to allow it to preserve data from the current session and load it in the case of someone closing the tab and opening it again. I can just preserve the data at the end of the run into an array and have it utilize the current day for the recovery function and the current week for the book keeping feature.


# Change Log
Week 1   
 - I learned the basics of HTML and CSS
 - I made a website playground to test my HTML/CSS/Javascript knowledge
 - I made a CSS file to augment the HTML file for the playground
 - I created a seperate change log and todo list for my playground as well
 - I learned a bit about flexboxes  
   
Week 2   
 - I went through the react tutorial [here](https://reactjs.org/tutorial/tutorial.html) that had me recreate tic-tac-toe in a browser.
 - I started a new website for my Casual Videogames Club. It is for administration, I plan to have it all donw in a week. Here is the [repo](https://github.com/stonex159/CVGC).
 - I've downloaded bootstrap and started to navigate and use it
 - I've created the repo for the chess game but i am having problems with the repo  
   
Week 3
 - I converted the website I made for my club into a react app.
 - I watched Dr. Bart's video about react [here](https://www.youtube.com/watch?v=q8eYF6cUi5c)
 - I added a form into my react app that takes a person's name, email, and health check status.
 - I added a dynamic table thanks to [this tutorial](https://dev.to/abodero/creating-a-dynamic-table-using-bootstrap-4-and-react-hooks-4a1m)
 - I made the dynamic table able to accept the form data and add a new row upon submit
 - I properly deployed the app to github pages with some help from Dr. Bart
 - I completed my Phase 1 of my react app: [The repo](https://github.com/stonex159/CVGC-Site), [The site](https://stonex159.github.io/CVGC-Site/).
   
Week 4
 - I added a modal that allows you to edit data in the table.
 - I added our club banner to the app
 - I added our club logo to the repository for future use
 - I changed the status input from a textarea to a set of radio buttons
 - I added margins to the buttons to make them look nicer
 - I made the control panel follow a grid pattern
 - I added measures to prevent the app from breaking or doing things it shouldn't, such as:
    - clearing the input fields upon submission and/or exit of the modal
    - preventing the index from reching the initializer or out of bounds of the array
 - I added colors to the radio buttons respective to their values
 - I added alerts for yellow and red status with advisements

# TODO
Week 1   
 - Learn HTML and CSS  
  
Week 2   
 - Look into React [tutorial](https://reactjs.org/tutorial/tutorial.html) and [hooks](https://reactjs.org/docs/hooks-intro.html)
 - Look into Bootstrap [here](https://www.w3schools.com/bootstrap4/bootstrap_get_started.asp) to make a new website, probably about Hololive
 - ~~Create some Javascript for the playground, or maybe a new project to link to it.~~
 - ~~Create a game of Chess in react~  
  
Week 3   
 - ~Learn about react hooks [here](https://reactjs.org/docs/hooks-intro.html)~
 - Get advice on committing properly to a repo from vscode
 - ~~Look more into features such as [draggables](https://www.freecodecamp.org/news/reactjs-implement-drag-and-drop-feature-without-using-external-libraries-ad8994429f1a/) and object manipulation via cursor in react, more specfically hovering and mouse events
 - I need to connect the form on my react app to the table that stores the info inputted
 - I need to make a history page to track the attendees and their checks per week
 - Add a warning popup if their health check is yellow that directs them to places that administer the vaccine
 - Ask a TA how to deploy my react app to github pages  
    
Week 4   
 - Add an alert for the yellow status along with a message to advise them
 - Add a history page to track attendees and if they were previously warned
 - empty the input boxes after a submit to prevent accidents
 - add a button to remove a row from the table to rectify potential mistakes
 - Add the CVGC club banner and logo to the page along with some css styling to spruce it up
 - make a framework for analytic information, such as an graph of attendance per month.
   
Week 5   
 - Make the history modal
 - Make the data searchable per week
 - Preserve the data of a session at termination
 - Load any data put in that day, especially in the case of accidental termination
