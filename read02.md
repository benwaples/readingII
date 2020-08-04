# Read 02 Sumamry

## Applying Atomic Design
### Part 1
Atoms are so small that if you tried to find anything smaller, you would have to split an atom and it would be an atom anything any more. When designing a page, split it up into large sections (organisms), then smaller sections (molecules), then get the elements that can't be broken up any further (atoms).

### Part 2
First create your atoms. Not all atoms are the same, so just make your atoms and tell it what to do later. For example a `<p>` tag is for text -- tell it what size of text later on. Then your molecules (reusing atoms) and then combine your molecules to have organisms.

## Thinking In React
I keep seeing a ? being used in the code and Idk what that does. Other than that, this seems to be another example of the atom articles from before. These are good questions when looking at data and making a react app 
1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.