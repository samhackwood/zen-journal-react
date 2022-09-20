# Zen Journal.
## A clean meditation app.


<img src="project-four-frontend/public/ZenJournalApp.png">

Project philosophy:

A clean and simple app to time and track meditations. We designed the app with two principal philosophies. Firstly, that journaling is an extremely powerful tool on the spiritual path. Not only does journaling allow us to become more aware of the content of our minds but it gives us a sense of our progress and prevents from sitting in rumination rather than actually meditating.
Secondly, that most mediation apps do too much; they are filled with excessive guidance, gadgets, and gizmos and ultimately become a distraction themselves. In our design we try not to get in the way but simply allow the user to meditate, then write about what they experience.

Technical requirements:

A working full-stack, single-page application hosted on Heroku.
•	Incorporate the technologies of the MERN-stack:
o	MongoDB/Mongoose
o	Express
o	React
o	Node
•	Have a well-styled interactive front-end.
•	Communicates with the Express backend via AJAX.
•	Implement token-based authentication. Including the ability of a user to sign-up, log in & log out.
•	Implement authorization by restricting CRUD data functionality to authenticated users. Also, navigation should respond to the login status of the user.
•	Have a well-scoped feature-set. Full-CRUD data operations are not required if one or more of the following are included:
•	Consume data from a third-party API.
•	Implement additional functionality if the user is an admin.
•	Utilise multi-user, real-time communications.

Wireframes + ERD/UML:

<img src="project-four-frontend/public/screenshots/Project Four-SEI (3).png">

<img src="project-four-frontend/public/screenshots/Screenshot 2022-07-15 at 11.36.45 am.png">

<img src="project-four-frontend/public/screenshots/Screenshot 2022-07-15 at 11.47.47 am.png">

Development Process: 

In the first meeting, I brought up my idea for Zen Journal, which I had in the back of my mind since I first began coding. I mentioned that I had a personal need for the app that I wanted to create, and therefore it may be appealing to others too. The rest of my group were fully on board with my idea, so we moved onto the planning stages. 

The next meeting involved assigning roles and beginning on the ERD and wireframes. I decided to work exclusively on the front end for this project because I enjoyed react and had previously created two full-stack applications at this point. So I got started on the wireframes based on my vision of what I wanted the app to look like while the rest of the team got started on the ERD. We then created a project board on Trelllo so that we could log our allocated tasks. 

The app consists of two separate apps - an ExpressJS backend and a ReactJS frontend. They are linked via REST API.
Styling of the React frontend was achieved with React Bootstrap.

The development was test-driven, with each team member testing codes they had written and the team coming together to fix any bugs.

After every day of work we would merge the code to that each morning we were working on the exact same site. 


Final testing and deployment on Heroku was done on day 9 with a presentation and demonstration on day 10.

 


Diffuculty:

Probably the most difficult aspect of the application was the timer functionality. Originally, I had intended to implement a Circle Timer Hook which counts down from a set time and displays a circle which slowly runs out as the timer ticks away. Unfortunately, this hook was very limited in what it could do and though it was easy to set the timer, to add start, pause, and stop buttons were not possible. After experimenting with using a loading bar hook, I eventually decided that the best way to go if I could not use the circle timer was simply to have the time count down. 

Another difficulty which I was quite surprised about was the how difficult the CSS became when using React and many divs stacked on top of one another. This made it difficult to access the correct element and made a seemingly simple task such as centering an element highly time consuming. Over the course of styling the whole site, the time really began to stack up and ate into time which could have been used creating the core functionality of the app.


Feedback: 

Shortly after completing the project, I decided to send it round a few friends as well as a mediation group of over 1000 people to receive some feedback for improving the app. I received a mix of positive and constructive feedback. 


-One user suggested that the word ‘name’ for a mediation is quite confusing and thought they might have to put their own name there. Perhaps ‘title’ would be a better term.

-Many users commented on the styling of the site and said that it looked very sleek and clean. With one or two noticing that the red, black and white theme resembled zen calligraphy. 

-Some users said that appreciated the concept and agreed that most meditation apps are too complicated.


-A few users pointed out that even after a template is created, the user still has to manually set the stages and time so there is not much point in creating the template in the first place. This should be relatively simple to fix, and the template data simply needs to be assigned to the meditation. 

-I have been using the app myself for my meditations and have found that my browser tends to sleep before the meditation has finished. This is incredibly frustrating since you are left meditating with no signal to stop. To counter this I have been using a chrome extension called ‘caffeine’ which keeps the browser awake for a set amount of time however I will look into a way of preventing the user’s browser from sleeping which I can implement into my code. 


