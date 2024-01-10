# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5


Try to put a blank line before...

# Heading

...and after a heading

I really like using markdown

&nbsp;&nbsp;&nbsp;&nbsp;I think I'll use it format all of my documents from now on with indent

# Line Breaks

This is the first line.  
And this is my second line.  
This is my third line.<br>
This is my fourth line.<br>

# Bold

I just love  **bold text**.  
I just love __bold text__.  
Love**is**Bold  
I just love <strong>bold text</strong>

# Italic

Italicized text is the *cat's meow*.  
Italicized text is the _cat's meow_.  
Italicized text is the <em>cat's meow</em>

# Bold and Italic

This text is ***really important***.  
This text is ___really important___.  
This text is __*really important*__.  
This text is **_really important_**.

# Blockquote

> Dorothy followed her through

> Dorothy followed her through many of the beautiful rooms in her castle
>
> The Witch bade her clean

# Nested blockquote
 > Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Lists

## Ordered List

1. First item
2. Second item
3. Third item
4. Fourth item  

## Nested Unordered List

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered List V1

- First item
- Second item
- Third item
- Fourth item

## Unordered List V2

* First item
* Second item
* Third item
* Fourth item

## Nested Unordered List

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## Horizontal Rules

***
 
---

Try to put a blank line before...

---

...and after a horizontal rule.

# Code

At the command prompt, type `nano`.  

At the command prompt, type <code>nano</code>.

## Escaping Backticks

``Use `code` in your Markdown file.``

<code>Use `code` in your Markdown file.</code>  

## Reference-style links

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"


# Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

## Adding titles

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## URL and Email Addresses
<https://www.markdownguide.org>  
<fake@example.com>

## Formatting Links
I love supporting the **[EFF](https://eff.org)**.  
This is the *[Markdown Guide](https://www.markdownguide.org)*.  
See the section on [`code`](#code).  

# Images

![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")

## Linking Images
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

# Tables

- :-- means the column is left aligned.
- --: means the column is right aligned.
- :-: means the column is center aligned.

| Item              | In Stock | Price |
| :---------------- | :------: | ----: |
| Python Hat        |   True   | 23.99 |
| SQL Hat           |   True   | 23.99 |
| Codecademy Tee    |  False   | 19.99 |
| Codecademy Hoodie |  False   | 42.99 |

# Programming Language within Markdown

`My Creator` (Inheritance `Micaela`)

## `C`
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    // Establish the seed for reproducibility
    srand(time(NULL));

    // Generate 5 random numbers between 1 and 10
    for (int i = 0; i < 5; ++i) {
        int random_number = rand() % 10 + 1;
        printf("Random number: %d\n", random_number);
    }

    std::cout<<"Diego Orlando Bustamante Palomino"<<std::endl;

    return 0;
}
```

## `C#`
```c#
using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```

## `C++`

```cpp
#include <iostream>
#include <math>
using namespace std;

int main()
{
    std::cout<<"Diego Orlando Bustamante Palomino"<<std::endl;

    return 0;
}

```

## `Javascript`
```js
let creator = "Diego Orlando Bustamante Palomino"
```

## `Ruby`
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

## `Java`
```java 
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Diego Orlando Bustamante Palomino!");
    }
} 
```



## `Python`
```python
print("Diego Orlando Bustamante Palomino")
```

## `HTML`
```html
<!DOCTYPE html>
<html>
<head>
    <title>My HTML Page</title>
</head>
<body>
    <h1>Diego Orlando Bustamante Palomino!</h1>
</body>
</html>
```

## `CSS`
```css
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
}
```

## `Ruby`

```r
set.seed(123)

# Generar 5 números aleatorios entre 1 y 10
random_numbers <- runif(5, min = 1, max = 10)

# Imprimir los números generados
cat("Números Aleatorios:", random_numbers, "\n")
```