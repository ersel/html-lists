# Welcome to HTML5 Lists.

In this section we will learn about the types of Lists in HTML, why we would use them and when?

There are usually 2 types of Lists in HTML.
___

### Ordered Lists

An <b>Ordered List </b>typically looks like this:

<ol>
  <li>List item one</li>
  <li>List item two</li>
  <li>List item three</li>
</ol>

Notice how the list item's are numbered? Hence the name <b>Ordered List</b>
This is created in HTML with the  &#60;ol&#62; and &#60;li&#62;  tags.

The &#60;li&#62; tag is the "List Item" tag. These tag's go together to make the <b>Ordered List </b>.

Here is what the HTML should look like:

&#60;ol&#62;
<br>
&#60;li&#62;List item one&#60;/li&#62;
<br>
&#60;li&#62;List item two&#60;/li&#62;
<br>
&#60;li&#62;List item three&#60;/li&#62;
<br>
&#60;/ol&#62;

___

### Un-Ordered Lists

An <b>Un-Ordered List </b>typically looks like this:

<ul>
  <li>List item</li>
  <li>List item</li>
  <li>List item</li>
</ul>

Notice how the list item's are not numbered this time? Hence the name <b>Un-Ordered List</b>
This is created in HTML with the  &#60;ul&#62; and &#60;li&#62;  tags.

The &#60;li&#62; tag is the "List Item" tag. These tag's go together to make the <b>Un-Ordered List </b>.

Here is what the HTML should look like:

&#60;ul&#62;
<br>
&#60;li&#62;List item&#60;/li&#62;
<br>
&#60;li&#62;List item&#60;/li&#62;
<br>
&#60;li&#62;List item&#60;/li&#62;
<br>
&#60;/ul&#62;

___

### Nested Lists

An <b> Nested Un-Ordered List </b>typically looks like this:

<ul>
  <li>List item 1</li>
    <ul>
      <li>List item 1a</li>
      <li>List item 1b</li>
      <li>List item 1c</li>
    </ul>
  <li>List item 2</li>
  <li>List item 3</li>
</ul>

Notice how the list item's are now nested this time? Hence the name <b>Nested Un-Ordered List</b>
This is created in HTML with the  &#60;ul&#62; and  &#60;li&#62; tags.

The &#60;li&#62; tag is the "List Item" tag. These tag's go together to make the <b>Un-Ordered List </b>.

Here is what the HTML should look like:

&#60;ul&#62;
<br>
&#60;li&#62;List item&#60;/li&#62;
<br>
&#60;ul&#62;
<br>
&#60;li&#62;List item 1a&#60;/li&#62;
<br>
&#60;li&#62;List item 1b&#60;/li&#62;
<br>
&#60;li&#62;List item 1c&#60;/li&#62;
<br>
&#60;ul&#62;
<br>
&#60;li&#62;List item&#60;/li&#62;
<br>
&#60;li&#62;List item&#60;/li&#62;
<br>
&#60;/ul&#62;
