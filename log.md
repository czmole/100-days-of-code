# 100 Days Of Code - Log

### Day 1: December 29, 2016 

**Thoughts:** This project is meant to build a small API that would be consumed inside a mobile application. There is already a web application used kinda intensively by a niche of users - students. This project was written back in time when I was at the beginning of web development as a side project/idea, then was turned into a freelance/paid project and now seems to be more demand for it to have a mobile interface for input.

I can’t really give more details about it because I am under an NDA, even if now I am actually back into volunteering in this project. Therefore I can not really provide the GitHub repo link.

I still think I can be part of this challange as this is a side project.

Today I struggled to find the right stack to build this, considering the initial/current structure of the database that does not match Laravel’s namings, the size of the API which is small. I tend to pick Laravel/Lumen because I am a big fan and it’s easier/fast to develop and maintain the code later but in this case would have been hard to create a migration or a mix / workarround in the models to really have it used more in Laravel style with Eloquent, tables relations and so on.

So, for now, version 0.0.1 I chose to create a bundle of libraries that would help me do it without too much hassle, some routing, PDO, validation, SparkPost wrapper for sending emails, JWT authentication.
I am sure is not the best / ideal stack considering a lot of things but for now is the best / light / straight I see. 
For the future, I am planning to talk the owner about a second version of the web application that would consume an API itself (version 2 of what I am doing now) and to have it entirely created in a modern framework from ground to top.

**Today's Progress**: after 1st day I have all the libraries set up, a document with all the end points and the authentication working.

**Link to a blog post on this:** [#100DaysOfCode starting today](https://newbitsontheblog.com/100daysofcode-starting-today-1727256d92f#.lmzh6qusc)

### Day 2: January 3, 2017 

**Today's Progress**: Worked and finished on an auth midleware, new API calls completed for pulling some standard lists, type of users, general lists that will be used across the app in different screens. Also found an easy way to test the API calls inside the editor I am trying now (VS Code) - the plugin URL is here https://marketplace.visualstudio.com/items?itemName=humao.rest-client - ussually I am using Postman to test my calls.