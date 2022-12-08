# Introductory course - Setup and basic workflow

Here you will learn all the basics to get you started with the web course.

## Steps

1. Install all necessary software:

   - (Visual Studio Code)[https://code.visualstudio.com/]
   - (Git)[https://git-scm.com/]

2. Let's get this repo to play around with it

   - Clone this repo:
     - Create a folder in the root of your drive, call it something short like `learning`, e.g. `C:\learning`, `/learning`
     - Click the green button in github
       ![Clone the repo](images/CloneRepo.png 'Clone Repo')
     - Copy the URL `CTRL+C` / `CMD+C`
     - Open the terminal and type the following:
     - `cd /c/learning`(git bash) / `cd /learning`(Linux/Mac) / `cd C:\learning`(cmd/cmder) (Navigate to the newly created folder)
     - `git clone paste_your_url_here_(CTRL-V)` (actually clone the repo)
     - `ls -al` (list all files and folders in the current folder)
     - `cd name_of_the_newly_created_folder` (navigate to the newly created folder (just cloned, is named like the repo))
     - `code .` (open Visual Studio Code to the current folder )

3. Install the recommended plugins
   - just click the `Install` button on the message in the bottom right of Visual Studio Code
     ![Install recommended Plugins](images/RecommendedPlugins.png 'How to install recommended plugins')

## Keyboard shortcut cheatsheet

1. Copy: `CTRL+C` / `CMD+C`
2. Paste: `CTRL+V` / `CMD+V`
3. Undo: `CTRL+Z` / `CMD+Z`
4. Redo: `CTRL+SHIFT+Z` / `CMD+SHIFT+Z` sometimes `CTRL+Y`
5. Save: `CTRL+S` / `CMD+S`
6. Open new tab in browser: `CTRL+T` / `CMD+T`
7. Reopen last closed tab in browser: `CTRL+SHIFT+T` / `CMD+SHIFT+T`
8. Open dev tools in browser: `CTRL+SHIFT+I` or `F12` / `CMD+OPTION+I`

## Command line cheatsheet

1. Navigate: `cd <path>`
   - `<path>` can be any valid path
   - `<path>` can be autocompleted by typing a few letters and then hitting `Tab` on the keyboard
2. Change drive letter: `D:`, `C:`, `E:` (command prompt), `cd /c/`, `cd /d/` (git bash), this is not necessary on a Mac or Linux PC
3. List contents of folder: `ls` (git bash, Mac, Linux), `dir` (command prompt)
4. Clear the console: `clear` or hit `CTRL+L`
5. Stop currently executing program: hit `CTRL+C`
6. Close Vim: `ESC` then `:wq` (w is for saving the file, if you don't want to save `:q` is enough or `:q!` to quit forcibly (if there are changes you don't want to save))
7. Find the Home dir: type `cd ~`, you are now in your home dir.
