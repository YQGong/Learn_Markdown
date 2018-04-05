# Learn_Markdown
```
* easy-to-read
* easy-to-write
* writing for the web
```
* easy-to-read
* easy-to-write
* writing for the web

## example 1 HTML table
```
This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.
```
This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.

##  emphasis

```
*emphasis*

_emphasis_

__emphasis__

**emphasis**
```
*emphasis*

_emphasis_

__emphasis__

**emphasis**

```
<span>test</span>
test

<cite>test</cite>
test

<del>test</del>
test
```
<span>test</span>
test

<cite>test</cite>
test

<del>test</del>
test
## escaping from special characters

* md

    < &
* html

    &lt; &amp; &copy; AT&T

&lt; &amp; &copy;

## paragraph

paragraph1  
paragraph1 with a &lt;br />


## headers
```
This is an H1
=
This is an H2
-

# H1
## H2
### H3
#### H4
##### H5
main paragraph
```
This is an H1
=
This is an H2
-

# H1
## H2
### H3
#### H4
##### H5
main paragraph

## quotes
```
> this is a quote garagraph
> 
> next  
> using a br 
```
> this is a quote garagraph
> 
> next  
> using a br 

```
> this is a quote garagraph  
 with a lazy style
```
> this is a quote garagraph  
 with a lazy style

 and
```
> # header1
> ## header2
> ### header3
> #### header4
> ##### header5

> nested quote
> > level 2
> > > level 3  

> ......
```
> # header1
> ## header2
> ### header3
> #### header4
> ##### header5

> nested quote
> > level 2
> > > level 3  

> ......

## Lists
```
* one
* two
* three

+ 1
+ 2
+ 3

- 1
- 2
- 3

1. one
2. two
3. three
```
* one
* two
* three

+ 1
+ 2
+ 3

- 1
- 2
- 3

1. one
2. two
3. three
```
* lazy
input
of
a
long
line

    or two paragraphs
with long long content
```
* lazy
input
of
a
long
line

    or two paragraphs
with long long content

```
* list item
> Quotes in an item


* list item

        codes in an item here
* list item
> Quotes in an item
```

* list item

        codes in an item here

* list item
> Quotes in an item

## code block

```
    code block
```
    code block

other code blocks
```
`
code blocks
`
``
code blocks
``
\`\`\`
code blocks
\`\`\`
```
`
code blocks
`
``
code blocks
``
```
code blocks
```

## horizontal lines
```
 * * *
 ***
 *******
 - - -
 ---------
```
 * * *
 ***
 *******
 - - -
 ---------

## links
```
[example](https://www.baidu.com "title")

[about](~/.bashrc)

[reference][id]

[id]:test "mytest"
```
[example](https://www.baidu.com "title")

[about](~/.bashrc)

[reference][id]

[id]:test "mytest"

### neat example:
```
I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
```
```
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
```

## images
```
![Alt text](/path/to/img.jpg "Optional title")
```
![Alt text](/path/to/img.jpg "Optional title")

## urls

```
<http://example.com/>
```
<http://example.com/>

