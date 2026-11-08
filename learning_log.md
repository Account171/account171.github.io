# Learning Log

## Part 1: GitHub and VS Code workflow

**My commits for this assignment** (paste the commit-history link and list the messages):

- Commit history: https://github.com/Account171/account171.github.io/commits/main
- Commit 1: "Create portfolio structure" (date). Added index.html, style.css, README.md, and learning_log.md.
- Commit 2: "Add content and personalize styling" (date). Replaced placeholders with my own name, skills, and projects, and changed the colors in style.css.
- Commit 3: 

**Pull practice:** Date and what I pulled at the start of a later session:

---

## Part 2: GitHub Copilot interactions



| Type | Prompt or question | What Copilot suggested | What I accepted, changed, or rejected (and why) | How I checked it |
|------|--------------------|------------------------|-------------------------------------------------|------------------|
| Build | Help me improve the About section of my portfolio. Use placeholders, don’t invent facts. | Added a more proffesional About section and made it better. | I accepted the changes, but some things had areas that I needed to fill out, such as it saying [YOUR NAME]. | I looked at what I had before I changed it and after and saw that it made my About section a lot more proffesional. |
| Understand | Explain how the nav links in my index.html connect to the section IDs. | Said that nav links use an anchor tag with a fragment link that matches the section element with the same ID. | I didn't change anything. | I checked it by going to the sections it said contained the section IDs and the nav links. |
| Improve / troubleshoot | Help me check my page on a narrow screen and explain any CSS fix. | Copilot said to test in responsive mode at about 375px wide. It explained that my CSS already handles narrow screens: a media query under 700px turns the two-column hero into one column, and flex-wrap: wrap lets the nav wrap instead of getting crowded. It also offered an optional tweak, adding flex-direction: column to the nav so the brand and links stack on very small phones. | I accepted the explanation because it showed me why the page already works on mobile. I rejected the flex-direction: column tweak because the nav already fit cleanly without it, and stacking would make the sticky header taller and take space from the content. | I opened my page in responsive mode at 375px wide. The hero was a single column and the nav links wrapped onto a second line without overlapping or causing sideways scrolling. I did not add the tweak since nothing looked cramped. |

---

## Part 3: Reflection (150-250 words)

GitHub, VS Code, Copilot, and GitHub Pages each handle a different job in building my portfolio. VS Code is where I write and edit my files, and GitHub stores them and keeps a history of every commit. Copilot answers questions about my code while I work, and GitHub Pages turns the files into a live website anyone can visit.

The hardest part was getting my first commit to work. VS Code opened my folder in Restricted Mode, which blocked Git, so I had to trust the folder. Then Git asked who I was, so I set my name and my GitHub noreply email with git config. After that, the commit went through.

One piece of code I can now explain is flex-wrap. By default, a flex container tries to keep all its items on one line, which can squeeze them or push them off a small screen. Setting flex-wrap: wrap lets items drop onto a new line when there isn’t enough room. I use it on my navigation so the links wrap instead of getting crowded on a phone.

Copilot helped clear up something I was confused about. When I asked it to check my page on a narrow screen, it explained how my media query turns the hero from two columns into one, and why that works.

Next, I want to add a project about the after-school club I'm in.



Word count: 231

---

## Part 4: Testing notes

Change each `[ ]` to `[x]` after you test it, and add a short note on what you saw.

- [ ] The live URL opens in a private/incognito window without signing in. Notes:
- [ ] All required sections are present and contain my own content. Notes:
- [ ] Navigation, GitHub profile, and project links work. Notes:
- [ ] The page is readable on desktop and at a narrow/mobile width. Notes:
- [ ] Images (if used) load correctly and have alt text. Notes:
- [ ] My latest change appears on the published site. Notes:
- [ ] The public website, repository, and screenshots contain no private information. Notes:
