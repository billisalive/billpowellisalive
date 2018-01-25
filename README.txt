Build with mkdocs 0.19.x

I needed to install the most recent version to get the config options I need.

pip install mkdocs --users

This is python, so watch the spacing carefully in mkdocs.yml

See custom_dir for theme modifications.

Many "mkdocs" elements are hidden in extra.css.

TO ADD A POST:

- CReate a new .md Markdown file under docs/. You can recreate the path using subdirs (e.g., put /blog/title as docs/blog/title.md
- The title is # title at the very top.
- If you want to add an offer at the bottom, manually copy it from blog/how-to-talk-to-a-rock.md for now.
- Publish with: make publish (see Makefile)
