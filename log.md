# 100 Days Of Code - Log - Andrew Zhang

> *This will be more like a diary of thoughts and learning rather than dedicated to an hour a day on a certain project.*

## Planned Todo List
- [x] Finish Colt Steele's WebDevBootcamp.
- [ ] Finish FreeCodecamp's Responsive Web Design Course.
- [ ] Build at least 2 Personal Projects.
- [ ] Build at least 3 Mini Projects dealing with a certain functionality.
- [ ] Start Colt Steele's React Course.
- [ ] Practice on Front/Backend Coding Challenge.
- [ ] Continue with StuMe after Uni
- [ ] Check out JS platformer [Building a platformer in javascript](https://www.youtube.com/watch?v=opiWzi0KWjs&t=4s)
- [ ] Check out Twitter bot [Coding Train Twitter-Bot Tutorial](https://www.youtube.com/watch?v=s70-Vsud9Vk&t=33s)
- [ ] Finish Code with Node
- [ ] Sentdex Basic JS tutorials

### Day 1: May 14, 2019

**Today's Progress:**
* Worked on University Project trying to understand how to use express-validation package to do custom validations. Finally managed to get through the validation and check that it works (I hope). Just need to decide on the details now such as how long to make the minimum length of password etc.
* Read through MarkDown Guide by Github.
* Started looking through the FreeCodeCamp Curriculum and had a start at the Responsive Web Design Certification Curriculum. Was interesting to learn some small bits about HTML that I didn't realise like jumping to different parts of the page using anchor tags and # to an id. Got through a bit of the HTML curriculum as a break from University Project.
* Got stuck on making a Date picker that blocks past dates from being selected.

**Things to Remember**
* express-validator custom validations (Ones that start with body(*field*).custom(value => {) must always have a return false/true or else will have an Invalid type error (seen in postman when doing Post Request)
* Don't spend so much time on one small thing when there are more important things to work on!

**Thoughts:**
* Started this challenge in the hopes of entering a constant cycle of learning and exposing myself to more in the dev community. So far it is pretty interesting reading through other peoples challenges and progress. Hoping to plan out a proper routine and something I want to build as a project.

**Link(s) to resources I found interesting:**
* [Medium Post: FreeCodeCamp - How to perform custom validation in your express.js app](https://medium.freecodecamp.org/how-to-perform-custom-validation-in-your-express-js-app-432eb423510f)
* [Express-Validator Documentation](https://express-validator.github.io/docs/custom-validators-sanitizers.html)
* [Github Guide to Mastering Markdowns](https://guides.github.com/features/mastering-markdown/)
* [Express-Validator Optionals](https://stackoverflow.com/questions/24681971/express-validator-how-to-allow-optional-fields)
* [Express-Validator Check alphanumeric if not empty](https://stackoverflow.com/questions/43571469/node-js-express-validator-check-if-field-is-numeric-only-if-it-is-not-empty)

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)
* [FreeCodeCamp Daily-Work Timeline](https://www.freecodecamp.org/fcc863fdc60-4853-4520-93da-668ce5ffd9b2)

### Day 2: May 15, 2019

**Today's Progress:**
* Reworked university websites timepicker
* Got through some of WebDevBootcamp on jQuery (I've actually finished most of the course but I skipped some parts to get to sections I needed at the time. And now I'm going back through the parts I've skipped.

**Things to Remember**
* Include jQuery files at the bottom and in app.js make sure to include __dirname.
* Keep things organised and commented out so you don't get confused later on.
* Tempus Dominus uses startDate instead of minDate.
* Errors can occur when having two jQuery script tags in code. Make sure not to double up!

**Thoughts:**
* Got really stuck trying to work on this datetimepicker and making sure everything is correct. Finally got it working but really shouldn't stay up until 4am working on it. It was satisfying to finally get things working and understand more about what I got wrong and why it behaved the way it did!

**Link(s) to resources I found interesting:**
* [Tempus Dominus Bootstrap4](https://tempusdominus.github.io/bootstrap-4/Usage/) (Used for timepicking)
* [Convert date of dd/mm/yyyy to Date format (e.g Thu 4 May) stackoverflow](https://stackoverflow.com/a/4048698/11505818)

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)
* [Colt Steele WebDevBootcamp](https://www.udemy.com/the-web-developer-bootcamp/)

### Day 3: May 16, 2019

**Today's Progress:**
* Made event default pictures based off type of event selected.
* Fixed CSS Styling for website.
* Finished Introduction to Basic HTML and HTML5 on FreeCodeCamp.
* Split textarea input into an array to output with lines (previously newlines would not be registered).

**Things to Remember**
* Turning off autocomplete for text boxes is autocomplete:"off". Do this for dates where input type="text"!
* Split up CSS files to be more manageable.

**Thoughts:**
* Didn't do too much today, but the changes made were good. Still much to do, hopefully tomorrow I can start on something more substantial! Should sleep earlier! Also need to figure out how to manipulate MazeMap as it ignores footers and any other forms of styling.

**Link(s) to resources I found interesting:**
* [Breaking up CSS files](http://alistapart.com/article/progressiveenhancementwithcss/)
* [Javascript Grammar - Greg Sidelnikov (Book)](https://www.amazon.com/JavaScript-Grammar-Greg-Sidelnikov/dp/1091212163/ref=as_li_ss_tl?keywords=javascript+grammar&qid=1553679757&s=gateway&sr=8-3&linkCode=sl1&tag=twitter-subteach-20&linkId=5c2d3f93879fad6cfe766f185410cef6&language=en_US)
* [Svelte Component Framework](https://svelte.dev/) (This is similar to React/Vue, except it runs at build time)
* [Svelte YGLF Video](https://www.youtube.com/watch?v=AdNJ3fydeao)

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)
* [FreeCodeCamp Daily-Work Timeline](https://www.freecodecamp.org/fcc863fdc60-4853-4520-93da-668ce5ffd9b2)

### Day 4: May 17, 2019

**Today's Progress:**
* Started a js course teaching basic concepts through the creation of a game.

**Things to Remember**
* Look properly through form validation and ensure it is clear and concise.

**Thoughts:**
* Didn't do much again today. Need to fix some bugs in website. Got to focus and sleep earlier.

**Link(s) to resources I found interesting:**
[Javascript Form Validation](http://javascript-coder.com/html-form/javascript-form-validation.phtml)

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)

### Day 5: May 18, 2019

**Today's Progress:**
* Not much, just worked on a university assignment and finished the jQuery section from Colt Steele's WebDevBootcamp

**Things to Remember**
* Understand the usage of fork() and exec() family.

**Thoughts:**
* Been swamped with university work so won't be able to do much coding and learning of my own (outside of school work). Need to sleep earlier. Maybe get some exercise to refresh my mind.

**Link(s) to resources I found interesting:**
[Coding Train Twitter-Bot Tutorial](https://www.youtube.com/watch?v=s70-Vsud9Vk&t=33s)

**Link(s) to work:**
* [Colt Steele WebDevBootcamp](https://www.udemy.com/the-web-developer-bootcamp/)

### Day 6: May 19, 2019

**Today's Progress:**
* Spent the whole day doing university projects. Not much else.

**Things to Remember**
* Understand the usage of remember popen() usage!

**Thoughts:**
* Been swamped with university work so won't be able to do much coding and learning of my own (outside of school work). Need to sleep earlier. Maybe get some exercise to refresh my mind.

**Link(s) to resources I found interesting:**
[Linux Exec System Call](https://www.youtube.com/watch?v=mj2VjcOXXs4)
[Linux Fork and Exec](https://www.youtube.com/watch?v=l64ySYHmMmY)
[Building a platformer in javascript](https://www.youtube.com/watch?v=opiWzi0KWjs&t=4s)

**Link(s) to work:**
* N/A

### Day 7: May 25, 2019

**Note: Took a break from this as I had a heavy load of University projects and didn't want to include it as part of my 100DaysOfCode but the workload has come back down so I'll be back to working on some side things!**

**Today's Progress:**
* Finished Section 17 - Color Game Project in Colt Steele's WebDevBootcamp
* Made Todo List Project

**Things to Remember**
* Paper.js is a great animation/graphics library!
* Howler.js for sounds!

**Thoughts:**
* Finally finished Colt Steele's WebDevBootcamp. It's been an amazing course and Colt is an amazing instructor. I bought this course about 9 weeks ago and have been doing it throughout the semester alongside my University courses so it's great to finally be finishing it after so long. I will probably take a look at some other courses to learn some more skills before hopping into his React course as I want to use React to help my mum build a website for her rental properties in Queenstown!

**Link(s) to resources I found interesting:**
[Paper.js](http://paperjs.org/)
[Howler.js](https://cdnjs.com/libraries/howler)

**Link(s) to work:**
* [Colt Steele WebDevBootcamp](https://www.udemy.com/the-web-developer-bootcamp/)

### Day 8: May 26, 2019

**Today's Progress:**
* Finished Basic CSS on FreeCodeCamp Responsive Web Design Curriculum

**Things to Remember**
* Learnt that there are variables in CSS!!! And can make cute drawings that are animated!

**Thoughts:**
* Should've done more work but was writing up a report for my Assignment. Got 6 hours of class tomorrow but hopefully can fit in some more! Also should sleep earlier and plan out my tasks to do as exams get closer!

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [FreeCodeCamp Public Portfolio](https://www.freecodecamp.org/fcc863fdc60-4853-4520-93da-668ce5ffd9b2)

### Day 9: May 27, 2019

**Today's Progress:**
* Did some of the Applied Visual Design on FreeCodeCamp

**Things to Remember**
* Just some recap for me as I've covered most of this already.

**Thoughts:**
* Need to sleep earlier, last two projects to get done before studying for exams.

**Link(s) to resources I found interesting:**


**Link(s) to work:**
* [FreeCodeCamp Public Portfolio](https://www.freecodecamp.org/fcc863fdc60-4853-4520-93da-668ce5ffd9b2)

### Day 10: May 28, 2019

**Today's Progress:**
* Medium Articles on JS

**Things to Remember**

**Thoughts:**
* Spent most of the day on projects again, but did read through some interesting articles on medium

**Link(s) to resources I found interesting:**
[JS Async & Await](https://medium.com/@zellwk/an-introduction-to-javascripts-async-and-await-edb313356677)
[JS Promises](https://zellwk.com/blog/js-promises/)
[JS Callbacks](https://zellwk.com/blog/callbacks/)
[JS ES6](https://zellwk.com/blog/es6/)

**Link(s) to work:**
* [FreeCodeCamp Public Portfolio](https://www.freecodecamp.org/fcc863fdc60-4853-4520-93da-668ce5ffd9b2)

### Day 11: May 29, 2019

**Today's Progress:**
* User Profiles on YelpCamp

**Things to Remember**

**Thoughts:**
* Made user profiles on yelpcamp. Was quick and fun, and will definitely implement on my website!

**Link(s) to resources I found interesting:**

**Link(s) to work:**
[YelpCamp](https://yelpcamp9799.herokuapp.com/campgrounds)

### Day 12: May 30, 2019

**Today's Progress:**
* Did more of FreeCodeCamps Applied Visual Design

**Things to Remember**

**Thoughts:**
* Finished another university project and just got one more! Excited to have more time for learning outside of uni!

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [FreeCodeCamp Public Portfolio](https://www.freecodecamp.org/fcc863fdc60-4853-4520-93da-668ce5ffd9b2)

### Day 13: May 31, 2019

**Today's Progress:**
* Add User Profiles to YelpCamp

**Things to Remember**

**Thoughts:**
* Getting started on my final project and did a tutorial on user profiles before trying to add to my website for the project.

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)

### Day 14: June 1, 2019

**Today's Progress:**
* Add User Profiles to StuMe

**Things to Remember**
* Always make sure Code is neat and organised. Messy code is a N I G H T M A R E

**Thoughts:**
* Getting started on my final project and did a tutorial on user profiles before trying to add to my website for the project.

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)

### Day 15: June 2, 2019

**Today's Progress:**
* Submitted final project
* Sentdex Running functions on an Interval with setInterval and Conditionals

**Things to Remember**

**Thoughts:**
* Finished all projects for the semester. Now hopefully I have more time for side things! Learning more about the canvas. Quite interesting. Looking to do more tomorrow!

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [University Project Website](https://stume.herokuapp.com) (Not linking github as it is private for tutors to mark)

### Day 16: June 3, 2019

**Today's Progress:**
* Sentdex OOSD & For Loops
* Code with Node module 1

**Things to Remember**

**Thoughts:**
* Studying for exams and doing a bit of coding on a new tutorial and gonna try out react too

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [Sentdex JS Tutorial Playlist](https://www.youtube.com/playlist?list=PLQVvvaa0QuDf2_A04M-m0WubgLf2_geR6)

### Day 17: June 4, 2019

**Today's Progress:**
* Code with Node set up routes and database

**Things to Remember**

**Thoughts:**
* Did some more of the online course, currently trying to think how I could adapt the course so it's not just doing what he's doing but putting my own twist on it. Managed to get a good amount of exam study done today too, so quite productive today!

**Link(s) to resources I found interesting:**

**Link(s) to work:**
* [Code with Node](https://www.udemy.com/code-with-node/)

### Day 18: June 5, 2019

**Today's Progress:**
* Code with Node set up models and some user authentication

**Things to Remember**
* Async/Await and Promises and how to use them!

**Thoughts:**
* Finished some more of Code W/ Node and also finished his Ajax course. Quite interesting but a bit complex, got to learn more and apply it!

**Link(s) to resources I found interesting:**
* [Async/Await/Promises/Callbacks Tutorial](https://www.youtube.com/watch?v=PoRJizFvM7s&t=185s)

**Link(s) to work:**
* [Code with Node](https://www.udemy.com/code-with-node/)
* [Jquery Ajax](https://www.udemy.com/jquery-ajax/)

### Day 19: June 6, 2019

**Today's Progress:**
* Mostly worked on exam study

**Things to Remember**

**Thoughts:**
* Organise time better and don't get distracted! Procrastination is a monster.

**Link(s) to resources I found interesting:**

**Link(s) to work:**

### Day 20: June 7, 2019

**Today's Progress:**
* More exam study

**Things to Remember**

**Thoughts:**
* Walked around outside for break, should do this more often. Studying is a bit behind but will try to catch up onto my schedule.

**Link(s) to resources I found interesting:**

**Link(s) to work:**

### Day 21: June 8, 2019

**Today's Progress:**
* More exam study

**Things to Remember**

**Thoughts:**
* Cooking more instead of using exam study as an excuse to order food. Saves money is healthier but I do end up spending quite a while cooking sometimes. Goes back to time management.

**Link(s) to resources I found interesting:**

**Link(s) to work:**

### Day 22: June 30, 2019

**Today's Progress:**
* Did freeCodeCamp's Applied Accessibility section.

**Things to Remember**

**Thoughts:**
* Exams are finally over so I can dedicate more time to this! Looking forward to doing a lot this break time!

**Link(s) to resources I found interesting:**
* [The Coming Software Apocalypse](https://www.theatlantic.com/technology/archive/2017/09/saving-the-world-from-code/540393/)
* [HTTPS on your local environment](https://www.freecodecamp.org/news/how-to-get-https-working-on-your-local-development-environment-in-5-minutes-7af615770eec/)

**Link(s) to work:**
* [Curriculum for FreeCodeCamp](https://learn.freecodecamp.org/)
