# The black-holes.org public site

This repo contains the [Jekyll](https://jekyllrb.com/) code responsible for creating the public
portion of the black-holes.org site.  Basically, this means that we can write pages for the site as
standard markdown, and it will be rendered for us to a nice, fancy website.  Currently, github
automatically does this rendering for us because it detects jekyll files in the `gh-pages` branch,
though it would also be possible to render manually via github actions if we need to use features
github doesn't enable by default.


## Writing your own posts

One of the goals of making this website more usable is to encourage SXS members to write entries
about their research for the site.  The two most recent entries show up on the homepage under
"Recent Research", along with brief synopses and links to the full description.

To write your own entry, just create a Pull Request on this repo, with a file as described below.

1. To get published, you *must*
   a. put the file in the `_posts` directory, and you *must*
   b. name the file starting with the date as `YYYY-MM-DD-awesome_file_name.md` (where you get to
      pick the awesome part of the name)

2. You also *must* add a section at the very start of the page that looks like this:
```yaml
---
layout: post
title:  "The title of my awesome research"
---
```
Again, you get to pick the title.  Try to keep it very short, to fit in its place on the homepage,
and maybe not so technical so that the public have a chance of understanding it.

3. After that top section, everything else is pretty much [standard
   markdown](https://github.github.com/gfm/).

4. The first paragraph will be used on the homepage to advertise this post, so think of this part as
   your [elevator pitch](https://en.wikipedia.org/wiki/Elevator_pitch).  Try to limit the jargon in
   this part, since it's the part that most non-scientists will see.  Try to keep it brief, but also
   include a little motivation and the most important conclusions.

5. The rest of the post can be as long as you like — though remember that this isn't the paper;
   long technical details should go in a paper.

6. If you need to include figures, PNG is best.  The files should be placed 



## To Do

1. Create menu automatically
