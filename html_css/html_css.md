# HTML && CSS

## Table of the content

- Lists
  - [Numbered Lists](#lists)
    - [Ordered Lists](#ordered-lists)
    - [Unordered Lists](#unordered-lists)
  - [Definition lists](#definition-lists)

- Links
  - [Linking to other sites](#linking-to-other-sites)
  - [Linking to other pages on the same sites](#linking-to-other-pages-on-the-same-sites)
  - Email Links

- Images
  - Adding Images

- Table
  - Basic table structure



### Lists

----------

#### Ordered Lists

```bash
<ol>
   <li>First element</li>
   <li>Second element</li>
   <li>Third element</li>
   <li>Fourth element</li>
</ol>
```

```bash
<ol>: The ordered Lists
<li>: Each item placed between an opening<li> tag
```

#### Unordered Lists

``` bash
<ul>
  <li>Second element</li>
  <li>First element</li>
  <li>Third element</li>
</ul>
```

```bash
<ul> The unordered list is created with <ul>elements
```

#### Definition Lists

```bash
<dl>
  <dt>Definition</dt>
  <dd>A definition is a statement of the meaning of a term. Definitions can be classified into two large categories, intensional definitions and extensional definitions</dd>
</dl>
```

```bash
<dl> The dinition list
<dt> This is used to contain the term being definted
<dd> This is used to contain the definition.
```

#### Nested Lists

```bash
<ul>
  <li>Coffee</li>
  <li>Juice
  <ul>
     <li>Apple</li>
     <li>Orange</li>
     <li>Kiwi</li>
     <li>Watermelon</li>
  </ul>
  </li>
</ul>
```

```bash
<li> you can put a second list inside an <li> element to creat a sub-list
```

### Links

----------

#### Linking to other sites

```bash
<p> Download lists:
   <ul>
     <li><a href="https://www.javascript.com/">javascript</a></li>
     <li><a href="https://nodejs.org/en/">nodejs</a></li>
     <li><a href="https://www.ruby-lang.org/en/">ruby</a></li>
   </ul>
</p>
```

#### Linking to other pages on the same sites

```bash
<p>
  <ul>
   <li><a href="index.html">name</a></li>
   <li><a href="age.html">age</a></li>
   <li><a href="gender.html">gender</a></li>
  </ul>
</p>
```

#### Relative link type

##### Same Folder

```bash
<p>
   <ul>
     <li><a href="reviews.html">reviews</a></li>
   </ul>
</p>
```

##### Child Folder

```bash
<p>
  <ul>
     <li><a href="music/listings.html">listings</a></li>
  </ul>
</p>
```

##### Parent Folder

```bash
<p>
   <ul>
      <li><a href="../index.html">Home</a></li>
   </ul>
</p>
```

##### Grandparent Folder

```bash
<p>
   <ul>
      <li><a href="../../index.html">Home</a></li>
   </ul>
</p>
```

#### Email Links

```bash
<p>
   <ul>
   <li><a href="html_css@example.org">Email</a></li>
   </ul>
</p>
```

### Images

-------

#### Adding Images

```bash
<img src="images/quokka.jpg"
alt="A family of quokka"
tittle="The quokka is an Australian marsupial that is similar in size to the domestic cat." width="600" height="450" />
```

- img : add image into the pages
- src : source of the picture
- alt : text description
- title: additional informaiton
- width: width of the pixels
- height: height of the image in pixels

### Table

------------

#### Basic table structure
