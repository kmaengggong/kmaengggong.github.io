---
title: "First Post"
categories: [Blog]
tag: [Test]
image: /assets/img/test/james-webb-cosmic-cliffs.jpg
---

# 1. 기본 설정(.yml)
```yaml
title: "First Post"
categories: [Docs]
tag: [Test]
image: /path/to/img/james-webb-cosmic-cliffs.jpg  // Preview Image
pin: false
```

# 2. Syntax
## 2-1. Headers
```markdown
# Heaeder1
## Header2
### Header3
// h1 ~ h6 까지 있음
```
# Header1
## Header2
### Header3

## 2-2. Block Quote
```markdown
> block quote 1
> > block quote 2
> > > block qoute 3
```
> block quote 1
> > block quote 2
> > > block qoute 3

## 2-3. List
```markdown
1. First
2. Second
3. Third
```
1. First
2. Second
3. Third

```markdown
- First
    - Second
        - Third
// -가 아니라 *, + 사용해도 됨
```
- First
    - Second
        - Third

```markdown
- [ ] Job 1
    - [x] Step 1
    - [ ] Step 2
```
- [ ] Job 1
    - [x] Step 1
    - [ ] Step 2

## 2-4. Prompts
````markdown
> Prompt Tip
{: .prompt-tip}
> Prompt Info
{: .prompt-info}
> Prompt Warning
{: .prompt-warning}
> Prompt Danger
{: .prompt-danger}
````
> Prompt Tip
{: .prompt-tip}
> Prompt Info
{: .prompt-info}
> Prompt Warning
{: .prompt-warning}
> Prompt Danger
{: .prompt-danger}

## 2-5. Tables
```html
<table>
    <thead>
        <tr>
            <th>Col1</th>
            <th>Col2</th>
            <th>Col3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row1</td>
            <td>Row1</td>
            <td>Row1</td>
        </tr>
        <tr>
            <td>Row2</td>
            <td>Row2</td>
            <td>Row2</td>
        </tr>
    </tbody>
</table>
```
<table>
    <thead>
        <tr>
            <th>Col1</th>
            <th>Col2</th>
            <th>Col3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row1</td>
            <td>Row1</td>
            <td>Row1</td>
        </tr>
        <tr>
            <td>Row2</td>
            <td>Row2</td>
            <td>Row2</td>
        </tr>
    </tbody>
</table>

## 2-6. Link
```markdown
// [Title](link)
[kmaengggong.github.io](https://kmaengggong.github.io "to home!")
```
[kmaengggong.github.io](https://kmaengggong.github.io "to home!")

```markdown
// <link>
// <address>
<https://kmaengggong.github.io>
<kmaengggong@gmail.com>
```
<https://kmaengggong.github.io>  
<kmaengggong@gmail.com>

## 2-7. Inline Code
```markdown
`Inline Code`
```
`Inline Code`

## 2-8. Code Blocks
```markdown
```java
public static void main(String[] args){
    System.out.println("Hello, Java!");
}
\\ ```
```

## 2-9. Line Break
```markdown
// Space Bar 두 번  
first line  
second line
```
first line  
second line

## 2-10. Code Emphasis
```markdown
*TEXT*  
**TEXT**  
~~TEXT~~
// *는 _로 바꿔도 됨
```
*TEXT*  
**TEXT**  
~~TEXT~~

## 2-11. Images
```markdown
![random-image](https://picsum.photos/id/2/600/400)
![test-image](/assets/img/test/james-webb-deepest-coldest-ices.png)
![test-image2](/assets/img/test/james-webb-galaxies-stephans-quintet.jpg){: w="700" h="400"}
![test-image3](/assets/img/test/james-webb-jupiter.png){: w="200" h="200" .right}  // .nomral, .left, .right
![test-image4](/assets/img/test/james-webb-satern.png){: .shadow}
_Neptune Shows Off Its Rings in Near-Infrared Light_  // Image Caption
```
![random-image](https://picsum.photos/id/2/600/400)
![test-image](/assets/img/test/james-webb-deepest-coldest-ices.png)
![test-image2](/assets/img/test/james-webb-galaxies-stephans-quintet.jpg){: w="700" h="400"}
![test-image3](/assets/img/test/james-webb-jupiter.png){: w="200" h="200" .right}
![test-image4](/assets/img/test/james-webb-satern.png){: .shadow}
_Neptune Shows Off Its Rings in Near-Infrared Light_

# 3. Videos
{% raw %}
```liquid
// {% include embed/{Platform}.html id='{ID}' %}
{% include embed/youtube.html id='jNQXAC9IVRw' %}  // https://www.youtube.com/watch?v=jNQXAC9IVRw
```
{% endraw %}
{% include embed/youtube.html id='jNQXAC9IVRw' %}

# 4. Comments
```html
// _includes 폴더에 해당 내용을 comments.html로 저장해두면 자동으로 나옴
<script src="https://utteranc.es/client.js"
        repo="kmaengggong/kmaengggong.github.io-utterances"
        issue-term="pathname"
        label="utterances"
        theme="github-dark"
        crossorigin="anonymous"
        async>
</script>
```
<br>
<br>
<script src="https://utteranc.es/client.js"
        repo="kmaengggong/kmaengggong.github.io-utterances"
        issue-term="pathname"
        label="utterances"
        theme="github-dark"
        crossorigin="anonymous"
        async>
</script>