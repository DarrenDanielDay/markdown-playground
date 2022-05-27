---
layout: page
title: My Page
permalink: /my-page/
---

# Hello My Page

> Displaying markdown

![DarrenDanielDay](/assets/DarrenDanielDay.jpg)

This is my custom page. Testing markdown basis.

## h2

## h2 copy

### h3

### h3 copy

#### h4

## h2 copy2

### h3 copy2

#### h4 copy

##### h5

###### h6

####### h7(not really h7)

## Highlights

## simple example

This is _leaning text_.\
This is also *leaning text*.\
This is **bold text**.\
This is also __bold text__.\
This is ~~deleted text~~.\
`colored highlighted text`

## Code

### C

```c
// A simple line note.
/**
 * multi-line note.
 * @author Darren_Daniel_Day
 */
#include <stdio.h>
#include <stdlib.h>
int main(){
    puts("Hello, Jekyll!");
    return 0;
}
```

### C\#

```csharp
// A simple line note.
/**
 * multi-line note.
 * @author Darren_Daniel_Day
 */
using System;
public class HelloJekyll{
    public static void Main(){
#if DEBUG
        Console.Writeline("In debug mode...");
#endif
        Console.Writeline("Hello, Jekyll!");
    }
}
```

### Java

```java
// A simple line note.
/**
 * multi-line note.
 * @author DarrenDanielDay
 * @version 0.0.1
 */
public class HelloJekyll
{
    public static void main(String[] args) {
        System.out.println(new HelloJekyll());
    }

    /**
      * @returns "Hello, Jekyll!"
      */
    @Override
    public String toString() {
        return "Hello, Jekyll!";
    }
}
```

### Python

```python
class HelloJekyll:
    def __init__(self):
        print("HelloJekyll.__init__()")
        f("Jekyll")
        f("Jekyll")

def EchoIt(obj):
    print("EchoIt init.")
    return obj

@EchoIt
def f(s:str)->int:
    '''Simple function.'''
    print("Hello, {}!".format(s))
    return 0

# Simple note.
HelloJekyll()
```

### Typescript

```typescript
let Jekyll:str = "Jekyll";
console.log(`Hello, ${Jekyll}!`);
```

### JavaScript

```js
console.log("Hello, Jekyll!");
```

### HTML5

```html
<!--some note-->
<html>
    <h1>Hello, Jekyll</h1>
    <script>
        alert("Hello, Jekyll!")
    <script>
</html>
```

### Text

```text
Hello, Jekyll!
```

> one line quote.

Random text to divide quotes.

> Blocked quote.\
> line2.
> also line 2.
>> quote in quote\
>> line2
>>>> skipped qoute
>>>>>>>> inner

Random text to divide quotes.

> ___~~[in quote link with style supported.](https://www.google.com)~~___

## List

1. First ordered list item

2. Another item
    * Unordered sub-list.
    1. Ordered sub-list.

3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list

4. And another item.  
    Some text that should be aligned with the above item.

* Unordered list can use asterisks
* Unordered list item 2

```note
Unordered list prefix can be '-', '+' and '*'.
But in one document, the prefixes should be the same.
```

## Links

[click me to the top](#Hello,-Jekyll)

## [click me to the bottom](#bottom)

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links.
<http://www.example.com> or <http://www.example.com> and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org

[link text itself]: http://www.reddit.com

[github.com]

[github.com]: https://github.com

<Darren_Daniel_Day@hotmail.com>

## bottom
<p>
<script>alert("Hello, Jekyll!");console.log("Hello, console!");</script>
</p>

<script>
  console.log('Executed javascript!');
</script>
