## Your Info:

Matric Number:  300206
Name: Nor Fitriyani Binti Zainol Abidin

## Objective

Learn how to create and publish a simple personal website using basic HTML elements and GitHub Pages.


## Learning Outcomes
By the end of this tutorial, students should be able to:
1. Apply appropriate HTML tags to create a well-structured resume page.
1. Add images, hyperlinks, and lists to format web content effectively.
1. Create multiple linked web pages (e.g., Home, Hobbies, Contact).
1. Upload and manage files in a GitHub repository.
1. Publish their personal website using GitHub Pages and share it publicly.

## Instruction

1. Create _THREE (3)_ HTML pages (Home, Hobbies, Contact) for your `Resume` website.
2. Create `style.css` for styling the pages.
3. Create a new empty repo on GitHub (e.g., my-resume-site).
4. Use the Git command to upload your resume to GitHub
```
git init
git add .
git commit -m "Initial resume site"
git branch -M main
git remote add origin https://github.com/<yourusername>/my-resume-site.git
git push -u origin main
```

5. Publish with GitHub Pages
   - On GitHub: Settings → Pages
   - Source: “Deploy from a branch”
   - Branch: main · Folder: / (root) → Save
   - Wait a moment, then your site appears at
```
https://<yourusername>.github.io/my-resume-site/
```

## Submission

1. Add your Matric Number and Name.
2. Add your Resume link below.
3. Write the mistake in the git or GitHub instructions.

## What is the mistake?
The mistake in the Git instructions is that they assume the GitHub repository is completely empty. If the repository already contains a README file or an initial commit, the `git push -u origin main` command may be rejected with a non-fast-forward error. The local and remote repositories must first be synchronised using `git pull` before pushing the files.

## Link to your Resume
https://nftryani29-beep.github.io/fitriyani-resume-site/

## Link of YouTube References (at least five references)
1. Coder Coder. (2026, June 28). Learn Git & GitHub for beginners | (2026) tutorial [Video]. YouTube. https://www.youtube.com/watch?v=h2a3Kw-I_Ec

2. Stratvert, K. (2022, June 24). Git and GitHub tutorial for beginners [Video]. YouTube. https://www.youtube.com/watch?v=tRZGeaHPoaw

3. Coding2GO. (2025, August 4). Build a personal website with HTML & CSS (beginner crash course) [Video]. YouTube. https://www.youtube.com/watch?v=ZPMtug9qExk

4. GitHub. (2026, April 13). Getting started with GitHub Pages for beginners | Tutorial [Video]. YouTube. https://www.youtube.com/watch?v=b2r9Cdvssi0

5. SuperSimpleDev. (n.d.). How to put an HTML website on the internet [Video]. YouTube. https://youtu.be/p1QU3kLFPdg





