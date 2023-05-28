# Hello I am Sauma Saha and this is my daily log

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
- Learned about what is markdown(md) files and how to write them
- Learned how to host a github page
