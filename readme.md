<!--
Market: SF
-->

# Command line lab

## Introduction

> ***Note:*** *This can be a pair programming activity or done independently.*


Developing web apps requires a degree of comfort navigating and interacting with your operating system through the command line, and similar to how you'll be practicing writing and running Ruby and JavaScript later in the course, we'll be practicing creating, modifying, and moving files and folders in your terminal to get you practicing Unix commands.

For this lab, you're going to create files and folders to organize your favorite books, movies, and music - then, you're going to reorganize them.

Be sure to use the cheatsheets in the "Additional Resources" section in case you get stuck.

> ***Note:*** _The specific authors, bands and names here are just examples -- use your own favorites! Seriously!_

## Exercise

#### Requirements

- From your root directory, create a folder called "my-favorite-things"; you'll use that folder to do the exercises below

- Organize your favorite books

  - in the "my-favorite-things" folder, create a folder called "books"
  - create a folder in books named after your favorite author (e.g. "mark-twain", or "john-grisham", but avoid spaces!)
  - create files named after some of the author's books in the author's folder
  - open the books folder in atom/sublime
  - edit each file to put a brief description of the book


- Organize your favorite movies

  - in the "my-favorite-things" folder, create a folder called "movies"
  - create a folder in movies named after your favorite actor
  - create a folder in the actor folder named after the actor's breakthrough movie
  - create a text file named after the actor's character in the breakthrough movie in the top level "movies" directory
  - move the text file to the breakthrough movie's folder
  - look back at Sublime/Atom and edit that text file with a description of the character's role in the movie


- Organize your favorite music

  - in the my-favorite-things folder, create a folder called "music"
  - move into the "music folder"
  - create a folder called "disco"
  - create a text file in "disco" called "ymca"
  - delete the "disco" folder
  - create a folder called "creed"
  - delete the "creed" folder
  - create folders called "one-direction", "the-strokes", and "rihanna"
  - create a text file in "one-direction" called "what-makes-you-beautiful.txt"
  - make two copies "what-makes-you-beautiful.txt" - one into "the-strokes" and one into "rihanna" and rename those files with songs by those artists


- Reorganize _everything_

  - in the my-favorite-things folder, create a folder called "media"
  - move "books", "movies", and "music" into the "media" folder


- Organize the top music, movies, and books of 2015

  - move to the my-favorite-things folder and copy the "media" folder, then, rename it "2015-media"
  - in the 2015-media folder, rename each folder to have "2015-" before the title
  - delete the contents of "2015-music", "2015-movies", and "2015-books"
  - create a file called "top-ten-movies.html" in "2015-movies"
  - create a file called "top-ten-songs.html" in "2015-music"
  - create a file called "top-ten-books.html" in "2015-books"
  - create an ordered list - using HTML! - of the top 10 movies, songs, and books in each of the appropriate files

**Bonus**

- Look through the additional resources and do the following

  - look at the top/bottom 10 lines of each file
  - figure out how search through a file from the command line - without opening the file - for a string of text
  - explore some more bash in their [docs](https://www.gnu.org/software/bash/manual/bashref.html)

#### Starter code

No starter code needed for this lab!

#### Deliverable

Add your `my-favorite-things` directory to your own fork of this repo and push it to your fork! Like so:

- Click 'Fork' on this github page. You will be redirected to your fork
- Clone the repo to your local machine by copying the url to the repo, and..
- enter `git clone https://github.com/wdi-29/THE-REPO-NAME.git` (only with the real url)
- Make your changes
- `git add -A`
- `git commit -m "some commit message"`
- `git push origin master`

You can open up your "my-favorite-things" directory in Sublime/Atom, to track your progress. You can also use `tree`.

Here's a look at what your files/folders should look like after each big step in the exercise:

- After "Organize your favorite books":

![](https://i.imgur.com/ySAjOeO.png)

- After "Organize your favorite movies":

![](https://i.imgur.com/h8WcyVE.png)

- After "Organize your favorite music":

![](https://i.imgur.com/T4E3eAg.png)

- After "Reorganize _everything_"

![](https://i.imgur.com/GEoIps9.png)

- After "Organize the top music, movies, and books of 2015"

![](https://i.imgur.com/EM2m8mL.png)


## Additional Resources

- A list of [CLI Shortcuts](https://gist.github.com/alexpchin/01caa027b825d5f98871)
- An awesome Unix command [cheatsheet](https://github.com/veltman/clmystery/blob/master/cheatsheet.md)
