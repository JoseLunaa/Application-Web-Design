# Application-Web-Design

## Student Information

**Name:** Jose Guadalupe Luna Luna  
**Registration number:** AI03112365  
**Degree:** Ing. Desarrollo de software  
**Semester:** 6to Semestre  

## Subject Information

**Subject:** Diseño de aplicaciones web  
**Professor:** Jose Ricardo Zapata Solis



## What is Markdown?

Markdown is a simple language used to format text.  

It is used mainly to create README files on GitHub and to write documentation in an easy and clean way.

---



## Section 1: Markdown Tagging Options



Markdown is like writing normal text, but using simple symbols to give format to the content.



### How to make headers



You can create titles and subtitles using the `#` symbol.





# Big title

## Subtitle

### Smaller title



---

### How to make text bold or italic

- **Bold text**: write `**text**` → **like this**

- *Italic text*: write `\*text\*` → *like this*

- ~~Strikethrough~~: write `~~text~~` → ~~like this~~


---


### How to make lists

**Bullet list example:**


- Item 1
- Item 2

&nbsp; - Sub-item

&nbsp; - Another sub-item





**Numbered list example:**




1. First item

2. Second item

3. Third item




---



### How to add links



```md

[GitHub](https://github.com)

```



---



### How to add code



**One line of code:**



```md

`console.log("Hello");`

```



**Multiple lines of code:**



```javascript

function hello() {

&nbsp; console.log("Hello World");

}

```



---



### How to add quotes



```md

> This is a quote written in Markdown.

```



---



### How to make tables



| Name  | Age | City     |

|-------|-----|----------|

| John  | 25  | New York |

| Maria | 30  | London   |




---



## Section 2: Git Commands



Git is like a time machine for your files. It lets you save changes, go back in time, and work safely.



### Check status of local repository



```bash

git status

```



### Add individual files or globally



```bash

git add README.md

git add .

git add *.js

```



### Add comments to the commit



```bash

git commit -m "Added Markdown section"

```



### Upload changes to remote repository



```bash

git push origin main

```



### Create, browse, and delete branches



```bash

git branch feature-name

git checkout -b feature-name

git branch

git branch -a

git checkout branch-name

git branch -d branch-name

```



### Roll back to a specific commit



```bash

git log --oneline

git reset --soft abc1234

git reset --hard abc1234

```



---



## Daily Workflow Examples



### Normal daily work



```bash

git status

git add .

git commit -m "Description"

git push origin main

```



### Working on a new feature



```bash

git checkout -b my-feature

git add .

git commit -m "Added feature"

git push origin my-feature

git checkout main

git merge my-feature

git branch -d my-feature

```



---



## Common Problems and Solutions



### You are not on any branch



```bash

git checkout main

```



### Uncommitted changes



```bash

git stash

git checkout -- filename.txt

```



### Can't push



```bash

git pull origin main

git push origin main

```


