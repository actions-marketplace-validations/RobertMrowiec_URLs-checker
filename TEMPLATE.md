# DevPath Template file

This file contains a basic structure template for each level of DevPath. Please use it in your paths and remove redundant parts if needed. Please stick to the template for consistency.

## Basic sections example:
### Level Name - Grade I
## Areas
- Table of contents
----
- π¦ - tools (with a short description of the section)
- π - learn (mainly links)
  - π - material to read (aka required)
  - π - nice to read material (aka optional)
- π€ - interview (list of questions that verifies the skill)
- π - katas (jobs that verifies the skill)

----

> Sample:

# Junior - level I

## Areas

**Tools**

- Work environment
- IDE

**Language & Browser API**

- JavaScript Basics

---

## π¦ Tools / Work environment

Know your environment (operating system, terminal, basic command lines, running docker on your machine). Ensure you are able to type with all you fingers, and without looking at the keyboard. Improve your everyday workflow.

### π Learn

- OS - Mac (or other)
  - π [macos](https://support.apple.com/macos)
  - π [mac shortcuts](https://support.apple.com/en-us/HT201236)

- Workflow
  - π [the art of command line: sections: βBasicβ & βEveryday Useβ & βProcessing files and dataβ (](https://github.com/jlevy/the-art-of-command-line)[oh my zsh](https://github.com/robbyrussell/oh-my-zsh), 
    - documentation via tldr/man or [dash](https://kapeli.com/dash) or [devdocs.io](https://devdocs.io/)
  - π [typing](https://www.keybr.com/)


### π€ Interview

- [typing](https://www.keybr.com/)
- Tell me about your environment, what makes it productive one?
- How docker helps with local development?
- What is the use case of environment variable `PATH` and how you can debug it?

### π Katas

- Do you have any plans to improve your productivity? Show me a 3 months plan with steps you would like to implement

---

## π¦ Tools / IDE

Know your editor - below are materials for VSCode, but you can choose other. Ensure you know basic keyboard shortcuts, and you ide / editor is configured in a manner that supports frontend development.

### π Learn

- π [vscode using & customizing](https://github.com/mike-works/vscode-fundamentals/tree/master/docs) (**Usefull Extensions:** ESLint, Sass, Prettier, Jest)
- π [intro to vim: from chapter: "background", to chapter "save & exit"](https://www.turnkeylinux.org/blog/vim-tutorial)
- π [practice vim](https://www.openvim.com/)

### π€ Interview

- Why do you use linters?

### π Katas

- Walk me through your IDE
    - what features you use the most often
    - how did you configure it
    - what plugins do you use
    - Is there anything unique

---

## π¦ Tools / Browser Tools

Read about how the web works - you do not need to remember all the details, just familiar yourself with the concept, and remember where you can find more. Read the documentation for dev tools - to have a overview about what is possible.

### π Learn

- π [how the web works](https://github.com/vasanthk/how-web-works)
- π [what web can do today](https://whatwebcando.today/)
- π choose your tool:
    - **Chrome DevTools**
        - π [crash course](https://www.youtube.com/watch?v=x4q86IjJFag)
        - π [official guide](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)Β - Home/ Open Dev tools / DevTools for beginners / CSS / JavaScript / Console / Network / HTML
    - **Firefox Developer tools**
        - π [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
        - π [Core Tools](https://developer.mozilla.org/en-US/docs/Tools)Β - Page inspector / Web Console / JavaScript Debugger / Network Monitor

### π€ Interview

- What did you learn from the article βhow web worksβ?
- Is there anything interesting your found in the page βwhat web can do today?β

### π Katas

- How dev tools will help you develop and debug the app? (Inspector / console / debugger / network / break points usage)

---

## π¦ Tools / GIT CLI

Be proficient in dealing with GIT from command line - only chapters mention below. For exercises do as much as think you should.

### π Learn

- π [Getting Started](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
- π [Git Basics](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)
- π [Writing Good Commit Message](https://juffalow.com/other/write-good-git-commit-message) 

### π€ Interview

- What is specific about Git (DVCS in general)
- Can you show me your git config?
- How you like browse git history?
- Main stages files can reside in?
- Why and how we should ignore certain files from git history?
- You forgot to include βchangelog.mdβ in your commit, how can you fix it?

### π Katas

- [Labs from 1 to 49](http://gitimmersion.com/)
- [Git Katas](https://github.com/praqma-training/git-katas)
- Are you using git prefixes? Show example in your project

---

## π¦ Language & Browser API / JavaScript Basic

Familiarize yourself with the concepts from the book, be able to explain then, and give an example where you would use it. Have a decent skill in writing solutions & tests in javascript.

### π Learn

- π [Eloquent JavaScript](http://eloquentjavascript.net/) ([our crash course](https://github.com/miksturait/od-zera-do-js-developera))
    - **Optional**
        - [Project: A Programming Language](http://eloquentjavascript.net/12_language.html)
        - [Drawing on Canvas](http://eloquentjavascript.net/17_canvas.html)
        - [Http and the forms](http://eloquentjavascript.net/18_http.html)
        - [Project: Pixlr editor](http://eloquentjavascript.net/19_paint.html)
- π [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)

### π€ Interview

- Software development in general:
  - How you would explain 5 rules of programming in your own words?
  - What is your role in Scrum team and Scrum events?
  - Could you guide me with your own words, throughΒ [Joel Spolsky Test](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/)
- JavaScript:
  - Explain differences between JavaScript, EcmaScrpt & TypeScript (high-level)
  - Explain what is scope. What you should avoid in terms of scope?

### π Katas

- Solve 5 problems (with tests coverage) fromΒ [the list](https://github.com/mre/the-coding-interview/tree/master/problems)