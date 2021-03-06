# Social Curator Developer Assessment
In this project, you'll be using Node and Typescript to build an employee management system. Feel free to go at your own pace but the assessment should, ideally, take no longer than one hour.

## Notes
- You'll be using a tree to keep track of employees and their relations.
- The comments in the code are just guidelines to help scaffold your thought process but are, by no means, strict requirements. Feel free to tackle the problem as you see fit.
- There is a JSON file provided in this repo with all the employees and their bosses. But there's been a mistake in the data collection process and now some `name` fields actually contain emails. One of your functions will need to normalize the data and pull their first name from the email.

## Requirements
- Fork this project to begin your work.
- The project was written in Javascript. Please convert the project to use Typescript and define types for all functions/variables.
- Build the following functions:
  - `generateCompanyStructure`
  - `hireEmployee`
  - `fireEmployee`
  - `promoteEmployee`
  - `demoteEmployee`
  - `getBoss`
  - `getSubordinates`
- An `EXPLANATION.md` file that details your thought process:
  - Instructions on how to install and run your code
  - Any noteworthy logic/style decisions you made? If so, what is your reasoning?
  - If you had more time, what improvements would you implement?
  - **Bonus**: What is the time complexity of each function in your code?
  - **Bonus**: There are two functions that have very similar logic and could be merged into one. Which functions do you think can merged and why?
- Lastly, make a pull request in Github for this repository with your forked changes. 

### Expected Output
The following should be logged to the console:
```
Normalizing JSON file...
Generating employee tree...

[hireEmployee]: Added new employee (Jeb) with Sarah as their boss 
[fireEmployee]: Fired Alicia and replaced with Sal 
[promoteEmployee]: Promoted Jared and made Bill his subordinate 
[demoteEmployee]: Demoted employee (demoted Xavier and replaced with Maria) 

[getBoss]: Bill's boss is Jared 
[getSubordinate]: Maria's subordinates are Xavier, Morty, Jared 

```