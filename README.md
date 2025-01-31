# FM - Recipe Page Solution - Fraser Jubb

This is a solution to the [Recipe Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

## 📖 Table of contents

- [Overview](#overview)
  - [Project Screenshot](#project-screenshot)
  - [Project Links](#project-links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [A Personal Note](#a-personal-note)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Noteworthy Updates Since Initial Submission](#noteworthy-updates-since-initial-submission)
- [Connect With Me](#connect-with-me)

## Overview

### Project Screenshot

![Screenshot of solution](/assets/images/solution-fraser.png)

### Project Links

- Solution URL: [Click Here](#)
- Live Site URL: [Click Here](https://fm-recipepage-fraser.netlify.app/)
- Frontend Mentor Profile: [@fraserjubb](https://www.frontendmentor.io/profile/fraserjubb)

## My Process

### Built With

- HTML
- CSS
- Desktop-first workflow

### A Personal Note

I started this challenge at the start of October, but then my back seized up. This meant I had to suddenly stop everything coding related and focus on recovery. After multiple intense sessions every single week with my Personal Trainer and Osteopath, I have managed to stabilize my back enough so that I can finally continue my journey learning to code. I immediately continued where I left off with this challenge.

### What I Learned

In this particular project:

1. I learned about `padding-inline-start` and the benefits it has for being able to switch between left-to-right and right-to-left script direction without any changes needing to be made to the code.

```css
.card__list {
  padding-inline-start: var(--sp-20px);
}
```

2. In my previous projects, the _prettier_ extension in vscode has always been changing my html code to sometimes separate one element into multiple lines instead of just one. Adding the following `printWidth` override seems to have fixed this:

```css
 {
  "singleQuote": false,
  "arrowParens": "avoid",

  "overrides": [
    {
      "files": "index.html",
      "options": {
        "printWidth": 250
      }
    }
  ]
}
```

### Continued Development

After submitting this project, I wish to develop the following:

1. Going forward, I would like to keep my CSS code a little more tidy earlier within the development of the project instead of a massive clean up at the end. Just a simple case of staying more organized. Perhaps I will try adding checkpoints to do this.

### Useful Resources

- [Padding-Inline-Start(MDN Documentation)](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline-start) - Demo has `writing-mode` which is useful to see how it works.

## Noteworthy Updates Since Initial Submission

1. No major updates since submitted.

## Connect With Me

<a href="https://github.com/fraserjubb"><img height="30px" align="left" alt="GitHub" style="padding-right:10px" title="Github" src="https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/fraser-jubb"><img height="30px" align="left" alt="LinkedIn" style="padding-right:10px" title="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=plastic&logo=linkedin&logoColor=white"/></a>
<a href="https://www.instagram.com/thejubbzone/"><img height="30px" align="left" alt="Instagram" style="padding-right:10px" title="Instagram" src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=plastic&logo=Instagram&logoColor=white"/></a>
<a href="https://x.com/fraserjubb"><img height="30px" align="left" alt="X" style="padding-right:10px" title="X" src="https://img.shields.io/badge/X-%23000000.svg?style=plastic&logo=X&logoColor=white"/></a>
<a href="https://www.youtube.com/@thejubbzone2374"><img height="30px" align="left" alt="YouTube" style="padding-right:10px" title="YouTube" src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white"/></a>
<a href="mailto:fraserjubb.dev@gmail.com"><img height="30px" align="left" alt="Gmail" style="padding-right:10px" title="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=plastic&logo=gmail&logoColor=white"/></a>

<br/>
