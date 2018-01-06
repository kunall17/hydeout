---
layout: post
title: Text Builder
comments: true
categories: project
excerpt_separator: <!--more-->
---

Makes the work of a software developer easier. This application saves a lot of time. We are inspired by the workflow of emmet plugin of atom or sublime text. It helps in working smart rather than working hard.

<!--more-->

This application can be used by developers as well as people who do the job of data entry. Also, it is possible that it might be used anywhere else according to their requirements and large data sets.

**Description**

This application lets you generate repeated text.

E.g. we will create custom key bindings using the following code:

```
<Button android:text=”W”’
‘android:id=”@+id/W”’
‘android:onClick=”keyBtn_Click”’
‘android:layout_weight=”1”’
‘android:layout_width=”0dp”’
```
On adding placeholders -

```
<Button android:text=”placeholder1”’
‘android:id=”@+id/placeholder2”’
‘android:onClick=”keyBtn_Click”’
‘android:layout_weight=”1”’
‘android:layout_width=”0dp”’
‘android:layout_height=”wrap_content” />

```
This code has to be repeated for every letter we want to bind. Instead of copying and pasting the code and changing each letter. Auto Text Generator will generate the code for me. As we see android:text=&quot;W&quot; and android:id=&quot;@+id/W&quot; are two variable so we add two placeholders in their place and write the text in the lists. And in some seconds we will be able to generate a whole keyboard. There will be option to fill alphabets, numbers and files. Another example is suppose we are making a gallery in HTML so we have to make code of &lt;img src=&quot;filename&quot;&gt; so we can select many files and this application will create the code automatically.

After we complete making the application, **we will create a plugin of this.**


https://github.com/kunall17/textBuilder
