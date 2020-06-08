# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [TRUE] `<div><span>hello</div></span>`

b) [FALSE]

```html
<ul>
<li>one</li>
</ol>
```

c) [FALSE] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

Screenreaders are software that support those with disiabilities to view webpages in an alternative way. They read the content of the page according to the way the code is written and regurgitate the content to the user.

There is a large population with visual impairments and it is moral (and legal) to provide this population with accessibility options.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

img

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

ul OR ol
li
a

c) You want to sell designer hats. You need to receive orders from the user.

form
input

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No - buttons' descendants/children are not clickable. This is because the original button will always be the primary and only clickable element.

## Q5 - What is the most generic tag you can use?

div

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list

e) `tr` table row

f) `th` table header

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements? 

tr

## Q8 - What is the difference between td and th?

1. th is meant to be the header, meaning it will have different default font styling
2. td is meant to be generic data within the table
3. it will be clearer to stylize headers and data if they are split up

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?

When the tag itself has no content, but rather refers to something else, e.g. img or source

## Q11 - What is autofilling and why is it important?

Autofilling shows options/text that the user has used previously. This speeds up the process of entering in information or selections. It's always better to make pages function more efficiently, and this is one of those ways.

## Q12 - Which attributes are always present in an img element?

src, which is the image source
alt, which is the alternative text that displays if the image does not load, or upon hover of image

## Q13 - Which attribute is always present for an anchor tag?

href, which is the destination address
