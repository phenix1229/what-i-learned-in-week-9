# what-i-learned-in-week-9

## Flexbox

A way to arrange elements easier with CSS.
* Assigned to parent element (directs child elements)
* Can only be a row or a column

*Example:*
```
<div id="parent">
    <div></div>
    <div></div>
    <div></div>
</div>

#parent {
    display: flex;
    flex-direction: row;
}
```

### Copy-ocelot
The object of this exercise was to copy the look of a website using flexbox to organize the layout.

https://github.com/phenix1229/copy-ocelot

---

## Git collaboration

Add collaborator(s), have them clone your repository, make and push changes one person at a time, the other person can then pull the changes from the repo.

### Instabox

This project was focused on teamwork and collaborating through Git in order to copy an instagram page using flexbox.

https://github.com/phenix1229/instabox

---

## Responsive design

Designing page layout so it will look good on varying sized screens (desktop, tablet, phone). Use media queries to set points where display changes are made.

*Example:*

```
@media (max-width: 300px){
    body {
        flex-direction: column;
    }

    #mainDiv {
        width: 100vw;
    }
}
```


### Holy-moley

This was a practice exercise to arrange the layout so the elements looked good on 3 different types of screens.

https://github.com/phenix1229/holy-moley

### Responsive portfolio

This project involved remaking a previous portfolio to make it responsive.

https://github.com/phenix1229/portfolio-html-2-old