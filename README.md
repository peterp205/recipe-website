# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./assets/images/127.0.0.1_5500_index.html(iPhone%20SE).png)

### Links

- Solution URL: [Live solution](https://peterp205.github.io/recipe-website/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This project felt pretty straight forward although I made a mistake early on not working mobile first on all the elements and retrospectivley had to then move some parts about. I hadn't really worked with tables so I was happy with the table styling. Most of this project was very independent for me without needed to research support on elements. I did use Gemini for a code review of the documents which was helpful. In future I might have played more about with refining sizes to be exact however I feel this is a waste of learning time as I understand the premise and this project is to learn.

```html
<table>
            <tr>
              <th scope="row">Calories</th>
              <td>277kcal</td>
            </tr>
            <tr>
              <th scope="row">Carbs</th>
              <td>0g</td>
            </tr>
            <tr>
              <th scope="row">Protein</th>
              <td>20g</td>
            </tr>
            <tr>
              <th scope="row">Fat</th>
              <td>22g</td>
            </tr>
          </table>
```
```css
/** Table styles */

table {
  border-collapse: collapse;
  min-width: 100%;
  margin: 0 auto;
}
td,
th {
  border-bottom: 1px solid var(--stone-150);
  padding: 0.5rem 1rem;
  text-align: start;
}

tr:last-of-type th,
tr:last-of-type td {
  border: none;
}

th {
  font-weight: 400;
}
td {
  color: var(--brown);
  font-weight: 600;
}
```

### AI Collaboration

I used Gemini to support throughout my project. I ensured to feed it the frontend mentor guidance which really helps it not give answers but only hints and support. How I used the AI is as follows:

- as a tutor for certain elements like the table
- It helped identify accessability info like the use of `scope="row"`

**Note: Delete this note and the content above if you didn't use AI, or replace with your own experience.**

## Author

- Website - [Add your name here](https://www.cv.cactiwebdesign.com)
- LinkedIn - [@PeterBrewster](https://www.linkedin.com/in/peter-brewster-9342792a5/)

