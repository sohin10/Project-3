# Milestone 1

Create a single page application (SPA) using React.js, or any front-end web development framework of our team’s choosing.

Team members

1. Sohini,
2. Shivangi, 
3. Preetam



## Topic of project

Single-page web application for course registration using React.js.

The goal of the project is to create a practical/real-world application. We all use or have used the online course registration tool as students. I believe the time is right to build one. Students can select from a list of available courses in this application, browse through each course, see the detailed information, add the course to their cart, and complete the registration process. The app will have multiple pages for courses cart page and registered courses page etc,. With this project, we can demonstrate what we’ve learned about React.js and how to use concepts like creating react components and using react router to create single-page web apps.

### Features:

Browse course list, 
Course detail page, 
Add course to cart, 
Check cart items, 
Complete course registration





# Milestone 2

We wanted to create a project UI prototype for this milestone. So we could figure out how to divide the app into component structures and plan for the MVP. We started with low-fidelity wireframes and then progressed to a high-fidelity prototype.

### low fidelity mockup
![lowfi](https://user-images.githubusercontent.com/60220627/204493681-6392f02e-5f45-44f6-aa48-96136c7c78c4.png)
![lowfi2](https://user-images.githubusercontent.com/60220627/204493690-50f8d7db-8ea1-4608-88aa-e83f0def4fd8.png)


### high fidelity mockup
https://www.figma.com/file/gZIyqi9MskasEv1aWzk55v/Buff-class-search?node-id=0%3A1




## Project outline 
We will be using React router package to implement the Single page application (SPA) using React.
The app is split in to 4 different pages.
- Home
- Course Detail
- Cart
- My Courses


## Breaking The UI Into components
Splitting the UI into to components so that each component adheres to single responsibility principle. Each component is responsible for one particular task alone.
We have split the UI into components.
- Navigation header Component
- Course list Component
- Search Component
- Cart component
- Course Detail Component
- The cart/my course item component
- Error message component (when the user tries to add a course that is already in cart/registered courses and when the time schedule clashes)


To make the UI interactive we need to provide React with state. The change in state tell react that something has changed and re-render the component to trigger changes.
To maintain the Application wise state we decided to use the useContext() react hook.


## Goals for Milestone 3
MVP (Minimum Viable Product)
For the MVP, we’d like to create all of the pages with their respective components and styles, as well as apply the routing. As a stretch goal, we’d like to have the entire application completed and working properly.




## MILESTONE 4 - REFLECTION

Each day, every class, I learnt something new. Not only were we working with a new Javascript library, React, but we were also working in teams. This made Project 3 very exciting. Within our group, there was a great deal of collaboration and mutual respect. Before beginning the project, we were aware of each other's skills, abilities, and weaknesses, and we allocated work correctly so that we could assist one another whenever we encountered difficulties. 

This project prepared us for working in the real world, cooperating with teams, and discussing code. We were able to solve errors and monitor each other's progress owing to our regular zoom calls. 

Preetam's presence on our team was incredibly beneficial, as he not only understood a little bit about React but also assisted Shivangi and me in comprehending the many React principles while we worked on the project together. 

All three of us are great at creating the user interface, so we started off by dividing the design across the three of us to create a wireframe to work off of. I sketched the website's initial design, while Shivangi built a low-fidelity prototype and Preetam worked on a high-fidelity mockup. 

When it came to coding, since Preetam had experience in working with Real Time database, he took the responsibility of structuring, retrieving and updating the database while Shivangi and me were responsible in the coding of the components, styling them and learning about routing and implementing that in the project as well, which was a struggle at first to understand how the routing concept works but once we had the basics down it all made sense. Preetam additionally worked on the functionality of the application by using states, context and other logic. 

There were no disagreements or misunderstandings between the three of us because we had established our goals and tasks beforehand, and then it was simply a matter of assisting each other in achieving our objectives. 
It was also quite exciting to see how React can be utilized to develop such interactive web designs and have the chance to see what others had made as well. 

I am quite surprised by how much I've progressed via this class. Coming into this course with no coding background whatsoever, it feels strange to say this now, but I can call myself a front-end developer, or at least I think I can. 

But in the future, I will invest more time and effort into mastering HTML, CSS, and JavaScript. And build interactive websites that are cool and engaging! I'm pumped!


