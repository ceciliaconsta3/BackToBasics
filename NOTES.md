## NOTES

_Search Advance Topics in README.md_

_Truthy vs falsy statements = practice syntax_

_Unicode capitals come before lowers_

_Note: cache static element lookups_

* Coercion way to change entity to another datatype (e.g ```console.log("5" + 15) = "515"```)

* For ... in statement loops through the properties of an object
* For ... of statement iterates over the values of an iterable
    node lists have for each, not exactly a true array
```
const paragraphs = document.querySelectorAll('p');

for ( let p of paragraphs) {
    console.log(p.innerText);
}
```

* parameter = at function declaration
* arguments = passed into function

* function expression = expressed to the right of an equal sign
* function declaration = named function

* Bracket notation = use case: a space, or special character in the key. 

* object literals don't work on older browsers

* accessor (e.g: concat, join) vs mutator (e.g: push,pop,unshift,shift) array methods. **AVOID** mutators

* "Do Something" loops: forEach, for..in, for...of. 