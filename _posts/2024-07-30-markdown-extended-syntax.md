---
title: "Markdown Extended Syntax"
excerpt: "LET'S MARKDOWN"
categories:
    - Guitar
tags:
    - [Markdown, Syntax]
toc: true
toc_sticky: true
date: 2024-07-30 14:30:00 +0900
last_modfied_at: 2024-07-30 16:20:00 +0900
---

## 1. Tables

### 1-1. Tables
```
| Album | Type | Release Date |
| --- | --- | --- |
| Nameless Name | Single | 2023.07.26 |
| White Drizzle in Gloom | Single | 2023.08.30 |
| Bleeding Hearts | Single | 2023.10.25 |
```

| Album | Type | Release Date |
| --- | --- | --- |
| Nameless Name | Single | 2023.07.26 |
| White Drizzle in Gloom | Single | 2023.08.30 |
| Bleeding Hearts | Single | 2023.10.25 |

💡 표 윗줄 한 칸 뛰어야 나옴
{: .notice--info}

### 1-2. Alignment
```
| Albummmmmmmm | Typeeeeeeeee | Release Dateeeeeeee |
| :--- | :---: | ---: |
| Nameless Name | Single | 2023.07.26 |
| White Drizzle in Gloom | Single | 2023.08.30 |
| Bleeding Hearts | Single | 2023.10.25 |
```

| Albummmmmmmm | Typeeeeeeeee | Release Dateeeeeeee |
| :--- | :---: | ---: |
| Nameless Name | Single | 2023.07.26 |
| White Drizzle in Gloom | Single | 2023.08.30 |
| Bleeding Hearts | Single | 2023.10.25 |

## 2. Fenced Code Blocks

### 2-1. Fenced Code Blocks
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

### 2-2. Using HTML Tags
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

💡 원래 되는데 Minimal Mistakes에선 적용이 안됨
{: .notice--info}

### 2-3. Language Highlighting
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

## 3. Footnotes
```
Nina Iseri[^1]

[^1]: Seiron Monster
```

Nina Iseri[^1]

[^1]: Seiron Monster

## 4. Definition Lists
```
Momoka Kawaragi
: Lead Guitar
: Dattai

Subaru Awa
: Drummer
: Usotsuki
```
Momoka Kawaragi
: Lead Guitar
: Dattai

Subaru Awa
: Drummer
: Usotsuki

## 5. Task Lists
```
- [x] Standing Middle Fingers
- [x] Standing Little Fingers
- [ ] Beating Diamond Dust
```
- [x] Standing Middle Fingers
- [x] Standing Little Fingers
- [ ] Beating Diamond Dust

## 7. Emoji
```
:jack_o_lantern: Jack-O' Valentine

🎃 Jack-O' Valentine
```
:jack_o_lantern: Jack-O' Valentine

🎃 Jack-O' Valentine

💡 원래 나와야 되는데 여러모로 안나오는 경우가 있나 보다. 그냥 복사해서 쓰자.
{: .notice--info}

## 8. Highlight
```
- I want to get ==Chiyahoya==
- I want to get <mark>Chiyahoya</mark>
```
- I want to get ==Chiyahoya==
- I want to get <mark>Chiyahoya</mark>

💡 이건 또 왜 안 먹혀
{: .notice--info}

## 9. Subscript
```
- Suso-water is good. Because it contains a lot of H~2
- Suso-water is good. Because it contains a lot of H<sub>2</sub>
```
- Suso-water is good. Because it contains a lot of H~2
- Suso-water is good. Because it contains a lot of H<sub>2</sub>

## 9. Superscript
```
- 2^2 2^e e^2 e^e
- 2<sup>2</sup> 2<sup>e</sup> e<sup>2</sup> e<sup>e</sup>
```
- 2^2 2^e e^2 e^e
- 2<sup>2</sup> 2<sup>e</sup> e<sup>2</sup> e<sup>e</sup>

💡 HTML > Markdown
{: .notice--info}

## -1. Reference
\[1\]: [https://www.markdownguide.org/extended-syntax/](https://www.markdownguide.org/extended-syntax/)