# Something went wrong

In order of how often it actually happens.

## My change is not on the website

Wait two minutes and refresh. Publishing is not instant.

Still nothing? Your browser is showing you a saved copy. Press **Ctrl+Shift+R**, or
**Cmd+Shift+R** on a Mac.

## My picture does not appear

Three things to check, in this order.

1. **Did you upload it?** Open your `images` folder and look. If it is not in the list, it is not
   there.
2. **Does the name match exactly?** `Photo.JPG` and `photo.jpg` are different files. Copy the name
   from the folder listing and paste it into `index.html`.
3. **Is the line right?** It has to look like this:

   ```html
   <img src="images/photo.jpg" alt="Farmers in the field">
   ```

## My page looks broken, everything is one big heading

You deleted a closing tag. Every `<h1>` needs a `</h1>`, every `<p>` needs a `</p>`.

Look at the place you edited last. The closing tag has a slash in it. If you cannot spot it, use
**History** to go back, see below.

## I want to undo what I did

Nothing is ever lost. Every version of every file is saved.

Open the file, click **History** at the top right, find the version from before the mistake, click
it, then click the **...** menu and choose **Revert changes**.

If you cannot find it, ask a maintainer and tell them roughly when you made the change. This is
normal and happens to everyone.

## I deleted a file by accident

Same answer as above. It is recoverable. Tell a maintainer.

## GitHub says there is a conflict

Two people edited the same file at the same time. Do not try to fix it. Tell a maintainer, it takes
them a minute.

You avoid this entirely by keeping to your own folder.

## My page has no styling at all, just black text

The link to your stylesheet is broken. Check that this line is still in the `<head>` of your
`index.html`:

```html
<link rel="stylesheet" href="style.css">
```

and that `style.css` is still in your folder.

## I still cannot work it out

Click **Issues** at the top of the repository, then **New issue**. Say what you clicked and what
happened. Screenshots help.
