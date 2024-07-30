---
title: "Markdown Basic Syntax"
excerpt: "LET'S MARKDOWN"
categories:
    - Guitar
tags:
    - [Markdown, Syntax]
toc: true
toc_sticky: true
date: 2024-07-25 14:53:00 +0900
last_modfied_at: 2024-07-30 14:10:00 +0900
---

## 1. Headings
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

## 2. Line Breaks
```
Need to add two spaces or more at the end.  
Then line breaks.
```
Need to add two spaces or more at the end.  
Then line breaks.

## 3. Emphasis

### 3-1. Bold
```
- regular **bold**
- regular __bold__
```
- regular **bold**
- regular __bold__

### 3-2. Italic
```
- korec *italic*
- korec _italic_
```
- korec *italic*
- korec _italic_

### 3-3. Strikethrough
```
- ball ~~strikethrough~~
```
- ball ~~strikethrough~~

### 3-4. Bold and Italic and Strikethrough
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

## 4. Blockquotes

### 4-1. Blockquotes
```
> block1
```
> block

### 4-2. Blockquotes with Multiple Paragraphs
```
> block1
>
> block2
```
> block1
>
> block2

### 4-3. Nested Blockquotes
```
> block1
> > block2
> > > block3
```
> block1
> > block2
> > > block3

### 4-4. Blockquotes with Other Elements
```
> #### I'm Heading level 4
>
> and I'm ~~bald~~ no **bold**
```
> #### I'm Heading level 4
>
> and I'm ~~bald~~ no **bold**

## 5. Lists

### 5-1. Lists
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

### 5-2. Unordered Lists
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

## 6. Code

### 6-1. Code
```
- I can print <code>Hello, world!</code>
- I can print `Hello, world!`
```
- I can print <code>Hello, world!</code>
- I can print `Hello, world!`

### 6-2. Escaping Backticks
```
``I can escape `backticks`!``
```
``I can escape `backticks`!``

### 6-3. Code Blocks
```
    <html>
        <head>
        </head>
    </html>
```
    <html>
        <head>
        </head>
    </html>

## 7. Horizontal Rules
```
***
---
_________________
```
***
---
_________________

## 8. Links

### 8-1. Links
```
- Togetoge: [Kara No Hako](https://youtube.com/watch?v=pA-pzhQQFBA&pp=ygUWdG9nZW5hc2hpIHRvZ2Vhcmkgdm9pZA%3D%3D "Ship Duck Warnings")
```
- Togetoge: [Kara No Hako](https://youtube.com/watch?v=pA-pzhQQFBA&pp=ygUWdG9nZW5hc2hpIHRvZ2Vhcmkgdm9pZA%3D%3D "Ship Duck Warnings")

### 8-2. URLs and Email Addresses
```
- Google: <https://www.google.com>
- E-mail: <kmaengggong@gmail.com>
```
- Google: <https://www.google.com>
- E-mail: <kmaengggong@gmail.com>

### 8-3. Reference-style Links
```
- [Apologize][1]

[1]: <https://ko.wikipedia.org/wiki/%EC%82%AC%EA%B3%BC> "사과"
```
- [Apologize][1]

[1]: <https://ko.wikipedia.org/wiki/%EC%82%AC%EA%B3%BC> "사과"

### 8-4. New Tabs
```
- New Tab: [새 창](https://search.naver.com/search.naver?where=nexearch&sm=top_hty&fbm=0&ie=utf8&query=%EC%83%88+%EC%B0%BD){:target="_blank"}
```
- New Tab: [새 창](https://search.naver.com/search.naver?where=nexearch&sm=top_hty&fbm=0&ie=utf8&query=%EC%83%88+%EC%B0%BD){:target="_blank"}

## 9. Images
```
![WR 124 for Chandra's 25th Anniversary](/assets/images/wr-124-for-chandra's-25th-anniversary.jpg "WR 124 for Chandra's 25th Anniversary")
```
![WR 124 for Chandra's 25th Anniversary](/assets/images/wr-124-for-chandra's-25th-anniversary.jpg "WR 124 for Chandra's 25th Anniversary")

## 10. Video (~~It's just a HTML code~~)
```
<iframe width="560" height="315" src="https://www.youtube.com/embed/jNQXAC9IVRw?si=Ael_4Th47ROyc5gU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```
<iframe width="560" height="315" src="https://www.youtube.com/embed/jNQXAC9IVRw?si=Ael_4Th47ROyc5gU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## -1. Reference
\[1\]: [https://www.markdownguide.org/basic-syntax/](https://www.markdownguide.org/basic-syntax/)