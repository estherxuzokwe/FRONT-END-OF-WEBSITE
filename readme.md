# Overview
* All files import styles.css which contains base styles for all pages like text colour and default tag styling (h1, h2, etc).
* All files contain the navigation bar which is a horizontal flexbox inside a `nav` tag. This contains `a` tags that link to the other pages on the site.
* All pages contain the profile section which is an `img` tag with associated heading tags. The `img` tag uses the `.profile-pic` css class to round the image and give it a subtle border.
* Within each page the main sections are divided up semantically using the `section` tag.
* Most pages use icons taken from [https://heroicons.com](heroicons) which are rended inline using `svg` tags with a touch of css styling (see `.icon` and `.icon-small`) for size and colour.
* The maximum content width is 600pt (see `.content`) to ensure the text is always legible.


# Index.html
* The contact section uses `a` tags for linking. It uses the `mailto:` prefix for the email address. All `a` tags on this page use the `title` attribute for accessibility.
* The profile picture contains the `alt` attribute for accessibility (for screen-readers).

# Experience.html
* This page uses a two-column layout achieved with a css horizontal flexbox (see `.hstack`, `.col2`, `.ivstack-col`, and `.iv-stack`).

# Skills.html
Nothing noteworthy yet.

# Blog.html
* The *new post* button uses a lot of styling (see `post-button` in blog.css). It takes advantage of text transforms, letter spacing, font weight, and shadows. It also has a custom hover state to show the user it's clearly a button (see `.post-button:hover`.)

# Login.html
* This page contains a simple styled form using the `form` and `input` tags.
* The `input` tags use HTML input validation, using the `required` and `minLength` fields where applicable.
* The form inputs use the correct type of the input so the email field validates an email and the password field transforms the text into dots.