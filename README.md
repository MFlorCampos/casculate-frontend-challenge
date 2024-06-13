# Casculate Frontend Assessment

The purpose of this exercise is for you to show your ability to integrate new features into an already existing project. You may design the page however you like.

The required features on this page are listed below.

**Don’t rush or feel stressed**! If you are running out of time, we’d rather see you do your best on implementing a few of these requirements than submitting something that you are not fully satisfied with.

## The Task

The end product should be an application that fetches posts from an API and displays them as a list of components. The posts can be of two types: **news** or **banner**. Each should be displayed by a different component. If the user clicks on a post, they should be redirected to a page displaying the post image, title, and content, as well as an "add to favourites" button. 
The user should be able to add and remove posts from favourites and search through them.
Furthermore, there should be an input where the user can leave their email to subscribe to our newsletter. This should only do a post to an endpoint with the email as the request body and display a success message if the request was successful.

**Bonus tasks**

If you have some extra time :)
* It would be nice if I could keep my favourites after reloading 
* make the application usable on a mobile device. 
* implement some kind of test automation

## Endpoints
**Newsletter**: localhost:3000/api/newsletter
**Components List**: localhost:3000/api/list

### Technology Stack Requirements

The goal of this technical test is to check how you would handle our current stack. That’s why you must use the following:

- Typescript
- React.js
- Next.js
- CSS3: you can use CSS pre-processors (SASS or LESS).
- If you like, you can use Material UI
- HTML5

### Non-functional Requirements

- For the user, the **loading times are critical**, so have that in mind when developing.
- Pay attention to **code clarity, structure, and legibility**.
- The solution should be **bug-free**.
- Please include a document in your solution or add to this `README.md` instructions to run your code, comments about your approach to the implementation and any other relevant information you’d like to include.

### What We Are Looking For

- Code quality
- Code structure
- Performance/optimization
- User interface/experience
- Search algorithm

### Delivery

Please deliver your work via email as a zip file containing the repository with all files needed to run your solution in a local environment.

Good luck!
