# learning-name

---

**20/10/2022**
###### Pulling from the main remote branch to the local in GitHub now makes much more sense, as I have found when working on the HTTP project. This was particularly the case when we deleted a remote branch called semantic-html, yet it still remains locally (i.e. on VSC on my computer). This helps me visualise the difference between local and remote, and the distinction between the two.

---

**28/10/2022**
###### I have really enjoyed learning the different console functions. I was already aware of the table function, but it's only now that I've learned about console error and console info. 

---

**02/11/2022**
###### It's interesting to see the contrast between my own tests in the Learn Integration Testing workshop, on the index.test.js page, on the sample calculator provided, and contrastingly those of the solutions. The use of the parseInt and parseFunction functions are problematic; what if therer were 30 arguments to pass in? In that case, the input argument would have to be automatically converted beforehand into a floating point number. 
Some examples of my own:

![testing_screenshot](https://user-images.githubusercontent.com/52511353/199527071-63878c82-4017-4ac4-a3cb-c30ed7dff14a.png)

###### And here's from the solutions provided:

![testing_screenshot(2)](https://user-images.githubusercontent.com/52511353/199529746-ac00cd21-0fbb-4856-bee4-77dce8dab309.png)

---

**06/11/2022**
###### I'm confused as to why adding a second true clause makes this pass on Execute Program? I have to use Reduce to write a function that returns true if all array elements are true.
```function allTrue(values) {
  return values.reduce((acc, current) => acc && current, true);
  ```

---

**08/11/2022**
###### Finished my mock take-home challenge, [viewable here](https://github.com/DominicSimpson/wordletest), where I have attempted to understand how a component of Wordle works - that of how it matches the input letters with the correct word. I assumed that I would have some kind of array to store the different correct words, but in the end just used one correct word, stored in a variable. I tried to add an animate function from animate.css, where each 'letterbox' would flip over, but this didn't seem to work. 

![screenshot](https://user-images.githubusercontent.com/52511353/202900378-cce2f2c3-7064-4b4d-8245-a2bbcaf748b8.png)

###### I've never actually played Wordle before, so I had to give it a go - I got the correct word on the last try! The version we were given to 'emulate' is the [New York Times version](https://www.nytimes.com/games/wordle/index.html).

---

17/11/2022

###### We [finished the Testing project](https://github.com/fac26/todo-derek-dominicS-georgia), involving constructing a To-Do list. I really struggled to incorporate the existing code with the TDD testing, though I did get close with the test question, "test("Can the user delete a task from the list?")". 

![testingscreenshot](https://user-images.githubusercontent.com/52511353/202847013-70ffaca1-f3f2-48dc-8c99-dfd5e7d42b20.png)

###### My hope is that I will eventually get used to incorporating TDD in my code simply from doing it so many times. 

###### Ivan used us as a 'guinea pig' during a session to suggest that we use Local Storage, which inspired us accordingly, and for which we're truly grateful. Subsequently, we were able to add the Local Storage facility after this (I have already used Local Storage, from when I was completing the Fruit Shop Shopping Cart project as part of the application for FAC26). Each to-do item is not part of an individual object inside an overall array, with its own unique ID; a Boolean to indicate whether the user has checked the radio box to indicate that the task is done (note that this is not the same as deleting the to-item completely via the X on the right of each to-do task); and a description.

![localstorage_screenshot](https://user-images.githubusercontent.com/52511353/202847365-9fb08f95-1a5d-4c19-b572-cfcf595c4fe2.png)

---

24/11/2022

###### I finished The Monty Hall Problem. You can see my GitHub [here](https://github.com/DominicSimpson/themontyhallproblem), with an extended ReadMe that goes deep into the legend. This includes PowerPoint presentations that I did in advance of the coding that prove that switching to another door does indeed increase your chances of getting the door that has the sports car.
####### Coding the Monty Hall Problem was difficult, and the final version only works 50% - if you try it out by clicking on a door and then click the 'No' button (i.e. you don't want to switch to another door), it then leads (via aynchronous JavaScript) to a separate screen that informs you that you were either successful or not successful, and tells you the statistics of choosing the door with the car, rather than the two with the goats. If you choose to switch to another door, it should *also* lead to a separate screen that informs you that you were either successful of not successful, with the corresponding statistics that tell you this time you had 33.333% more chance of getting the door with the car than if you'd stayed on your original choice of door. However, and somewhat frustratingly, I couldn't get the JavaScript to work well enough, so the yes button doesn't quite work. I hope to reexamine the code one day, when I have more time, and find out what I did wrong. 
