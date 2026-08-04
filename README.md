# GlobalAI

Student built AI projects from the B.Tech in Artificial Intelligence programme at
[GCST](https://gcst.edu.np/).

**The website: https://globalai.github.io/**

There is no build step. Every file in this repository is served exactly as it is written.
`projects/pod-07/index.html` is the page at `https://globalai.github.io/projects/pod-07/`.
Change the file, and two minutes later the page has changed.

---

# Students, start here

You do not need to install anything. Everything happens in your browser.

## Your page

Your project is **Pod 7**, and your web address is:

```
https://globalai.github.io/projects/pod-07/
```

That address never changes. Print it on a poster, put it on your CV.

## Editing it

1. Click **projects** above, then your folder, for example `pod-07`.
2. Click **index.html**.
3. Click the **pencil icon** at the top right.
4. Change the words between the tags. `<h1>Pod 7</h1>` becomes `<h1>Crop Disease Scanner</h1>`.
5. Click the green **Commit changes** button, then **Commit changes** again.
6. Wait two minutes, then open your address and refresh.

Change the words, keep the tags. `<p>` and `</p>` are the machinery. The text between them is
yours.

## Your folder

```
projects/pod-07/
├── index.html   your page
├── style.css    the colours and spacing
└── images/      your pictures
```

Those three things are yours. Nothing you do to them can affect any other project or the front
page.

## Adding a picture

Open your **images** folder, click **Add file**, then **Upload files**, drag the picture in, and
click **Commit changes**.

Then in `index.html`, change the file name in this line:

```html
<img src="images/cover.svg" alt="A picture of our project">
```

to your file, for example `images/field-photo.jpg`. Type the name exactly, capital letters
included.

## Changing the colours

Open `style.css` and change this one line near the top:

```css
--accent: #0d5c4a;
```

Any colour code works. Search the web for "colour picker hex" to find one.

## Adding your code

Make a folder called `code` and upload your Python files or Colab notebooks into it. Nobody runs
them. They are there so other people can read what you did.

---

## Rules

1. **Only touch your own folder.** Everything outside `projects/pod-07/` belongs to someone else.
2. **Never upload passwords or API keys.**
3. **Nothing over 5 MB.** Big datasets and model files do not belong here. Link to them instead.
4. **Plain file names.** Lowercase, no spaces. `field-photo.jpg`, not `Field Photo (1).JPG`.
5. **Ask before deleting anything you did not create.**

## Something went wrong

See [HELP.md](HELP.md).

Worth knowing: **you cannot break the website.** Every project is a separate folder of plain
files. A mistake in your page shows up on your page and nowhere else. Every version of every file
is saved forever and can be put back.

## For maintainers

See [FOR-MAINTAINERS.md](FOR-MAINTAINERS.md).
