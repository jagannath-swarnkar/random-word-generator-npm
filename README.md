# random-word-generator-npm

## Installation
```
npm install random-word-generator-npm
```

## Usage
```
import { generateRoomWithoutSeparator } from 'random-word-generator-npm';
```
`OR`
```
const rwgn = require('random-word-generator-npm')
```

```
const randomWord = generateRoomWithoutSeparator();
--- or ---
const randomWord = rwgn.generateRoomWithoutSeparator()
```
---

### Example
```
import React from 'react';
import { generateRoomWithoutSeparator } from 'random-word-generator-npm';

const App = () => {
    const [randomWord] = React.useState(generateRoomWithoutSeparator())
    return (
        <div>
            Random Word: ${randomWord}
        </div>
    )
}

export default App;

// Random Word: LoyalInjectionsIntendMore
```
### Stackblitz [Demo](https://stackblitz.com/edit/random-word-generator-npm?file=index.tsx)

---
### Other methods
- generateRoomWithoutSeparator: ƒ generateRoomWithoutSeparator()
```
call this method to get random name with a formated word
```
---
- randomAlphanumString: ƒ randomAlphanumString(length)
```
use this method to get random string of defined length
ex:- randomAlphanumString(10) //7ZJVVzOOfT
```
---
- randomElement: ƒ randomElement()
```
pass and array of string/words to get random word from that array
ex- 
const wordsList = ["Linkify","Videoplayer","ShowMore","ReactShare","ShortenUrl"]
randomElement(wordsList) //Linkify
```
- randomInt: ƒ randomInt()
```
use this methog to get random integer
```
---

- randomHexDigit: ƒ randomHexDigit()
- randomHexString: ƒ randomHexString()

---
# License
The project is released under the [MIT license](http://www.opensource.org/licenses/MIT).

# Contact
The project's website is located at https://github.com/jagannath-swarnkar/random-word-generator-npm

Author: Jagannath (jagannath18@navgurukul.org)