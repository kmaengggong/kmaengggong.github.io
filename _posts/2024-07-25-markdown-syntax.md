---
title: "Markdown Syntax"
excerpt: "LET'S MARKDOWN"
categories:
    - Markdown
tags:
    - [Markdown, Syntax]
toc: true
toc_sticky: true
date: 2024-07-25 14:53:00 +0900
last_modfied_at: 2024-07-25 18:24:00 +0900
---

# Markdown Snyax

## 1. Basic Syntax

### 1-1. Headings
```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

### 1-2. Line Breaks
```
Need to add two spaces or more at the end.  
Then line breaks.
```
Need to add two spaces or more at the end.  
Then line breaks.

### 1-2. Emphasis

#### 1-3-1. Bold
```
- regular **bold**
- regular __bold__
```
- regular **bold**
- regular __bold__

#### 1-3-2. Italic
```
- korec *italic*
- korec _italic_
```
- korec *italic*
- korec _italic_

#### 1-3-3. Strikethrough
```
- ball ~~strikethrough~~
```
- ball ~~strikethrough~~

#### 1-3-3. Bold and Italic and Strikethrough
```
- regular and korec and ball ~~***bold and italic and strikethrough***~~
- regular and korec and ball ~~___bold and italic and strikethrough___~~
- regular and korec and ball ~~__*bold and italic and strikethrough*__~~
- regular and korec and ball ~~**_bold and italic and strikethrough_**~~
```
- regular and korec and ball ~~***bold and italic and strikethrough***~~
- regular and korec and ball ~~___bold and italic and strikethrough___~~
- regular and korec and ball ~~__*bold and italic and strikethrough*__~~
- regular and korec and ball ~~**_bold and italic and strikethrough_**~~

### 1-4. Blockquotes

#### 1-4-1. Blockquotes
```
> block1
```
> block

#### 1-4-2. Blockquotes with Multiple Paragraphs
```
> block1
>
> block2
```
> block1
>
> block2

#### 1-4-3. Nested Blockquotes
```
> block1
> > block2
> > > block3
```
> block1
> > block2
> > > block3

#### 1-4-4. Blockquotes with Other Elements
```
> #### I'm Heading level 4
>
> and I'm ~~bald~~ no **bold**
```
> #### I'm Heading level 4
>
> and I'm ~~bald~~ no **bold**

### 1-5. Lists

#### 1-5-1. Lists
```
1. List 1
2. List 2
3. List 3
    4. List 4
```
1. List 1
2. List 2
3. List 3
    4. List 4

#### 1-5-2. Unordered Lists
```
- List 1
- List 2
- List 3
    - List 4
```
- List 1
- List 2
- List 3
    - List 4

### 1-6. Code

#### 1-6-1. Escaping Backticks
<pre>
<code>
```
public static void main(String[] args) {
    System.out.println("Hello, world!");
}
```
</code>
</pre>

```
public static void main(String[] args) {
    System.out.println("Hello, world!");
}
```

#### 1-6-2. Using HTML Tags
```
<pre>
<code>
public static void main(String[] args) {
    System.out.println("Hello, world!");
}
</code>
</pre>
```
<pre>
<code>
public static void main(String[] args) {
    System.out.println("Hello, world!");
}
</code>
</pre>

#### 1-6-3. Language Highlighting
<pre>
<code>
```java
public static void main(String[] args) {
    System.out.println("Hello, world!");
}
```
</code>
</pre>
```java
public static void main(String[] args) {
    System.out.println("Hello, world!");
}
```

### 1-7. Horizontal Rules
```
***
---
_________________
```
***
---
_________________

### 1-8. Links

#### 1-8-1. Links
```
- Togetoge: [Kara No Hako](https://youtube.com/watch?v=pA-pzhQQFBA&pp=ygUWdG9nZW5hc2hpIHRvZ2Vhcmkgdm9pZA%3D%3D "Ship Duck Warnings")
```
- Togetoge: [Kara No Hako](https://youtube.com/watch?v=pA-pzhQQFBA&pp=ygUWdG9nZW5hc2hpIHRvZ2Vhcmkgdm9pZA%3D%3D "Ship Duck Warnings")

#### 1-8-2. URLs and Email Addresses
```
- Google: <https://www.google.com>
- E-mail: <kmaengggong@gmail.com>
```
- Google: <https://www.google.com>
- E-mail: <kmaengggong@gmail.com>

#### 1-8-3. Reference-style Links
```
[Apologize][1]

[1]: <https://ko.wikipedia.org/wiki/%EC%82%AC%EA%B3%BC> "사과"
```
[Apologize][1]

[1]: <https://ko.wikipedia.org/wiki/%EC%82%AC%EA%B3%BC> "사과"

### 1-9. Images
```
![WR 124 for Chandra's 25th Anniversary](/assets/images/wr-124-for-chandra's-25th-anniversary.jpg "WR 124 for Chandra's 25th Anniversary")
```
![WR 124 for Chandra's 25th Anniversary](/assets/images/wr-124-for-chandra's-25th-anniversary.jpg "WR 124 for Chandra's 25th Anniversary")

#### 1-10. Video (~~It's just HTML code~~)
```
<iframe width="560" height="315" src="https://www.youtube.com/embed/jNQXAC9IVRw?si=Ael_4Th47ROyc5gU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```
<iframe width="560" height="315" src="https://www.youtube.com/embed/jNQXAC9IVRw?si=Ael_4Th47ROyc5gU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## 2. Extended Syntax

### 2-1. Tables

### 2-2. Fenced Code Blocks

### 2-3. Footnotes

### 2-4. Heading IDs

### 2-5. Definition Lists

### 2-6. Task Lists

### 2-7. Emoji

### 2-8. Subscript

### 2-9. Superscript

### 2-10. Automatic URL Linking

### 2-11. Disabling Automatic URL Linking