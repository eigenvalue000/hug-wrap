# hug-wrap

`hug-wrap` is.

[![npm version](https://badge.fury.io/js/hug-wrap.svg)](https://badge.fury.io/js/hug-wrap)
![Node.js version](https://img.shields.io/badge/node-%3E%3D%2014.0.0-brightgreen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Installation

Install the package using npm:

```bash
npm install hug-wrap
```

## Usage
Note: In your .env file, you must declare HUGGING_FACE_API_KEY=your_api_key_here
```
// .env file
HUGGING_FACE_API_KEY=asdf1234asdf1234
```
By setting your Hugging Face API key in your .env file, hug-wrap can automatically grab your API key from your .env file.
We do not store or save your API key. Examine the package to verify this. Your API key is local only to your project and not to the hug-wrap package.

---

### Test
#### Example usage:
```
const h = require("hug-wrap");

const main = async () => {
    console.log(await h.Test());
}
main()

```

Or:

```
const { Test } = require("hug-wrap");

const main = async () => {
    console.log(await Test());
}
main()
```