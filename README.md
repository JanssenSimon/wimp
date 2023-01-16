# WIMP
Dynamic Static Website generator using inotify and pandoc to convert Markdown
files into html pages.

My goal with this software is to make it self-sufficient.

## DEPENDENCIES:
- linux (using systemd, sudo, and some posix compliant shell)
- pandoc
- inotify-tools

## INSTRUCTIONS
0. Make wimp script executable (`chmod +x wimp`)
1. Run `wimp init`
2. Put your markdown files in `src/`
3. Point a webserver to `public/` if you want to
4. ???
5. Profit.

## POSIX
This shell script is supposed to be posix compliant; it not being so is a bug.
Feel free to report any bugs you find.
