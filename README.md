
# Quick Starter Kit - Add Your Stay Static Site Sample!

You're invited and more than welcome to add new static site samples.
New tools always welcome!

The static site sample when done must include:

- Three (news) post pages
- One about page
- One index (front) page -- listing the latest posts and latest links (from a datafile e.g. `links.yml|toml|json|js`)


and looks like:

```
|   about.html
|   index.html
|
+---posts/
|       new-build-system.html
|       new-repo-maps.html
|       new-season.html
|
\---css/
        style.css
```

or

```
|   index.html
|
+---about/
|       index.html
|
+---css/
|       style.css
|
\---post/
    +---new-build-system/
    |       index.html
    |
    +---new-repo-maps/
    |       index.html
    |
    \---new-season/
            index.html
```

or

```
|   about.html
|   index.html
|
+---2014/
|     new-repo-maps.html
|     new-build-system.html
|
+---2015/
|     new-season.html
|
\---css/
        style.css
```

depending on your static (web)site builder convention.


It's best to browse the live samples
and some source samples to see what's included.


To help you get started you will find in this quick starter kit:

### Three news posts

in Markdown with front matter (meta data) e.g. a title and a date.

- /posts/new-build-system.md
- /posts/new-repo-maps.md
- /posts/new-season.md

Note: Feel free to add new front matter (meta data) or change from YAML to TOML
to JSON or what you static (web)site builder requires / prefers.

### One about page

in Markdown again

- /about.md

Note: Because it's a page (not a post) there's
no date in the front matter (meta data). Please add your tools title
and use the folder and filenames for your (web)site builder tool.


### One simple stylesheets

in plain vanilla simple styles in a single file

- /style.css


### Three building blocks (includes/partials)

a simple footer (no need change anything - just links to stay static site)
and a header. In the header change the site title to
"Nicola Stay Static Sample" or
"Metalsmith (+Handlebars) Stay Static Sample"
or something. And a "Fork me a GitHub" ribbon.

- /includes/footer.html
- /includes/header.html
- /includes/github.html


### One datafile (for links/bookmarks) in many flavors

a datafile listing links/booksmarks (title and url) in many
flavors e.g. yaml, toml, json, js. Use your flavor of choice
or if missing add/use your own.


That's it. Good luck.


## Questions? Comments?

Ping us [@viennahtml]() on twitter or send questions or comments
to the [wwwmake mailing list/forum](https://groups.google.com/group/wwwmake).  
