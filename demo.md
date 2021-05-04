# Learning Markdown and github flavour of markdown features

<!-- headings -->
  <!-- like html h1 to h6 we have 1# to 6# if no # is defined it will be taken as p tag -->

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

paragraph

<!-- Italics -->

_following text will be rendered as italics_

_following text will be rendered as italics_

<!-- strong/Bold -->

**this text looks bolder/strong**

**this text looks bolder/stro**

<!-- strike through -->

~~this text will be striked out~~

<!-- Horizontal ruler/seperator -->
  <!-- use - or _ 3 times -->

---

---

<!-- escape Charactor -->
  <!-- use \ -->

\*this text should be italisised but markdown charactor is escaped\*

<!-- Block Qoute -->

> This is how Block Qoute looks like

<!-- LInks -->
  <!-- syntax: [name of link to display](link "optional on hover name") -->

[check out this google link](https://google.com)

  <!-- to display custom text when hovered on link -->

[check out this google link](https://google.com "you hovered over me")

<!-- Unordered List -->
  <!-- use tab for nesting -->

- Unordered List Item 1
- Unordered List Item 2
- Unordered List Item 3
  - Unordered List Nested Item 1
  - Unordered List Nested Item 2

<!-- Ordered List -->
  <!-- using 1. for each item is allowed and is automatically converted to the next number -->

1. Ordered List Item 1
1. Ordered List Item 2
1. Ordered List Item 3

  <!-- or -->

1. Ordered List Item 1
2. Ordered List Item 2
3. Ordered List Item 3

<!-- Inline Code Block -->

`<p> this is how inline code block looks</p>`

<!-- Images -->
  <!-- Syntax is similar to url just add ! before [ -->
  <!-- styntax: ![name of image to display](imageUrl "optional on hover name") -->

![check this image](https://static.toiimg.com/thumb/msid-31346158,width-748,height-499,resizemode=4,imgsize-114461/.jpg "you hovered over me")

<!-- GitHub MArkdown -->
  <!-- code block -->

```
  npm i express

  npm start

  node app.js
```

  <!-- we can specify language of syntax -->

```javascript
function greet(name) {
  console.log(`hello ${name}`);
}

greet("world");
```

<!-- Tables -->

| Sno | names  | emails              |
| --- | ------ | ------------------- |
| 1   | akhil  | johndoe.1@gmail.com |
| 2   | chintu | johndoe.2@gmail.com |

<!-- Task List / check boxes -->

- [ ] This is a Unchecked box
- [x] This is a Checked box
