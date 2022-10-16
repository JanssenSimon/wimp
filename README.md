# WIMP
Dynamic Static Website generator using inotify and pandoc to convert Markdown
files into html pages.

## DEPENDENCIES:
- linux (using systemd)
- posix compliant shell (some other shells work)
- pandoc
- inotify-tools

## INSTRUCTIONS
0. Make wimp script executable (`chmod +x wimp`)
1. Run wimp
2. Put your markdown files in `src/` and your style containing html files in `includes/`
3. Point a webserver to `public/`
4. ???
5. Profit.


## What's in the works?
1. Figure out how to run wimp watch on startup using systemd.
2. Have the wimp delete html files when their corresponding markdown file is deleted
   from `src/`.
3. Make names of folders configurable using variables;
   also add a config option for compilation of all files.
4. Support the following flags for pandoc:
    - --template
    - -V
    - --css
