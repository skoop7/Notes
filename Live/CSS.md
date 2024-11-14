# CSS

CSS- Cascading style sheet

Cascading - It means everything is implemented in streight line

1. Internal
2. External
3. Inline

Internal and external have same priority . Its decided on which is mentioned first.

While Inline have more priority than both of them

## CSS Selector

There are 4 Selectors

1. Tag/ID/Class/Attribute
2. Nested Selector
3. Grouped Selector
4. Pseudo Selector

id for particular element is unique. class name can be same for multiple same.

Nested selector example

```
.purple>h1
{
    background-color:"purple";
}
```

Grouped selector example

```
.para,.para1,.para2
{
    font-size:larger;
}
```

Pseudo selector example

```
.c2:hover{
    background-color:yellow;
}
```

- vw- viewport width

  e.g. 50 vw- 50% of the screen width

- percentage - it is scale relative to its parent

  e.g. - 25% - 25% of its parent .

<b> Text Decoration

```
.wavy{
    text-decoration-line:underline;
    text-decoration-style:wavy;
    text-decoration-color:red;
}
```

# Box Model

- Padding - The CSS padding properties are used to generate space around an element's content, inside of any defined borders.

- Border - A border that goes around the padding and content

- Margin - Clears an area outside the border. The margin is transparent

# Positions

- Static - It is a default position

- Sticky - It is stick to one position with parent

- fixed - Fixed on that position

- Absolute - It changes according to nearest non static Parent element

- relative - It changes according to its prior position or original position
