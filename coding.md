# Coding

How to stay sharp and build a kick*ss portfolio!

## 1. Build on your Foundations:

#### [Javascript 30](https://javascript30.com/)
**30 Day Vanilla JS Coding Challenge** - by *Wes Bos*
Wes Bos is a Fullstack JavaScript developer and host of the excellent [Syntax](https://syntax.fm/) podcast (definitely worth a listen!) His free course will take you through learning some of the VERY cool things you can accomplish with Vanilla Javascript, and they make great portfolio projects! 

#### [DevProjects](https://www.codementor.io/projects/ruby)
**This is a new website I found and I LOVE it so far - super cool**
Designed to help you imporve your Ruby coding skills and your project scope and management skills, these are awesome projects to add to your portfolio and ways to stay sharp with Ruby! (Fun fact, you can find projects in other languages too!)

#### [30 (Ruby) Coding Challenges in 30 Days](https://www.youtube.com/playlist?list=PLEoubTKvE34g5uL5_pg5FOoo3Ae6vlSwu) 
**30 CODING CHALLENGES IN 30 DAYS** - by *Alexandre Gama*
Join Alexander's engaging video series and level up your Ruby skills one challenge at a time. In order to maximize your learning, track your progress, and keep your Github green - create a git repo for this video course and commit after very lesson. 

#### [Awesome Interests](https://github.com/KatherineEvans/what-next/blob/main/awesome-interests.md)
Keep working on cultivating your awesome interests in tech! Pick a project to work on, find a new tutorial for something you've always wanted to learn, explore different areas of tech to see if it sparks new interests in you. Just keep learning! 

## 2. Work on your personal website!

Now’s the time to create/work on your personal website to make it the best it can be! Haven't started? That's ok! There are awesome resources available online and through Actualize that will help you create a presonal website that highlights your brand and who you are as a developer.

Don't forget to make sure it's clean and polished! Spend some time combing through your personal website to make sure:
 - All spelling is correct
 - All the links work (remove any you don’t need!)
 - There’s no dummy text (aka lorem ipsum)
 - There are no sections with empty content, blank photos, or broken code
 - REMEMBER: less is more - don’t add content to just “add content”. Make it work for you!  

Some examples:
- [https://www.caseycantrell.com/](https://www.caseycantrell.com/)
- [https://www.johnnyproano.com/](https://www.johnnyproano.com/)
- [https://ikarabulut.github.io/](https://ikarabulut.github.io/)
- [https://www.katevansdev.com/](https://www.katevansdev.com/)  (*My site is RIDICULOUSLY plain and simple - it doesn’t need to be long and/or flashy, simple websites are better than larger ones with useless or incomplete content!*)


## 3. Keep working on your capstone project:

I know that, for almost all of you, there are aspects of your capstone projects you haven’t finished yet. **Keep working on them!!**

I also know that this can be a daunting suggestion, since you’ve just lost your daily accountability (i.e. class), and your ready access to TA and instructor assistance. But fear not! You have access to the Actualize alumni network, your Tech Mentor, and Actualize Tech Leads (you’re free to schedule sessions with them any time you’d like). You can also use each other as a resource! When working on your capstones, you should never be “stuck” - if you get stuck and spend more than 30-45 minutes researching solutions to no avail, move on to another task and contact someone for assistance. This will also help you become a more self sufficient developer and help you hone your “googling skills” and your error message reading skills. (Google, StackOverflow, and ChatGPT are your friends).

A fun, alternate approach:
*Rebuild your capstone with a different technology! Try building your frontend using Vue or Angular! Try building your backend using PHP or Python. This is a great way to learn: start with something you KNOW and incorporate something NEW.*

Lastly, publish your capstone project on [Render](https://github.com/Actualize-Evening-02-2023/resources/blob/main/deploy_with_render.md)!

## 4. Work on something new! 
Don’t have any idea what to build? I gotchu! Here are some ideas for projects to work on:

## Backend Applications (APIs - no frontend!)
So many companies these days have built their business models around APIs as a product. Think about Twilio - they have a very robust codebase that users like us are able to connect to via API calls. (**API** stands for Application Programming Interface). The backends that we built in Ruby on Rails were APIs! You wrote a bunch of Ruby code that your frontend was able to connect to, to retrieve and manipulate data. Many of you also connected to external APIs for your capstone projects! 

If you're at all interested in building out backend applications (i.e. APIs that either you or others can access) I encourage you to read more about what it means to build a good API.  

- [How to build an API](https://rapidapi.com/blog/20-tutorials-on-how-to-create-your-own-api-sorted-by-programming-language/) (in multiple languages!)

- How to (conceptually) [build an API](https://www.mindk.com/blog/how-to-build-an-api/)

#### Build a "Developer Todo List Manager" for the terminal (CLI - command line interface)

Create a simple application where developers can (C)reate, (R)ead, (E)dit, and (D)elete tasks on their to-do list all from their terminals. *For some imaginary bonus points: research how to display a user's todo list every time they start up their terminals.*

Think about this app - how would you decompose it into managable steps? Spend 5-10 minutes thinking about it, and write down some ideas! If you're a little lost on where to start, here's a suggestion: 

<details>
<summary>Decomposition Steps</summary>
<br>

- Spin up new Rails app, create a Github repository, and make initial commit
- Plan your database: how many tables do you want/need? Since this is an app that is designed to be accessable to one user (you) locally through the CLI, is a users table really necessary? (That's up to you!) My suggestion: start off with your Todo model. What attributes live on the Todo model? (A few: name, description, priority, due_date, is_completed )
- Generate the Todo Model, `run rails:db migrate`
- Generate the Todos Controller
- Populate your Seeds file and run `rails db:seed`, OR hop into your rails console and generate some Todo data.
- Create your CRUD routes in your routes.rb file
- Create your CRUD controller actions
- Create tests using minitest
- Create a `frontend.rb` file at your projects root, puts a simple statement and test it in your terminal
- Keep going! Add more decompositon steps! 
</details>

## Frontend Applications (no backend!)

*(Please note, some API will require you to create a backend to make your API calls)*
___
#### Build A Weather app!

Using the frontend framework/library of your choice, connect to a [weather API](https://github.com/public-apis/public-apis#weather) and build out the following capabilities:

 - A route/page for the Daily Forcast
 - A route/page for the Weekly Forcast
 - An "About Page" that talks about the technology used and how you build the project. 
 - **Bonus:** create routes for polution/air quality and/or pollen count using an [environment API](https://github.com/public-apis/public-apis#environment)

This app should allow the user to input their location (zipcode/city/address, etc) to retrieve the daily/weekly forecast relevant to them. *And make it look nice!*

 - Include different CSS and JavaScript elements to show different images based on the weather: i.e. if it’s sunny, show an image of a sun/sunny day, if it’s raining, show rain, etc, etc

___
#### Build a Dictionary/Thesaurus app!

Using the frontend framework/library of your choice, connect to a [dictionary API](https://github.com/public-apis/public-apis#dictionaries) and build out the following capabilities:

- Allow the user to search for a word's definition, include a search bar that allows the user to input the word they’re looking to define.
- Show the user synonyms and antonyms for a word, i.e. similar/opposite words based on the user’s search parameters.
- Create a route/page that shares a *"Word of the Day"*!
- An “About” page that talks about the technology you used and how you build your project
- **Bonus:** Include the word's pronunciation - show the user the correct pronunciation, and include an audio clip!
- **Bonus:** show the user the word in different languages!

___
#### Build a currency converter/exchange app!

Using the frontend framework/libray of your choice, build an **SPA** (single page application) that connects to a [currency API](https://github.com/public-apis/public-apis#currency-exchange) and allow the user to compare one or more currencies by entering a starting amount for a particular currency. *Make it your own!*

___
#### Build a Cryptocurrency application!

Using the frontend framework/library **AND** JavaScript charting library of your choice, build an **SPA** (single page application) that connects to a [cryptocurrency API](https://github.com/public-apis/public-apis#cryptocurrency) and allow the user to compare one or more currencies - include a graph for each crypto to show it's price history. *Make it your own!*

___
#### Dealer's Choice! 

There are so many great (read: FREE) APIs available, I encourge you to spend some time looking through a few of these resources to find some inspiration: 

- [apilist.fun](https://apilist.fun/)
- [rapidapi.com](https://rapidapi.com/collection/list-of-free-apis)
- [Public APIs on Github](https://github.com/public-apis/public-apis)

## Fullstack Applications

#### Hiking Application ([view schema](https://docs.google.com/spreadsheets/d/1ilBbMvdKGO9ttQPbR1ib5LCwh6i2Y9_FiLL_mSLRR78/edit#gid=0))

Create a fullstack hiking application in your prefered languages/frameworks that connects to a third party API or library (maybe a weather app, or a mapping library, or the Cloudinary API to allow users to upload pics from their hike)! 

This app should: 

- Have Sign up (CREATE User)
- Have Login (CREATE session)
- Have Logout
- Display all hiking trails (*User should **NOT** need to be logged in to see trail information!*)
- Show one hiking trail (with all ratings and comments from any user for that hiking trail - User should **NOT** need to be logged in)
- Allow a user to "favorite" a hiking trail (ONLY if user is logged in)
- Show a user all of their "favorited" hiking trails (ONLY if user is logged in)
- Allow a user to delete a hiking trail from "favorites" (ONLY if user is logged in and ONLY for THEIR favorites list)
- Allow a user to add rating to hiking trails (ONLY if user is logged in)
- Allow a user to update rating for hiking trail (ONLY if user is logged in and ONLY if it’s their rating)
- Allow a user to delete rating for hiking trail (ONLY if user is logged in and ONLY if it’s their rating)
- Allow a user to add a comment to hiking trails (ONLY if user is logged in)
- Allow a user to update comment for hiking trail (ONLY if user is logged in and ONLY if the comment belongs to them)
- Allow a user to delete comment for hiking trail (ONLY if user is logged in and ONLY if the comment belongs to them)
- **Bonus: Show trail location on a map by integrating with a Map API**
- **Bonus: Allow user search for hikes with a search bar**
- **Bonus: Deploy your Application!**
___
#### Cookbook Application ([view schema](https://docs.google.com/spreadsheets/d/1ilBbMvdKGO9ttQPbR1ib5LCwh6i2Y9_FiLL_mSLRR78/edit#gid=1530641594))

Create a fullstack Cookbook Application in your prefered languages/frameworks! This app should show/allow a user to:

- Have Sign up (CREATE User)
- Have Login (CREATE session)
- Have Logout
- Show **ALL** recipes (User does NOT need to be logged in)
- Show **ONE** recipe (User does NOT need to be logged in)
- Allow a user to create a recipe (ONLY if the user logged in)
- Allow a user to update a recipe (ONLY if the user is logged in AND the recipe belongs to them)
- Allow a user to delete a recipe (ONLY if a user is logged in and the recipe belongs to them)
- Show **ALL** ingredients for/with a specific recipe 
- Allow a user to create an ingredient (ONLY if the user is logged in and the recipe belongs to them. Ingredient *must* be tied to a recipe)
- Allow a user to update an ingredient (ONLY if the user is logged in and the recipe belongs to them. Ingredient *must* be tied to a recipe)
- Allow a user to delete an ingredient (ONLY if the user is logged in and the recipe belongs to them. Ingredient *must* be tied to a recipe)
- Show **ALL** directions for specific recipe
- Allow a user to create directions (ONLY if the user is logged in and the recipe belongs to them. Direction *must* be tied to a recipe)
- Allow a user to update a direction (ONLY if the user is logged in and the recipe belongs to them. Direction *must* be tied to a recipe)
- Allow a user to delete a direction (ONLY if the user is logged in and the recipe belongs to them. Direction *must* be tied to a recipe)
- **Bonus: Install a (free) theme or style using bootstrap**
- **Bonus: Deploy your Application!**

___
#### Make a Clone!  

Is there a website you like? Try to make a *(SIMPLE)* clone of it! Do your best to create a schema (really good practice!) and include the has_many/belongs_to relationships. If you're stuck on creating a schema, I'm happy to look at them, OR here are some [schemas](https://docs.google.com/document/d/1NfSx0Op0wAiZZiYCEFJddfIEJLvW4pIwksCdXSDftzk/edit#heading=h.gv6h0timkwrl) to get you started!


## Some AWESOME (FREE) tutorials

 [Scrimba](https://scrimba.com/topic/free) (perhaps my favorite tutorial platform) has courses on: 

- React
- Python
- ChatGPT & AI
- UI Design Fundamentals
- HTML & CSS (also CSS Grid and Flexbox!)
- CSS Animations
- Bootstrap and more!