
# HTML Cheat Sheet For Beginners Written By CodeXam
I am **Subham Maity**
I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.
## Help us improve this guide - **Fork, Pull Requests, Shares and Likes are recommended**!

## **HTML Cheatsheets Chapters**

* [Structure](#structure)
* [Headings](#headings)
* [Container](#container)
* [Text Formatting](#text-formatting)
* [Lists](#lists)
* [Media](#media)
* [Table](#table)
* [Links](#links)
* [Form](#form)
* [Characters & Symbols](#characters-and-symbols)
* [Random Text](#random-text)
* [Semantic Elements](#semantic-elements)





### **Structure**

This is the basic template or barebone structure of HTML.


#### **Boilerplate**


```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <!-- Body -->
</body>
</html>
```



### **Headings**

There are six headings available in HTML, H1 is the largest among all, and H6 is the smallest.


#### **&lt;h1> Tag**


```
<h1>Heading 1</h1>
```



#### **&lt;h2> Tag**


```
<h2>Heading 2</h2>
```



#### **&lt;h3> Tag**


```
<h3>Heading 3</h3>
```



#### **h4 Tag**


```
<h4>Heading 4</h4>
```



#### **h5 Tag**


```
<h5>Heading 5</h5>
```



#### **h6 Tag**


```
<h6>Heading 6</h6>
```



### **Container**

Container tags are the tags that contain some data such as text, image, etc. There are several container tags in HTML.


#### **div tag**

div tag or division tag is used to make blocks or divisions in the document.


```
<div> This is div block </div>
```



#### **span tag**

span is a container for inline content


```
<span> This is span block </span>
```



#### **p tag**

Paragraph


```
<p> This is a paragraph </p>
```



#### **pre tag**

pre tag represents pre-formatted text


```
<pre> Hello World </pre>
```



#### **code tag**

code tag is used to represent source codes


```
<code>
import python
</code>
```



### **Text Formatting**

Text formatting tags are used to format text or data of HTML documents. You can do certain things like creating italic, bold, strong text to make your document look more attractive and understandable.


#### **&lt;b> tag**


```
<b>I'm bold text</b>
```



#### **&lt;strong> tag**


```
<strong>I'm important text</strong>
```



#### **&lt;i> tag**


```
<i>I'm italic text</i>
```



#### **&lt;em> tag**


```
<em>Emphasized text</em>
```



#### **&lt;sub> tag**


```
<sub>Subscript</sub>
```



#### **&lt;sup> tag**


```
<sup>Superscript</sup>
```



### **Lists**

Lists can be either numerical, alphabetic, bullet, or other symbols. You can specify list type and list items in HTML for the clean document.


#### **&lt;ol> tag**

Ordered list starts with &lt;ol> tag and each list item starts with &lt;li> tag


```
<ol>
    <li>Data 1</li>
    <li>Data 2</li>
    <li>Data 3</li>
</ol>
```



#### **&lt;ul> tag**


```
<ul>
    <li>Your Data</li>
    <li>Your Data</li>
</ul>
```



### **Media**

Media is anything that is present in digital form such as image, video, audio, etc.


#### **&lt;audio> tag**

It is used to embed sound content in the document.


```
<audio controls>
    <source src="demo.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```



#### **&lt;img> tag**

It is used to embed or import image in a webpage.


```
<img src="Source_of_image" alt="Alternate text">
```



#### **&lt;video> tag**

It is used to embed video in the webpage.


```
<video width="480" height="320" controls>
    <source src="demo_move.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```



### **Table**

A table is a collection of rows and columns. It is used to represent data in tabular form.


#### **Table Structure**


```
<table>
    <caption>Demo Table</caption>
    <thead>
        <tr>
            <th>Column1</th>
            <th colspan="2">Column2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data1</td>
            <td>Data2</td>
            <td>Data2</td>
        </tr>
        <tr>
            <td>Data1</td>
            <td>Data2</td>
            <td>Data2</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>&nbsp;</td>
            <td>Data</td>
            <td>Data</td>
        </tr>
    </tfoot>
</table>
```



### **Links**

Links are clickable text that can redirect you to some other page.


#### **&lt;a> tag**

&lt;a> or anchor tag defines a hyperlink.


```
<a href="https://www.codewithcodexam.com/">Visit CodeWithcodexam.com!</a>
```



### **Form**


#### **Sample Form**

Form is used to collect user's input, generally user's data is sent to server for further processing.


```
<form action="/action.php" method="post">
    Name: <input name="name" type="text" /> <br />
    Age: <input max="90" min="1" name="age" step="1" type="number" value="18" /> <br />
    <select name="gender">
        <option selected="selected" value="male">Male</option>
        <option value="female">Female</option>
    </select><br />
    <input checked="checked" name="newsletter" type="radio" value="daily" /> Daily <input name="newsletter" type="radio"
        value="weekly" /> Weekly<br />
    <textarea cols="20" name="comments" rows="5">Comment</textarea><br />
    <label><input name="terms" type="checkbox" value="tandc" />Accept terms</label> <br />
    <input type="submit" value="Submit" />
</form>
```



### **Characters and Symbols**

Some symbols are not directly present on the keyboard, but there are some ways to use them in HTML documents. We can display them either by entity name, decimal, or hexadecimal value.


#### **right Symbol (©)**


```
&;
```



#### **Less than (&lt;)**


```
&lt
```



#### **Greater than (>)**


```
&gt;
```



#### **Ampersand (&)**


```
&amp;
```



#### **Dollar ($)**


```
&dollar;
```



### **Random Text**


#### **Elon Musk**


```
Elon Reeve Musk FRS is an entrepreneur and business magnate. He is the founder, CEO, and Chief Engineer at SpaceX; early stage investor, CEO, and Product Architect of Tesla, Inc.; founder of The Boring Company; and co-founder of Neuralink and OpenAI. A centibillionaire, Musk is one of the richest people in the world.
```



### **Semantic Elements**

Semantic elements are those elements that are self describable, i.e., from their name itself, you can understand their meaning.


#### **&lt;section> tag**

It defines a section in the document


```
<section>This is a section</section>
```



#### **&lt;article> tag**

It represents self-contained content


```
<article> Enter your data here </article>
```



#### **&lt;aside> tag**

It is used to place content in the sidebar


```
<aside> Your data </aside>
