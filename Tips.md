- When learning a new technology, it's natural to try and squeeze it into a familiar shape. But I promise you, you'll have a much better time learning to swim with the currents, rather than trying to fight against it.

- Always a good idea to do things in a conventional DOM friendly way.
  
- crypto.randomUUID() - random unique ID
  
- use array index only when order of item won't change

- In component instances the state of component gets stored, when component unmounts, that component instance is destroyed and state also goes away with it, and when it mounts again, new component instance is created.

- Always use 'const' when let not necessary
  
- Try to update the code to be simpler, rather than just fixing warnings or bugs.
  
- We can track whether elements are on viewport via IntersectionObserver API
  
- Any time we can minimize space for errors, it's a good thing.

- Make sure to safeguard the code as against as many use cases you can.
  
- Better to break components into smaller components, into separate files, for easy management.
  
- We can often improve app performance and unnecessary re-renders using alternate strategies like changing application / component structure.
  
- What if we need a generic utility, something like useWindowSize? Should we build it from scratch, or use the library? Here's my suggestion: you should build it yourself if you think you'd learn something from the process. That's a solid investment of your time and energy.

- I do think there's a danger in becoming too dependent on these libraries. If you automatically reach for a library whenever you encounter a new problem, your skills will atrophy. Sooner or later, you'll run into a problem that can't be solved with a library, and you won't have the skills to be able to solve it yourself!

- component when given attribute with value of 'undefined' react will strip of that from props object

- I've learned to use a “precise” check by default. It's a bit more typing, but a heck of a lot less thinking.
  
- Always take benefit of composition of component, using primitive low level  components to develop higher level components

- In React, we're 100% allowed to copy props into state as long as it's clear that we're setting the initial value, and that changes to that prop won't affect the state.

- Principle of Least Privilege - descendant components must not have more privilege than they need to accomplish particular tasks.
- 
- JSON.stringify takes second parameter 'space' for beautifying the output