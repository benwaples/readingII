# Summary of Read04

## URLSearchParams
`URLSearchParams()` returns a object instance. 
`URLSearchParams.append()` will add a key value pair to the end of a URL. Essentially URLSearchParam will return the url, and you can treat it like an object?

## .toString() on URLSearchParams
calling `.toString()`on URLSearchParams will return a 'DOMString' (without question mark) that can be used in a URL. No clue about this one! Looks like there are a couple ways to do this same thing without using `.toString()`