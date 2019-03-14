# Main title
## Section title
### Part title
#### Is it really possible to go further?
##### Damn yeah it is!
###### This has to stop...

---

*Emphasize*

**Strong**

---

List:
- First
- Second

Another one:
1. Hello
2. World
    * Sub-element
---

Links:

[Inline](http://www.christophech.com) link.

[Referenced][1] link.

[1]: http://www.christophech.com
---

Images:

![Alt](https://media.giphy.com/media/xT8qB2e02TaKVIsaU8/giphy.gif "Gif found on giphy")

---

Footnotes:

Sugar: 0% [^1]

[^1]: Well, maybe about 50% but not more!

---

Code:

```js
const binaries = ["1010100", "1101000", "1100101", "100000", "1110010", "1100101", "1110011", "1110101", "1101100", "1110100", "100000", "1101001", "1110011", "100000", "1101110", "1101111", "1110100", "100000", "1101001", "1101110", "1110100", "1100101", "1110010", "1100101", "1110011", "1110100", "1101001", "1101110", "1100111", "100000", "1100001", "1110100", "100000", "1100001", "1101100", "1101100", "101100", "100000", "1101001", "1110011", "1101110", "100111", "1110100", "100000", "1101001", "1110100", "111111"];

let secretMessage = "";

binaries.forEach(bin => secretMessage += String.fromCharCode(parseInt(bin, 2)));

console.log(secretMessage);
```

---

Quotes:
> Christophe, clean your room!