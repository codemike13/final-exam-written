Node - Express - MongoDB

1. What is Node js? 

2. What is Express and what it is use for?
   -Express is used to manipluate the Html of a website with JS, its also works as a backend manager to communicate with your database.

3. What is npm? 
    -(Node Package Manager) Npm allows you to pull neccessary repositories down fron the net, these modules contain prebuilt components / methods /classes and logic to be utilized in your code. 

4. What is package.json? 
    - Package.json is the file that list all of the imported modules to use when you start as well start up scripts.
    - 
5. In the package.json - what is npm script? 
    -The NPM script dictates what to load and what mode when you Npm start.

6. What is callback hell and how to avoid it?
   -I honeslty dont know but from the sound of it , I think it is a matter of your call backs performing a function like and endless loop or a persistent eventListener that will cause hang ups or over consumption of resources.

7. What is a Promise? 
   A Promise is a logic method that will only (resolve) the data result you need. If your criteria isnt met while flowwing through this promise its caught in catch blocks and then (rejected). 

8. What is a request object?
   -A request object is the data that is bundled into a network request. It can be used to get relevant information such as data passed during this activity for the router to consume or conrtollers. You can also reference DOM fields to retrieve information

9.  What is a response object? 
    -The response object handles what happens after all criteria is met from the req portion and sends this information back to the requestor, such as {obj} with new data to update fields with. Or your error codes that you want a promise to pass back from your controller methods.

10. What is a middleware? 
    MiddleWare is used to alter/check data during an operation , it also can be use to perform things like auth functions during a network request or updating things not directly relevent to the operation that called it. 

11. What is a route? 
12. -Routes are used to navigate through a site , access/modify data resources. 

13. What is a controller? 
14. -A controller is built to unload and handle logic operations from your routes.  

15. What is MongoDB?

- MongoDB is a database system used to store/manipulate/retrieve relevant data for your project in JSON/BSON format. 

16. What is Schema in MongoDB?
    -A Schema is the structure of a data object that you set prior to the creation of one of these objects. It dictates to the Db fields names/types and the hiearchy or these things. Based on the allowed fields types from the DB.

17.  What is a JSON? 
   -JSON is a lightweight "key":"value" pair system written very similarly to an object for storing DB info.

-------------------------------------------
React 

1. What is React, and why was it created? 

- React was created by facebook as a hack way to do thier DOM updates without modifying/reloading the entire DOM. After realizing how much time and resources it saved they took that logic and created Reactjs. React is a component based system that allows a website front end to be built with html using JS. These components can be updated without having to refresh or modify the whole DOM.

2. What is the advantage React has over jQuery and template engine?

Speed , flexibility , lower resource consumption , re-usability ,components can be utilized in other projects more readily simply plug them into your react dom if the suit your needs.

3. What is a State and how do you create it?
   
   State is the current condition of the values you are tracking in your ReactJs component, for example if a user is validated you can set a boolean to true in the  state of your index.js file allowing other components to be rendered and viceversa.

4. What is a Prop and what does it do?

Props are properties passed down to child components that allow them to interact upwardly if some data condition has been met.

5. What is componentDidMount? 
   
   A function call that will execute when a component is rendered, you can add startup functionality to this function for when your component loads. 

6. What is componentDidUpdate?

   A function call that will execute when a component is updated, you can modify state , fire functions, or call backs.

7. What is children in React? 
8. Things that are inside a components when it is rendered.

9. What is a setState?
It is a method that allows you to modify state objects in a react component.

10. Why and when maximum callstack exceed happens?

When a components is trying to update state and is caught in a logic loop.

1.  What is propTypes and why it is important? 


-------------------------------------------
Fullstack Node/React

1. What is Fullstack development?
   Being able to build the frontend and backend of and application.

2. How does React and Node communicate with each other? 
   Axios establishing net connection via url.

3. What is a session storage and JWT? 

Seesion storage dictates how long a session can be active for an auth period. A JSON Web Token allows you to auth utilizing this token which is helpful across multipe devices . 



