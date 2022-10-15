# WIMP
Dynamic Static Website generator using inotify and pandoc to convert Markdown
files into html pages.

## DEPENDENCIES:
1. Linux (using systemd)
2. Posix compliant shell (bash, dash work)
3. pandoc
4. inotify-tools

## INSTRUCTIONS
0. If not already done, make wimp script executable
1. run wimp
2. put your markdown files in src/ and your style containing html files in includes/
3. point a webserver to public/
4. ???
5. profit.


## What's in the works?
1. support the following flags for pandoc:
  - --template
  - -V
  - --css
2. make it so that html files are sent into public
   at the same time, rename so that .html instead of .md.html
3. figure out how to run on startup or something when initializing
   use systemd to make it work
4. make names of folders and things configurable using variables
