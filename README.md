# How to host a resume on GitHub Pages

## Purpose

This README will guide you, the user, how to host and format your resume on GitHub Pages. Andrew Etter's describes a simple process to put your resume online in his book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

> This guide is intended for a computer science student who has no experience with Markdown or GitHub, and also interested in learing about technical communication.

## Prerequisites

1. **Basic understanding of Markdown.**
   If you have never worked in Markdown before, you can learn it via a tutorial [here](#More-Resources).

2. **Create a GitHub account.** You need a GitHub account to host your resume. You can visit their main web site [here](https://github.com/join) to create account.

3. **Install GitHub desktop software** You can download [here](https://desktop.github.com/). It is a tool that allows you to interact with GitHub from your desktop.

---

### Writing your resume in Markdown

### Host your resume to GitHub.

1.  Open the GitHub Desktop App.

1.  Create a new Repository

    > The Repository is a place where you are goint to store your files.
    > Click `File` on top of your screen and click `New Repository`.
    > Name the new repository your `repository_name.github.io`

    >![repo](https://user-images.githubusercontent.com/57551793/97372034-a4851e00-1880-11eb-9bf4-3bb03aaa6ce9.gif)

1. Open Visual Studio Code.

   > Click the `Visual Studio Code`. Now GitHub Desktop will use the reposiotry that you just create.

   > You can change External Editor. Click `Preference` and go `Advanced` then choose other editor.
![IMG_50EC0F8EDD6F-1](https://user-images.githubusercontent.com/57551793/97371524-62a7a800-187f-11eb-950c-d40816effb7f.jpeg v=4&s=200)
1. Write your resume in Markdown.

   1. Create a new text file and save it as " **_index<i></i>.md_** "

      > The reason for make file with the name is GitHub Pages looks for "_index<i></i>.md_ " file to use as the main page of your site.

   1. Enter your Resume Header.

      > On the Header put your name and contack information.

      ```
      ## Your Name
      Phone: (555) 555-5555 |
      Email: person@gmail.com |
      GitHub link: github.com/githubId
      ```

   1. Add your technical sklls, experience and education with details as subheading.

      ```
      ### Education
         - **B.Sc. Computer Science Major** | Name of University  | 2016 - Present

      ### **TECHNICAL SKILLS**
         - HTML/ CSS / JS

      ### **Work Experience**
         - Google | Porject Manager | Sep 2017 - Dec 2018

      ```

1. Push your Resume to GitHub

   > When you finish your resume, then go to the GitHub Desktop app then it will show what you have made changes do your Markdown document.

   > To host the file to your GitHub webpage, click `commit master` button and then click `Push origin` button.

1. Visit your GitHub website.

   > Now you can see your

### More Resources

Markdown Resources

- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Andrew Etter: Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown Quick Reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

GitHub

- [Github Pages Help](https://help.github.com/en/github/working-with-github-pages)

---

## Authors and Acknowledgments

- Thanks to Etter Andrew who written Modern Technical Writing. It inspired me about technical writing. Especially reagarding writing resume and put it on online.

- Thanks to my group member for consultation during this assignment, whose help was required to get this one in time with better vocabulary and grammer.

---

## FAQs

### **Why is Markdown better than a word processor?**

- Version control system : When you work with someone else, using a word processor is relly hard to merge changes. But Markdown helps keep your file update.

- Variaty platform : Markdown is like plain text so any operating system can read it and also it can easily be converted to any format such as pdf, dock, HTML. On the other hand, if you use word processor the other person need to have Word or something that can opern the word file to see it.

### **How to update my resume on my GitHub pages?**

- You can update your Markdown resume on the GitHub page. First you can go your repository where you upload your resume. If you followed by my instruction then it supposed to be name `index.md`. So just click the Markdown and on the right hand side click edit icon. Now you will be able to edit your resume.
