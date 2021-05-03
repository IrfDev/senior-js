# Questionaire: 

- How many years of production software development do you have?  
  
  
- What was your most challenging technical issue in terms of handle large state applications and how did you solved it?  
  
  
- Name your favorite JS stack and why?

 - What is your common data state management flow/ architecture
   
   (regardless the framework)?

  
- What are your workflow to solve building issues on clientside / frontend? (WebPack, Babel, etc) [Are they create his custom implementations, seek for new ones or whaaat?]

- Your favorite tools for data management and why?  

  
# Code assignment:  
  
## Build a state management package from scratch that covers:  
- Save data in objects/classes  
- Update data in Objects/classes  
- Dispatch an action each time the Object/ Classes changes

### Answer: 
This give us an idea if the candidate have a good understanding of how you can handle state patterns without any high level library.  
  
Event bus, flux / dispatch, observables, classes, etc.  
  
  
  
##  Bundle / WebPack workflow
This for us to test the build workflow:  
  

 1. Create a custom webpack / parcel / rollup build that includes
    support for SCSS, that can handle prefixes for css, including some
    CSS framework or library or UI framework like Tailwind, Bootstrap,
    etc. And have an output on dist/ directory  
    
 2. Create a function that fetch from X api and then create his own bundle from webpack named: custom-interview-bundle.js



### Answer: 
This is to test the WebPack workflow and how you can make custom builds without need of frameworks (at the end of the day if you know how to customize builds you can customize your plugins and bundles)  
  
 Custom ***webpack.config.js***

The output should have some scss processing, some file processing and a module with async functionallity.

  
  
## Promises:  
- Base Url: https://swapi.dev/api/
- Create a function that returns the planets (/planets) who had been appear in at least two movies and who residents (/people) have reptiles  (/species)

It only needs to be in one function and it needs to deal with at least two Promises

Extra point if you return an arrray of Promises, complete Promise for planets with the above conditions

Documentation: 
Planets: https://swapi.dev/documentation#planets
People: https://swapi.dev/documentation#people
Species: https://swapi.dev/documentation#species

  
  
### Answer: 
You just need to call the api three times to populate people and species then you have to filter the array by the conditions above. 
For the extra point, you need to wrap part of your functions in a Promise.all()
