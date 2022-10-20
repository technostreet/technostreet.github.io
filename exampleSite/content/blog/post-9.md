---
title: Updating content via forestry
date: 2022-10-19T04:07:47+00:00
image: images/post/post-6.jpg
description: this is meta description
categories:
- Python
tags:
- Photos
- Game
- HTML
- Python
- New
type: post

---
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<hr>

##### Emphasis

Emphasis, aka italics, with _asterisks_ or _underscores_.

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

<hr>

##### Link

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link](https://www.mozilla.org)

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions](http://slashdot.org)

Or leave it empty and use the [link text itself](http://www.reddit.com).

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or [http://www.example.com](http://www.example.com) and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

<hr>

##### Paragraph

Hugo Folder - /var/www/html/lh/exampleSite/  
Github pages - /var/www/html/technostreet.github.io/

Step 1 - prepare the content using forestry.  
Step 2 - git pull origin hugo  
Step 3 - cd exampleSite/  
Step 4 - hugo --themesDir ../..  
Step 5 - Copy the public folder and push it to master branch.

<hr>

##### List

1. List item
2. List item
3. List item
4. List item
5. List item

##### Unordered List

* List item
* List item
* List item
* List item
* List item

<hr>

##### Code and Syntax Highlighting

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

    No language indicated, so no syntax highlighting. 
    But let's throw in a <b>tag</b>.

<hr>

##### Blockquote

> This is a blockquote example.

<hr>

##### Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
<dt>Definition list</dt>
<dd>Is something people use sometimes.</dd>

<dt>Markdown in HTML</dt>
<dd>Does _not_ work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

<hr>

##### Tables

Colons can be used to align columns.

| Tables | Are | Cool |
| --- | :---: | ---: |
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less | Pretty |
| --- | --- | --- |
| Still | renders | nicely |
| 1 | 2 | 3 |

<hr>

##### Image

![image](../../images/post/post-1.jpg)

<hr>

##### Youtube video

{{< youtube C0DPdy98e4c >}}