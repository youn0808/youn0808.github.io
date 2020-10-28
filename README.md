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

### Host your resume to GitHub.

1.  Open the GitHub Desktop App.

1.  Create a new Repository

    > The Repository is a place where you are goint to store your files.
    > Click `File` on top of your screen and click `New Repository`.
    > Name the new repository your `repository_name.github.io`

    > ![repo](https://user-images.githubusercontent.com/57551793/97372034-a4851e00-1880-11eb-9bf4-3bb03aaa6ce9.gif)

1.  Open Visual Studio Code.

    > Click the `Visual Studio Code`. Now GitHub Desktop will use the reposiotry that you just create.

    > You can change to other editor. Click `Preference` and go `Advanced` then choose other editor.
    > ![click](https://user-images.githubusercontent.com/57551793/97372256-34c36300-1881-11eb-918e-e5dcbcf97838.png)

1.  Write your resume in `Markdown`.

- **Need to use Lightweight Markup**: When you write `README` and `Resume` in our case, you need to use lightweight markup langues such as GitHub Flavored Markdown and also you should use a editor such as Atom, Sublime Text and Visual Studio to write lightweight markup.<br> If you write XML by hands, it is very tedious and error prone. For example, a small missing slash or bracket can break an entire page.

1.  Create a new text file and save it as " **_index<i></i>.md_** "

    > The reason for make file with the name is GitHub Pages looks for "_index<i></i>.md_ " file to use as the main page of your site.

1.  Enter your Resume Header.

    > On the Header put your name and contact information.

    ```
    ## Your Name
    Phone: (555) 555-5555 |
    Email: person@gmail.com |
    GitHub link: github.com/githubId
    ```

1.  Add your technical sklls, experience and education with details as subheading.

    ```
    ### Education
       - **B.Sc. Computer Science Major** | Name of University  | 2016 - Present

    ### **TECHNICAL SKILLS**
       - HTML/ CSS / JS

    ### **Work Experience**
       - Google | Porject Manager | Sep 2017 - Dec 2018

    ```

1.  Push your Resume to GitHub

    - **Use Distributed Version Control (DVCS)** : It enables you to manage the changes offline and allows you to branch stay in sync. <br>Unlike ./docs directory make dramatically slow down to access, using DVCS is way faster. So most developers perfer using it.

    > When you finish your resume, then go to the GitHub Desktop app then it will show what you have made changes do your Markdown document.<br>
    > To host the file to your GitHub webpage, click `commit master` button and then click `Push origin` button.

    > Now you can see your resume on the GitHub page.

    > ![commit](https://user-images.githubusercontent.com/57551793/97372613-072ae980-1882-11eb-8252-5f538e6a8daa.gif)

1.  Host static website on GitHub Pages.

    - **Make Static website** :
      It consists of only simple documents, so there is little communication between servers, so the speed is fast and also you don't need to install anything.<br>
      You can manually create a simple static website but it is very tedious and error prone so it is better to using static stie generator such as Jekyll.<br> you can learn it via a tutorial [here](#More-Resources).

    > Go to your repository, click the `Settings`.
    > ![IMG_EC2F5E6348ED-1 2](https://user-images.githubusercontent.com/57551793/97400157-a1a81e80-18bc-11eb-8bfe-2f77213dcb00.jpeg)

    > Select `"Master branch"`.
    > ![theme_1](https://user-images.githubusercontent.com/57551793/97400490-3448bd80-18bd-11eb-92ab-3aff29bb584f.gif)

    Now you are suppose to see your Markdown resume online. "`<YourUserName>`.github.io".

1.  Applying a Theme to your Resume.

    - You can customize the theme by using it which make your page speciall.
      Our tutorial shows you Jekyll functionality to select a theme for your resume.<br>

    > In the setting screen, you can scroll down and click `Change theme` > ![IMG_A4B61453EEA2-1](https://user-images.githubusercontent.com/57551793/97402107-fd27db80-18bf-11eb-942e-18ecfb8e2491.jpeg)

    > You can choose your favorit theme and click `Select theme`.
    > ![IMG_2E83ED09A6AE-1](https://user-images.githubusercontent.com/57551793/97402151-10d34200-18c0-11eb-9d10-66a5f72f77e8.jpeg)

    Now your Resume theme is changed.

### More Resources

Markdown

- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Andrew Etter: Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown Quick Reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

GitHub

- [Github Pages Help](https://help.github.com/en/github/working-with-github-pages)

Jekyll

- [Jekyll Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

---

## Authors and Acknowledgments

- Thanks to Etter Andrew who written Modern Technical Writing. It inspired me about technical writing. Especially reagarding writing resume and put it on online.

- Thanks to my group member for consultation during this assignment, whose help was required to get this one in time with better vocabulary and grammer.

---

## FAQs

### **Why is Markdown better than a word processor?**

- Version control system : When you work with someone else, using a word processor is relly hard to merge changes. But Markdown helps keep your file update.

- Variaty platform : Markdown is like plain text so any operating system can read it and also it can easily be converted to any format such as pdf, dock, HTML. On the other hand, if you use word processor the other person need to have Word or something that can opern the word file to see it.

### **Why is my resume not showing up on the page?**

There are many reasons that could cause your website to not show up,

- There will be many reasons that could vause your website to not show up. First, the most common mistake is you might not make your resume to name `"index.md"`.
  Another common issue could be that your repository is named is not exactly match your github account name.

### **How to update my resume on my GitHub pages?**

- You can update your Markdown resume on the GitHub page. First you can go your repository where you upload your resume. If you followed by my instruction then it supposed to be name `index.md`. So just click the Markdown and on the right hand side click edit icon. Now you will be able to edit your resume.
