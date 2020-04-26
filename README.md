# noteworthyTeX
Some behaviours, bugs and code snippets worth remembering
This starts as a list of things I keep looking up every second month or so...

## longtabu and strange line separation
In an `X` column in a `longtabu`, rows having at least one cell with more than one line miss a strut. This needs to be added explcitly in the declaration, e. g.:
  
    \begin{longtabu}{@{}X[2,l]<{\strut} X[1,l]<{\strut}@{}}
    
## Tracking
