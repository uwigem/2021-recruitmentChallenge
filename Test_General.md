# Washington iGEM Web Developer Recruitment General Test

```
If you do not know HTML:

Generally, you can have HTML elements inside each other, like this:

<div> <h1> Hello </h1> </div>

This would be a `h1` header tag inside a `div` tag.

You can add styles to tags like the following (without using external CSS).
The following will add a solid black border that is 1px wide around the content,
which is "stuff"

<div style="border: 1px solid black"> stuff </div>

You can add multiple styles like this:

<div style="border: 1px solid black; color: green"> stuff </div>

This does the same as above, except makes the text color green.

===

HTML tags are usually in the body of a page. The body of a page is denoted
with body tags:

<body></body>

You can use languages like JavaScript to insert elements into tags
you can find on the page. Later in my language below, there will be a
method of doing that.
```

## Fictional language

Below, I have written code with a syntax I just made up. Try 
to reason through what it is doing and determine the output. 
This is meant to test your reasoning skills. Don't worry if 
you cannot solve the problem!

One thing to note: `>>` prints a statement on a new line in 
this fictional language, and `start[]` is the entrypoint to 
this program.

### 1.1

```
addTwo[a number] number {
    var outputVal number = a + 2
    output[outputVal]
}

start[] {
    >> addTwo[3]
    >> "I like React"
    >> addTwo[5]
}
```

What does this print out when it has finished? Your answer 
should look exactly like the expected console output. Enter 
your solution in the code block

```

```

### 1.2

```
const strings Strings = lib[strings]

doAnotherThing[a number] string {
    var outputValue string = strings^NumToString[a]
    outputValue = strings^Concatenate[outputValue, " people"]
    output[outputValue]
}

doSomething[a number, b func] {
    var passNumber number = a + 1
    var outputValue string = b[passNumber]
    output[outputValue]
}

start[] {
    >> doSomething[3, doAnotherThing]
}
```

What does this print out when it has finished?

```

```

### 1.3

```
const htmlDOM HtmlDOM = lib[htmlDOM]

start[] {
    var body HtmlDOM^BodyEl = htmlDOM^GetTagInDOM["body"]
    var div HtmlDOM^DivEl = htmlDOM^Create["div"]
    div^SetStyle["background-color", "red"]
    div^SetClass["test"]
    div^SetID["igem"]
    div^SetInnerText["this is text"]
    htmlDOM^InsertIn[body, div]
}
```

Complete the HTML without using `<style>` tags
```
<body>

</body>
```

### 1.4

Write code using this made up syntax (as best as you can) to
create a `<div>` with class `container`, with two `<div>` 
elements inside it each with a class `inner`. One of those 
`inner` `<div>` elements should have just the text `A` inside 
it, and one should have `B` inside it. Rather than repeat code, 
try to create a reusable function. Once you have created this `div`,
enter it into the `body` tag.

I've started it off for you.

```
const htmlDOM HtmlDOM = lib[htmlDOM]

customDivEl[insideString string] HtmlDOM^DivEl {

    output[           ]
}

start[] {

}
```