# Hello I am Sauma Saha and this is my daily log

## 13th June, 2023

---

Today I learned about img and hr tag in html

- with img tag we can insert an image in our page, and
- hr tag gives a horizontal line in the page

```html
<img src="/SomeImagePath.jpg" />
or
<img src="SomeImageLink.jpg" />

<hr />
<!-- gives a horizontal line -->
```

Built a page of STEP - 9 which contains github account links of all and details about them

## 6th June, 2023

---

Today we learned about Events

- How to handle events
- what events are there, Example
  - process.stdin.on("data")
  - process.stdin.on("end")
  - process.stdin.on("err")
- how to create a readStream using createReadStream() function so that we can generate events on file read and operations on file

```js
const readStream = fs.createReadStream();
readStream.on("data", "utf-8", "file_path");
```

Also got to know about EventEmitter Class which has a on method that registers events and and emmit method that emmits a specific event when something happens like certain key is pressed in keyboard

- We can create our own events using the EventEmitter class

Got to know about Set class

## 5th June, 2023

---

Today i learned about packages in node

Package in node is a bundle of files grouped together sp that we don't jave to require them individually we can require the whole package and we will get all the exports

- how to make a package

```sh
npm init
```

> Note: this initializes the npm in the current project and we should always do a "npm init" in the root of the project

- After npm init a pop up comes like

```sh
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help init` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (todayilearned)
```

- We have to fill the necessary info and a package.json file is created with the info

```json
{
  "name": "todayilearned",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}
```

- We always don't have to do "npm init" if there is a package.json in the directory with necessary details it will be treated as a package

- Made some package of our own installed it and when we install a package we get a folder called node modules and that we shouldn't put it in our git

```sh
npm install <package_name>
```

> Note: to install a package the current project should also be package

- Also got to know about how a package is installed by npm from the internet(npmjs.com) which is not present in my machine

- Installed some packages from npmjs.com like (table, colours)

- To version control the packages installed npm creates a package-lock.json

## 3rd June, 2023

---

Nothing much happened. Presentations were given by

- Ritika(McKinsey)
- Swapni, Tanmay, Nilam and Vivek(Mercedes)

## 2nd June, 2023

---

Went to give BCA Programming in C++ exam

## 1st June, 2023

---

Went to give BCA English Exam

## 31st May, 2023

---

Went to give BCA Communication Skills Exam

## 30th May, 2023

---

Same no classes for BCA prep but had presentations of seniors

- Lakshmi, Subhash prensented about Atlassian, and
- Nitin and Manikanta presented about E4R(YASKA and DIC)

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
