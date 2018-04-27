# HTML && CSS

## Table of the content

- Lists
  - [Numbered Lists](#lists)
    - [Ordered Lists](#ordered-lists)
    - [Unordered Lists](#unordered-lises)
  - [Definition lists](#definition-lists)

- Links
  - Creating links
  -

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

#### Unordered lists

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
