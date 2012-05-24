# Project templates
A collection of project templates. Each template serve as sort of starting point for specific kind of project.

## Usage

Lets say you want to write a latex article. If you do not have a local copy of this repository,
you should make one, suppose that we want to store it in `~/Repos/project-templates`:

    git clone git://github.com/liborw/binfiles.git ~/Repos/project-templates
    cd ~/Repos/project-templates
    git submodule init
    git submodule update

then `cd` to the path where you want to make the new project and copy the `latex-article` project template:

    cp -L ~/Repos/project-templates/latex-article new-article

and you are ready to go. The `-L` option is crucial as some of the files in the template are symlinks to other
templates or submodules.

## Already in the collection

    

## Contributing
Any kind of feedback and contribution is welcome.
