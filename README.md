# react-dashboard-notes

1. Exports are only done in the outermost level (for example , you can’t export a variable in a function that is already being exported)
2. You can export a useContext hook as a custom hook by providing it in a function - usually an arrow function- . Assigning it directly to a variable won’t work as hooks can only be used in functions .
3. You should study and implement React context API because it is amazing and saves a lot of prop drilling
4. React applies the rules of HTML semantics : We can’t nest a <p> tag inside another <p> tag because a p tag is used to wrap inline elements , so instead , we can wrap the second p in a div to override this issue (Actually, this is the first time to know this information regarding HTML semantics)
5. On passing attributes to some elements , for example an input , it is better to write checked = {true} instead of checked = “true” , this won't cause an issue with the 'true' value but with 'false', because 'false' is a string and not a boolean value . So putting curly braces around the booleans is important . 
