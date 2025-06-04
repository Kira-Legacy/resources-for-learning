# Resources-for-learning
A repository where I keep learning resources address. You are invited to check them out to improve your technical skills as a developer.

## From the course "The Complete 2024 Web Development Bootcamp" taught by Dr. Angela Lu

### For responsiveness using Media Quieries
- Mobile Devices: 319px - 480px
- iPads and Tablets: 482px - 1200px
- Laptops: 1201px - 1600px
- Desktops: 1601px and more.

### For learning Flex-box
- <a href = "https://appbrewery.github.io/flexboxfroggy/" style="text-decoration:none;"> Flex box froggy game </a>

### For learning Grid-box
- <a href = "https://appbrewery.github.io/gridgarden/" style="text-decoration:none;"> Grid Garden Game </a>

### For minifying code
- <a href = "https://www.minifier.org/"> Minify your code </a>
- Minifing means reducing the size of your code through space and comment removal.

### Short Notes
- Higher order functions are functions that can take other functions as inputs.
- Node is not a JavaScript framework, rather Node is a runtime environment. Node allows us to run JS on a computer and not just limited on the computer.


### Fun
- Would like to have fun with the fake hacker typer? then checkout <a href = "https://hackertyper.com/"> hackertyper </a>

### Learn Enough Command Line to be Dangerous
- Visit the <a href = "https://www.learnenough.com/command-line-tutorial"> learn enough </a> website

### Common words and Abbrevations

- CDN stands for Content Distribution Network. I have discovered this when learning BootStrap.
- Vanilla language = Pure language without any external libraries and frameworks
  Example: Vanilla CSS = Pure CSS without bootstrap or tailwind css and soon.
- NPM = Node Package Manager
- CJS = Common JavaScript
- ESM = ECMAScript Modules
- EJS = Embedded JavaScript
- JSON = JavaScript Object Notation. This is basically a configuration file.

### HTTP return codes cheat sheet
- GET => Request resource.
- POST => Sending resource.
- PUT => Update by replacing resource.
- PATCH => Update by patching up a resource.
- DELETE => Deleting a resource.
- 1xx => Hold on
- 2xx => Here you go
- 3xx => Go away
- 4xx => You (the user) screwed up 
- 5xx => I (the server) screwed up

### Version control using git and GitHub

Steps to using the command line to commit on a github repository.
#### Creating Local Repostitory


      1. git init 
      2. git add example1.example1 example2.example2
      3. git commit -m "Your commit message here"
      - git status --> to check the status 
      - git log --> to get information about recent commits made.
      - git diff filename --> check the difference of a file from the original version
      - git checkout filename --> rollback a file to it's last version

  #### Creating Remote Repostirory (On Github or others)
      1. git remote add origin github_repository_url
      2. git branch -M main --> Change the deafult branch to main ( the code is going to be pushed here)
      3. git push -u origin main --> Push the code
  #### Git Cloning
    git clone url
  #### Sample cloning URLs
- https://github.com/inolen/quakejs.git
- https://github.com/clupasq/word-mastermind.git

### APIs
- https://www.bored-api.appbrewery.com/endpoint?query=value&query2=value2. bored-api.appbrewery.com ---> base URL   endpoint ---> endpoint  ?query=value&query2=value2 ---> query

### JSON
- To see a humanoid version of JSON ---> jsonviewer.stack.hu
- A password decoding website ---> base64decode.org
- JSON visualizer --> <a href = "https://jsonviewer.stack.hu/">jsonviewer.stack.hu</a>

### Angular
- Angular supports MVC architecture. MVC architecture allows developers to separate thier code into 3 distinct parts, namely Model, View and Controller.

#### Collaboration addresses
- https://github.com/MunGell/awesome-for-beginners.git

#### Random Image Resource
- https://picsum.photos/

### React
    1. npx create-react-app your-react-app-name
    2. cd your-react-app-name
    3. npm start
1. Create a new react project.
2. Change the directory into that project folder.
3. Start the server.

#### React's Map, Reduce, Find and FindIndex functions.
- There are three ways to execute these functions.
##### Map Function
const numbers = [5, 10, 15, 20, 25, 30];

1. function square(num) {
  return x * x;
};
- const squareNum = numbers.map(square);
- console.log(squareNum);

2. const squareNum = numbers.map(function (num) {
  return x * x;
});  
- console.log(squareNum);

3. const squareNum = numbers.map((num) => x*x);
- console.log(squareNum);

##### Reduce Function

const numbers = [5, 10, 15, 20, 25, 30];

1. function accNum(accumulator, currentNumber){
      return accumlator + currentNumber;
   };
- const accumulatedNum = numbers.reduce(accNum);
- console.log(accumatedNum);

2. const accumulatedNum = number.reduce(function (accumulator, currentNumber){
      return accumulator + currentNumber;
   });
- console.log(accumulatedNum);

3. const accumulatedNum = number.reduce((accumulator, currentNumber) => accumulator + currentNumber);
- console.log(accumlatedNum); //For checking the output
   
#### Find Function

const numbers = [5, 10, 15, 20, 25, 30];

1. function findNum(num){
    return num < 15;
   }
- const findNumber = numbers.find(findNum);
- console.log(findNumber);  //For checking the output

2. const findNumber = numbers.find(function (num) {
   return num < 15;
   });
- console.log(findNumber);

3. const findNumber = numbers.find((num) => num<15);
- console.log(findNumber);

##### FindIndex Function

- const numbers = [5, 10, 15, 20, 25, 30];

1. function findNum(num){
    return num < 15;
   }
- const findNumber = numbers.findIndex(findNum);
- console.log(findNumber);  //For checking the output

2. const findNumber = numbers.findIndex(function (num) {
   return num < 15;
   });
- console.log(findNumber);

3. const findNumber = numbers.findIndex((num) => num<15);
- console.log(findNumber);

### Starting Servers of different Frameworks

    1. node entryfilename.js / nodemon entryfilename.js (If you have nodemon installed)  => For node, Express
    2. npm start  => For react
    3. ng serve   => For Angular

    
