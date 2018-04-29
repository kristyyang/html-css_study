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
  - [Relative link type](#relative-link-type)
  - [Email Links](#email-links)

- Images
  - [Adding Images](#adding-images)

- Table
  - [Basic table structure](#basic-table-structure)
  - [Table Headings](#table-headings)
  - [Spanning columns](#spanning-columns)
  - [Spanning Rows](#spanning-rows)

- Form

### Lists

----------

#### Ordered Lists

```html
<ol>
   <li>First element</li>
   <li>Second element</li>
   <li>Third element</li>
   <li>Fourth element</li>
</ol>
```

```html
<ol>: The ordered Lists
<li>: Each item placed between an opening<li> tag
```

#### Unordered Lists

``` html
<ul>
  <li>Second element</li>
  <li>First element</li>
  <li>Third element</li>
</ul>
```

```html
<ul> The unordered list is created with <ul>elements
```

#### Definition Lists

```html
<dl>
  <dt>Definition</dt>
  <dd>A definition is a statement of the meaning of a term. Definitions can be classified into two large categories, intensional definitions and extensional definitions</dd>
</dl>
```

```html
<dl> The dinition list
<dt> This is used to contain the term being definted
<dd> This is used to contain the definition.
```

#### Nested Lists

```html
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

```html
<li> you can put a second list inside an <li> element to creat a sub-list
```

### Links

----------

#### Linking to other sites

```html
<p> Download lists:
   <ul>
     <li><a href="https://www.javascript.com/">javascript</a></li>
     <li><a href="https://nodejs.org/en/">nodejs</a></li>
     <li><a href="https://www.ruby-lang.org/en/">ruby</a></li>
   </ul>
</p>
```

#### Linking to other pages on the same sites

```html
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

```html
<p>
   <ul>
     <li><a href="reviews.html">reviews</a></li>
   </ul>
</p>
```

##### Child Folder

```html
<p>
  <ul>
     <li><a href="music/listings.html">listings</a></li>
  </ul>
</p>
```

##### Parent Folder

```html
<p>
   <ul>
      <li><a href="../index.html">Home</a></li>
   </ul>
</p>
```

##### Grandparent Folder

```html
<p>
   <ul>
      <li><a href="../../index.html">Home</a></li>
   </ul>
</p>
```

#### Email Links

```html
<p>
   <ul>
   <li><a href="html_css@example.org">Email</a></li>
   </ul>
</p>
```

### Images

-------

#### Adding Images

```html
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

```html
<table>
   <tr>
       <td>11</td>
       <td>12</td>
       <td>13</td>
   </tr>
   <tr>
      <td>21</td>
      <td>22</td>
      <td>23</td>
    </tr>
    <tr>
      <td>31</td>
      <td>32</td>
      <td>33</td>
    </tr>
</Table>
```
[Demo](https://jsbin.com/keceqofuno/edit?html,output)

- table : creat table
- tr : elements
- td : features

#### Table Headings

```html
<table>
   <tr>
    <th></th>
      <th scope="col">Attri 1</th>
    <th scope="col">Attri 2</th>
   </tr>
   <tr>
    <th scope="row">Ele 1: </th>
     <td>1</td>
     <td>2</td>
   </tr>
   <tr>
    <th scope="row">Ele 2: </th>
     <td>3</td>
     <td>4</td>
   </tr>
</table>
```

[Demo](https://jsbin.com/keceqofuno/edit?html,output)

- th: represent the empty cell, Headings

#### Spanning columns

```html
<table>
   <tr>
    <th></th>
    <th>9am</th>
    <th>10am</th>
    <th>11am</th>
    <th>12pm</th>
   </tr>
   <tr>
    <th>Monday</th>
    <th colspan="2">Math</th>
    <th>CPSC</th>
    <th>English</th>
   </tr>
   <tr>
     <th>Tuesday</th>
     <th colspan="3">French</th>
     <th>Chemistry</th>
   </tr>
</table>
```

[Demo](https://jsbin.com/keceqofuno/edit?html,output)

#### Spanning Rows

```html
<table>
   <tr>
    <th></th>
    <th>9am</th>
    <th>10am</th>
    <th>11am</th>
   </tr>
   <tr>
    <th>Monday</th>
    <th rowspan="2">Math</th>
    <th>CPSC</th>
    <th>English</th>
   </tr>
   <tr>
     <th>Tuesday</th>
     <th>French</th>
     <th>Chemistry</th>
   </tr>
</table>
```

[Demo](https://jsbin.com/keceqofuno/edit?html,output)

- rowspan : row Spanning
- colspan : column Spanning

### Form

--------

#### Form structure

##### Password input

```html
<form action="http://www.example.com/login.php">
 <p>Usename:
    <input type="text" name="usename" size="15" maxlength="30">
 </p>
 <p>Password:
   <input type="password" name="password" size="15" maxlength="30">
 </p>
</form>
```

[Demo](https://jsbin.com/wokakufome/edit?html,output)

- type = "text" : data type as text input
- name : name attributes
- size/maxlength : size and maxlength attributes

##### Text area

```html
<form action="http://www.example.com/comments.php">
 <p>What do you see yourself in the upcoming ten years? </p>
 <textarea name="comments" cols="20" rows="4">Entering your comments...</textarea>
</form>
```

[Demo](https://jsbin.com/keceqofuno/edit?html,output)

- textarea: used a multu-line text input.

##### Checkbox

```html
<form action="http://www.example.com/profile.php">
  <p>Please select your favorite coffee drink:
    <br />
    <input type="checkbox" name="service" value="black" checked="checked" /> Black
    <input type="checkbox" name="service" value="Latte"  /> Latte
    <input type="checkbox" name="service" value="Mocha"  /> Mocha
  </p>
</form>
```

[Demo](https://jsbin.com/keceqofuno/edit?html,output)

- type = "radio" : pick just one of a number of options.
- type = "checkbox" : select more than one options.
- name : indicates the value that is sent to the server for selected options
- checked : can be used to indicate which value should be selected when the page loads

##### Drop Down List Box

```html
<form action="http://www.example.com/profile.php">
 <p> What programming language do you use to do project?</p>
 <select name="language">
   <option value="javascript">javascript</option>
   <option value="Ruby">Ruby</option>
   <option value="nodejs">NodeJs</option>
 </select>
</form>
```

[Demo](https://jsbin.com/weqinepidu/1)

- select : drop down list Box, allows users to select one option.
- name : name of the form
- option : specify the options that the user can select from
  - value : option name

##### Multiple select Box

```html
<form action="http://www.example.com/profile.php">
  <p>What programming language you usually use? (You can select more than one option by holding down control on a PC or command key on a Mac while selecting different options.)</p>
  <select name="language" size="3" multiple="multiple">
  <option value="javascript" selected="selected">javascript</option>
  <option value="Ruby" selected="selected">Ruby</option>
  <option value="NodeJs" selected="selected">NodeJs</option>
  </select>
</form>
```

[Demo](https://output.jsbin.com/wuhonavezo)

- multiple: select multiple options

###### File input Box

```html
<form action="http://www.example.com/upload.php" method="post">
 <p>upload your sone in MP3 format</p>
 <input type="file" name ="user-song" /><br />
 <input type="submit" value="Upload" />
</form>
```

[Demo](https://jsbin.com/tayufodahu)

- input: allow users to upload a file
- type = file : creates a box that look like a text input followed by Browse
- type = submit : the submit button is used to sent a form to the server.
- value : text appears in the button

###### Image button

```html
<form action ="http://www.example.org/sunscribe.php">
  <p>Subscribe to our email lists</p>
  <input type="text" name="email" />
  <input type="image" src="images/subscribe.jpg" width="10" height="20" />
</form>
```

[Demo](https://jsbin.com/dexicafodo)

###### Labelling form controls

```html
<label>Age: <input type="text" name="age" /></label>
<br/ >
Gender:
<input id="female" type="radio" name="gender" value="f">
<label for="female">Female</label>
<input id="male" type="radio" name="gender" value="m">
<label for="male">Male</label>
```

- Label: both the text description and form input.
- Separate from the form control and use for form control.

###### Grouping form elements

```html
<fieldset>
  <legend>Contect details</legend>
  <label>Email: <br />
  <input type="text" name="email" /></label ><br />
  <label>Mobile: <br />
  <input type="text" name="mobile" /></label><br />
  <label>Telephone: <br />
  <input type="text" name="telephone" /></label>
</fieldset>
```

[Demo](https://jsbin.com/pevujicove)

- fieldset : related form controls
- legend : identity purpose of Grouping

###### Form Validation

```html

```