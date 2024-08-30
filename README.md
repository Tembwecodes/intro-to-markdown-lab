Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. **Basic syntax**

**const** functionName = (params) => {
  // code to be executed
}

const: const should be used whenever a function expression is assigned to a variable.
* **The function** name: The name you choose for the function.
* **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* **The arrow syntax**: Indicates that this will be a function.
* **The body**: The statements that make up the function itself. Surrounded by curly braces.

***Example***:

const greet = (name) => {
  console.log("Hello, " + name + "!");
}

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. **Calling a function**

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

***Example***:

greet('Alice'); // Outputs: Hello, Alice!

3. **Return values**

Functions can process data input and output a value using the *return* keyword.

***Example***: 

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

# h1
## h2
### h3
#### h4
##### h5
###### h6

This text is **bold**. This text is also __bold__.

This text is in *italics*. This text is also in _italics_.

This text is ***bold and italicized***. This text is also ___bold and italicized___.

const: ...
The function name: ...
Parameters: ...
The arrow syntax: ...
The body: ...

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2

Use the `console.log()` function to print values to the console.

```javascript
const printItem = (item) => {
  console.log(item);
}
```

const printItem = (item) => {
  console.log(item);
}
```Javascript
function myAnimals() => {
    const = num1 + num2
}
let num1 = 3;
let num2 = 6;
myAnimals();
```

 [Google](https://www.google.com)

This is [a reference][example].

[example]: http://www.example.com/


[google](https://developer.mozilla.org/en-US/)


> This is a blockquote.

> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.

![some alt text](www.url_to_an_image.com/image)

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

![Computer with Code](/modular-curriculum-all-courses/intro-to-markdown-lab/exercise/assets/james-harrison-unsplash.jpg)


![some alt text](www.url_to_an_image.com/image)

![some alt text](https://images.unsplash.com/photo-1505873242700-f289a29e1e0f?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8cmVhbCUyMGVzdGF0ZXxlbnwwfHwwfHx8MA%3D%3D)


![some alt text](./the-name-of-my-image.jpg)

![some alt text](\\wsl.localhost\Ubuntu\home\tembwes\code\ga\labs\intro-to-markdown-lab\aaron-huber-s95oB2n9jng-unsplash.jpg)

| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

This text has been ~~redacted~~. 


**PART 2: TUTORIAL HOW TO CREATE HTML BOILERPLATE**


**HTML Boilerplate**

When starting a new web project, setting up a solid foundation is important. 

**WHAT IS AN HTML BOILERPLATE**

An HTML boilerplate is a template that is used at the beginning of the web project. This boilerplate should be added to all of the HTML pages. The primary goal is to save time and ensure consistency by providing a robust template that follows industry standards.

**IMPORTANCE OF USING THE HTML BOILERPLATE**

Using an HTML boilerplate has several benefits:

1. **Efficiency**: Quickly set up new projects without rewriting the same basic structure each time.
2. **Consistency**: Maintain a consistent structure and style across multiple projects.
3. **Best Practices**: Follow industry standards and best practices out of the box.
4. **Cross-browser Compatibility**: Ensure your site works well across different browsers and devices.


**Essential Elements of an HTML Boilerplate**

* Doctype declaration
* HTML tag and Language attribute
* Head section
* meta tags
* title tags
* Body section

**HTML5 Boilerplate example**
```html 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
<!-- Your content goes here -->
</body>
</html>
```

* **DOCTYPE in HTML**

Doctype HTML is a declaration that informs the browser of the HTML version in which the document is written. In an HTML file, this declaration appears as the first line.
Every HTML document must begin with a `<!DOCTYPE>` declaration.

The declaration does not contain an HTML tag. It is “information” to the browser about the type of document to expect.
The declaration in HTML5 is straightforward
`<!DOCTYPE html>`

* **HTML element**

The `<html>` element is the top-level element of an HTML document, and is referred to as the root element.
Here you will nest the `<head>` and `<body>` tags inside of it.
```html 
<html lang="en">
    <head></head>
    <body></body>
</html>
```
The *lang* attribute specifies the language of the element’s content. Always use a language attribute on the html tag to declare the default language of the text in the page. This is inherited by all other elements.


* **head tags in HTML**

The `<head>` element, which is positioned between the `<html>` and `<body>` tags, is a container for metadata (info about data). Metadata is information about an HTML document. Metadata is not shown. The document title, character set, styles, scripts, and other meta information are often defined via metadata.

* **UTF-8 character encoding**
The UTF-8 character encoding system. It allows you to display characters as ASCII text while still supporting international characters like Chinese characters.
```html
<meta charset="UTF-8">
```

* **X-UA-Compatible mean**
X-UA-Compatible is a document mode meta tag that allows web authors to choose what version of Internet Explorer the page should be rendered as. It is used by Internet Explorer 8 to specify whether a page should be rendered as IE 7 (compatibility view) or IE 8 (standards view). “IE=7” “IE=EmulateIE8” “IE=8”

In the example below, it supports the latest browser “IE=edge”. This is the highest supported document mode of the browser.
```html 
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

* **viewport meta tag in HTML**
The viewport is the visible area of a web page to the user. It varies depending on the device; on a mobile phone, it will be smaller than on a computer screen. This provides guidance to the browser on how to control the page’s scale and dimensions.

You should include the following `<meta>` element in all your web pages:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0"
```
The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

* **HTML title tags**

The title of the web page is specified by the `<title>` tag. This text appears in the title bar of the browser.

* **body tags in HTML**

The body of the document is defined by the `<body>` tag. The `<body>` element holds all of an HTML document’s contents, such as headings, paragraphs, graphics, hyperlinks, tables, lists, and so on.

**ADDING A BOILERPLATE IN VSCODE**

> To create an instant HTML boilerplate in VSCode create an empty index.html document.
Type the following into your text editor and then hit tab to see the results.
```html
!
```
Should reveal the following code:
![html code](https://learningmonkey.in/wp-content/uploads/2022/03/HTML-Document-Structure-and-HTML-Boilerplate-code-2-1024x416.png)


**Conclusion**

An HTML boilerplate is an essential tool for any web developer. It provides a standardized foundation that ensures your projects are built on best practices and are compatible across different browsers. By using a boilerplate, you save time, maintain consistency, and ensure a professional starting point for all your web development projects.



**TUTORIAL FOR MARKDOWN**

**How to Design a Logo: A Step-by-Step Guide**

Creating a perfect logo for your company involves a lot of decisions, namely: colors, layouts, fonts, and symbols. But learning how to design a logo doesn’t have to be hard – and you don’t need to be a designer!

Here we have the five beginner-friendly steps:
* Research your brand
* Learn about logo design
* Make a logo
* Test and finalise

**What is a logo?**

The term *logo* is often used as a catchall to define any emblem a company uses to visually represent its brand. Your logo isn’t your brand, visual identity, or an indicator of success. It’s simply the first step to creating your visual identity!

> “A brand is not a static logo. It’s the emotional and collective space your organization holds within your audience’s mind. The logo is a spoke in a larger wheel. It acts as a springboard to a larger brand story and experience.”  – Sunny Bonnell, Founder + Chief Vision Officer at Motto.

1. **Researching your brand identity**

To make your logo successful and long-lasting, you’ll need to set a solid foundation. And to set a solid foundation, you need to do your research.

Creating a strong brand identity helps your company gain credibility and become recognizable as you grow. Before you dive into your logo design, take some time to think through these questions:
> Who’s my ideal customer?

> What brands do they like?


Research your competitors and create a moodboard of all their logos to familiarize yourself with the colors, symbols, fonts, and layouts they use. This will help you understand how to stand out visually, while still associating with your industry.
> “The best branding connects to the most specific target market possible — not everyone. A highly focused visual directed at that target will connect the brand to the audience. Focus on who you’re attracting.” – Kyle Golding, CEO & Chief Strategic Idealist, The Golding Group.

2. **Learn about logo design**

**What makes a good logo?**

Though the quality of a logo is subjective, there are certain elements that make a logo either good or bad.

A good logo is:
* simple
* Memorable
* Unique
* Versatile
* Adorable
* Relevant

> “A logo is “great” when it works. Those characteristics are memorable, recognizable, and functional to the project. ” – Pierpaolo Chiaravalloti, Head of Branding at Desircle.

**THREE TYPES OF LOGOS**

Logo design can be broadly put into two categories: logos that only consist of text (denoting the name or initials of a company) and those containing both text and a symbol.

Here’s a breakdown of the three most common types of logos — there are a few more, but we want to keep it simple!

Wordmark logo

![wordmark logo](https://miro.medium.com/max/4106/1*zGKuH1pIC-kjVxlS-opKrg.png)

Monogram logo

![monogram logo](https://th.bing.com/th/id/OIP.Hp7xQ_NNNwEETvlXglCnJgHaHa?rs=1&pid=ImgDetMain)

Combination logo

![combination logo](https://www.webcodersinc.com/public/images/logo-design-portfolio/combination-design/1.png)

3. **Get color, font, and symbol ideas**

**COLOR**:
Choosing a color for your logo design isn’t just about picking what looks good to you. Think about how your audience will perceive it and where it will be displayed. Your logo colors will be your brand colors, so imagine how they’ll look on all of your business assets

> “Color is one of the most identifiable components of a visual identity, so if no competitors are using a specific color it allows you to stand out from the crowd with little effort.”– Ian Paget, Founder, Logo Geek.

Pay attention to the colors your competitors use, you’ll want to stay with colors familiar to your industry but differentiate from the competition at the same time.

Warm colors
![warm colors](https://th.bing.com/th/id/OIP.YPEonMGzzSGZxUr5e7JgzwHaEc?rs=1&pid=ImgDetMain)


Cold colors
![cold colors](https://th.bing.com/th/id/OIP.W4SZTCupt1QlIt1un_uf2gHaFB?rs=1&pid=ImgDetMain)

Serene vibe
![serene colors](https://th.bing.com/th/id/R.98d7a5e73161a20bb340d0b4f954baf3?rik=YldaXYbUaOy8Gw&riu=http%3a%2f%2fwww.color-hex.com%2fpalettes%2f27748.png&ehk=KzaqkiWqe9dWKVIUWUWpehs1OLvRtOHPAKmeo%2ba8%2fx4%3d&risl=&pid=ImgRaw&r=0)


Elegant vibe
![elegent colors](https://assets-global.website-files.com/6009ec8cda7f305645c9d91b/646ce8cf5dcb2db9ac6a6a25_b0002bc1.png)

**FONT**: With thousands of fonts to choose from, picking one for your logo isn’t an easy task. Each font conveys something different and should fit with your brand attributes and identity.

> “If I could provide a single most important tip in designing a logo, it would be to avoid common typefaces. Unique typography in logo design is the simplest way to look professional.” – Erik Pitzer, Graphic Designer, Illumine8 Marketing & PR.

***Serif fonts***, Fonts that have little “feet” on the edges are referred to as serif fonts. They’re timeless, high-end, classic fonts associated with tradition and propriety. The most well-known serif font is Times New Roman. Because of its timelessness, it’s often used to attract a more mature demographic.

***Sans-serif fonts***,
These fonts don’t have the little feet like serif fonts do, so they tend to have a more clean and modern look. They’re easy to read and work well across mediums.

***Script fonts***,
Handwritten and script fonts add tons of personality to a logo, and tend to look formal, elegant, and feminine. This is one of the harder styles to pull off because script fonts are harder to read at a glance — but when done right, they can make your logo distinctive and iconic.

***Modern fonts***,
Modern fonts are sans-serif fonts that hold a certain sophistication and starkness. This makes them most effective with younger demographics — and popular among app and tech companies.

***Display fonts***,
Display fonts tend to be a broad category of out-of-the-ordinary fonts that add major visual impact. They can be bubbly and fun, or edgy and futuristic — but beware of using ones that are super trendy or that don’t match your brand personality.

***Handwritten fonts***,
As the name suggests, handwritten fonts mimic the appearance of handwritten text. They’re based on real hand lettering and have an organic, imperfect, and personal feel. 

These fonts often evoke a sense of creativity, personalization, and informality. They can bring a human touch to digital designs, making them ideal for conveying emotions and establishing a more personal connection with the audience.

4. **Design a logo**

* **Design your own logo from scratch**

If you’ve already got some design experience, and have access to software like Adobe Illustrator or Photoshop, then designing your own logo from scratch is an option.

* **Buy a logo template and customize it**

Another option is to go with a template. There are a few companies and sites that offer free or paid logo templates that you can customize by making edits to the company name, colors, and more.

* **Use an online logo maker**

If you want a unique custom logo, but don’t have the design experience or time to do it yourself, using an online logo maker is probably your best bet. Instead of working with a template, these tools allow you to create your own designs with a much more intuitive and smart design platform.

* **Test and finalize**

Once you’ve designed your own logo (or a few!), it’s time to do some stress testing. Here are a few questions you should address before finalizing your business’ new logo design.

0.1. **check Is my logo scalable?**

Having a scalable logo means you can display it anywhere and everywhere your heart desires (well, pretty much anywhere). Want to put it on a huge billboard? How about on your business cards?

When you’ve got a scalable logo, wherever you decide to put it, it will look clean and crisp (not pixelated) and will remain easy to read and identify. Check that your logo works at both large and small sizes and remains readable.

> Ensure your logo is a vector of the highest resolution quality and is able to scale and be easily identifiable and memorable.”– Christine Lieu, Founder at CL Designs.

0.2. **Does my logo look good in all black or all white?**

Having an all-black and all-white version of your logo with a transparent background is essential. Why? Because it allows your logo to be more versatile and work in various visual environments.

When the background of your logo is transparent, it gives you the power to place your logo over any colored background, including images and videos!

0.3. **Do I have brand guidelines?**

Lastly, after you finalize a design, you’ll want to create brand guidelines. Brand guidelines are a set of rules about how to represent your brand across channels and assets, helping your business build credibility and recognition as you grow. Brand guidelines should include:

* A cover page

* Logo guidelines

* Color palettes

* Typography

*Usage examples

They can also include a mission statement, visual rules around images and icons, brand voice guidelines, and specifications for assets like packaging, email marketing, and more.