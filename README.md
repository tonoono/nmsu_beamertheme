# nmsu_beamertheme

This is a New Mexico State University latex-beamer theme.

I've used the city naming scheme for this theme, LasCruces, where New Mexico State University main campus
is located.

## Installing a custom theme

#### Working directory
Copy the file *beamerthemeLasCruces.sty* to your working directory.

#### Not in working directory
If you are going to use the theme often, it is best to "install" it.  If my **$HOME** 
directory is **/home/antonio**, the path **/home/antonio/texmf/tex/latex/** must be
created if it doesn't already exist. If it exists, skip the first command.

To create the path use the following commands:
    
    mkdir -p ~/texmf/tex/latex
    cp beamerthemeLasCruces.sty ~/texmf/tex/latex/
    texhash


## Usage

Once the theme is installed, add the following lines at the top of your tex file:

    \documentclass{beamer}
    ...
    \usetheme{LasCruces}
    ...

### Custom content

Add the following lines to your tex file

    \newcommand{\UniName}{New Mexico State University}
    \newcommand{\UniDeptName}{Computer Science}

See lascruces_example.tex for more details.


### titlepage logos

I have included the option to have one or two logos on the title page. 

For one logo, the file `uni_logo.jpg` is expected. 

For two logos, the files `uni_logo.jpg` and `uni_dept_logo.jpg` are expected.


## Screenshots

![Title Page](http://www.cs.nmsu.edu/~aarredon/screenshots/lascruces_shot01.png "Title Page")

![Colored Boxes](http://www.cs.nmsu.edu/~aarredon/screenshots/lascruces_shot02.png "Regular Page")



