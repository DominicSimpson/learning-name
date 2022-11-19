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

06/11/2022
###### I'm confused as to why adding a second true clause makes this pass on Execute Program? I have to use Reduce to write a function that returns true if all array elements are true.
```function allTrue(values) {
  return values.reduce((acc, current) => acc && current, true);
  ```

---

17/11/2022

We [finished the Testing project](https://github.com/fac26/todo-derek-dominicS-georgia), involving constructing a To-Do list. I really struggled to incorporate the existing code with the TDD testing, though I did get close with the test question, "test("Can the user delete a task from the list?")". My hope is that I will eventually get used to incorporating TDD in my code simply from doing it so many times. 

---
