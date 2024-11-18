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

# FlexBox

flexbox have 4 types of properties

- flex-direction --> It is to decide which is the main axis and which is the cross axis e.g. row,row-reverse,column,coloumn-reverse
- flex wrap --> it will wrap up the content according to the size
- justify-content --> it is use to justify the content across main axis
- allign-items --> it is use to allign items across the cross axis

<b> For applying above properties just add

```
display:flex
```

Most common properties of container are

- gap
- grid-template-row
- grid-template-col
- justify-content
- allign-items

if you write to make columns in grid

grid-template-columns: 1fr 1fr 1fr 1fr

here fr means fraction

instead of that you can write

```
grid-template-columns:repeat(4,1fr)
```

# Transform

There are main 4 properties of Transform

- scale --> To increase or decrease the size
- Skew --> To tilt the element
- rotate --> Rotate the element by certain deg
- Translate

# Transition

- Duration
- Delay
- Property
- family function --> ease in ,ease out , ease in out, cubic breezer
