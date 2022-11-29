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
