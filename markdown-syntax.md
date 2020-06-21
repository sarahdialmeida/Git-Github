# Markdown Language
_Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor._ Source: [Wikipedia](https://en.wikipedia.org/wiki/Markdown)

# Title level 1
## Title level 2
### Title level 3
#### Title level 4
##### Title level 5
###### Title level 6


**bold text** __bold text__ (double asterisks or double underscores) 

*italic* _italic_ (one asterisk or one underscore)

~~Strikethrough~~

**_bold & italic_**

# <h1> text between double lines

## Horizontal Rules 
(***) or (___)
***




## Unordered lists 
(use asterisks, pluses, and hyphens - tab for subitens)
- 1
    - 1.1
    - 1.2
- 2
  - 2.1
  - 2.2
+ 1
    + 1.1
    + 1.2
+ 2
  + 2.1
  + 2.2    
* 1
  * 1.1
* 2
  * 2.1
* 3
* 4
* 5

## Ordered lists using numbers 
1. Iten 1
2. Iten 2
   1. Iten 2.1
3. Iten 3
   1. Iten 3.1
   2. Iten 3.2

## Task lists 

- [x] Study Github
- [x] Create a repository for Git & Github documentation
- [x] Code in Java for 4 hours
- [ ] Call mum
- [ ] Run for 30 min
- [ ] Practice yoga for 1 hour
- [ ] Bake a cake


## Inserting a image

Suported files: gif, jpeg, jpg, png, docx, gz, log, pdf, pptx, txt, xlsx or zip.

![Description here](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Macaca_nigra_self-portrait_large.jpg/173px-Macaca_nigra_self-portrait_large.jpg)


<!-- COMENTS -->


## Create links: 
- same to images, except for the !exclamation mark

[Link to my GitHub](https://github.com/sarahdialmeida)

### Tables


| Name |  Meal  | Order|
| -----| -----  | ---- |
| Rose | quiche | 5    |
| Mary | salad  | 2    |


## Quotes or citations
Introducing my quote:

> Neque porro quisquam est qui 
> dolorem ipsum quia dolor sit amet, 
> consectetur, adipisci velit...

## Code blocks

```
This is a code block
```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```

## Insert emojis 
- colon +  shortcode + colon

:vulcan_salute: :blush: :technologist:

You will find all emoji´s shortcodes [here](https://github.com/ikatyang/emoji-cheat-sheet). Thanks @ikatyang!  	:smiley:

## To tag someone in GitHub:
- just use @ 

Exemple: @sarahdialmeida



