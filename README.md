oolib.js is a tiny JavaScript library that provides an original solution to the age-old problem of JavaScript OOP encapsulation.

You can find the documentation here: http://idya.github.com/oolib/.

#Files
* **oolib.js**
* **oolib-min.js** (the minified version)

The library will detect the environment it has been loaded into:
* an A(synchronous) M(odule) D(efinition) environment (RequireJS, curl.js, etc.)
* a CommonJS environment (typically server-side)
* if none of the above, it simply creates a global namespace variable named *oo*
