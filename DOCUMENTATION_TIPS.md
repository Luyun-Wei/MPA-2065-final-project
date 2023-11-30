# Code Documentation and Organization Tips

Documentation allows developers to quickly understand what the code does and how to use it.

Markdown files are all the `.md` files and here is some help with some [Basic Syntax](https://www.markdownguide.org/basic-syntax/).

## Organization of Files
### `README.md`

A `README.md` file is the first file a reader encounters when browsing a repository. It's used to provide orientation, 
especially for first-time users. Replace the main `README.md` file with your own! 

Here is a handy-dandy website to help generate your `README.md` file: [readme.so](https://readme.so/). Some suggested
headers include:

```md
# Title
A brief description of what this project does and who it's for

## Installation
After we clone the directory, are there any additional steps?

## Usage/Examples
How to run the code?

## Results
Perhaps briefly talk about results here? Screenshots or images of plots would be nice too !

## Acknowledgements
Any additional acknowledgements or citations?

```

### `.gitignore`

A hidden files is a folder or file which filesystem utilities do not display by default when showing a directory listing.
A gitignore file specifies intentionally untracked files that Git should ignore.

### `images/`

Folder of images if needed.

### `data/`

Folder of raw data files. There is a `README.md` file in there. Use it as an opportunity to further explain your datasets.

### `results/`

Folder for an intermediary results files or final results