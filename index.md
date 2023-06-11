# Hello I am Sauma Saha and this is my daily log

## 30th May, 2023

---

Same no classes for BCA prep but had presentations of seniors
1st presentation was given by Lakshmi, Subhash about Atlassian, and
2nd presentation was given by Nitin and Manikanta about E4R(YASKA and DIC)

Learnings

```
Document things well so that it's easy to understand
It makes it easier to use tools
Do automations where you can do
There are different ideologies in different programming language
Consider optimizations for later when required
Ask "Why"
Conidering different solutions
Build frameworks and habits to get things done
Time box explorations
Attend fun workshops
```

## 29th May, 2023

---

No classes today studied for BCA.

## 28th May, 2023

---

Sunday not much work studied for BCA made notes from chatgpt.

## 27th May, 2023

---

Today I learned about inversion of control using dependency injection.

- Learned how to inject a function and give control of the program to that function.
- Learned how to test a function by injecting another function.

  ```js
  const add = (a, b) => {
  	console.log(a + b);
  };
  ```

  > Note this function can't be tested because we dont have control when we do a console.log directly

- To test the function we have to inject the function that we want to give the control

  ```js
  const add = (a, b, print) => {
  	print(a + b);
  };
  ```

  > Here in the print function we can give any function refernce that will get called

- I also learned about what are the types of testing

  - Functional testing
  - Unit testing

- Also got to know about how to check if a read and write functions sync or async can be tested if they are woring fine or not
- Used mock functions to test them
- Learned about what is markdown(md) files and how to write them
- Learned how to host a github page
