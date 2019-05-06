# Buster Code Challenge
This is intended as an exercise to see how you approach an issue and implement a solution.

### Time allotment
We respect your time and don't want you spending more 3 hours on your challenge. We want to get a sense of your thought process and development patterns. If there are features you don't have time to implement, feel free to use pseudo code to describe the intended behavior.


### What to submit
- README
  - Describe your solution and reasoning behind your choices. Include any trade-offs and what you might do differently given more time. 
- Repository
  - Preferably on github. We won't accept archives or single files.
- App
  - Preferably this is hosted somewhere online

### What we look for
- Correctness: does it work as asked?
- Clarity: README is easy to comprehend and includes necessary details
- Code quality: is the code readable? can it be maintained easily? is there consistent styling?
- Testing: does automated testing work and covers critical components? can it be upgraded easily in case changes are made to the app?
- UX: can the user understand the interface? is it intuitive?

## Challenge description
- Create an web app where I can manage "Companies"
  - Each Company has a name, latitude, longitude
  - Import `companies.json` as seed data (it's included in this repository)
  - I can create, edit, and delete companies
- Create a page with a map of US that shows Companies that have been entered as pins on the map, with a list of the companies below
  - Let user enter a latitude, longitude, and radius that limits the list of companies shown to those only inside the circle specified by the params.