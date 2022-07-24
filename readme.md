# nytecode #
- workspace for game and software development
- this is a tool made of parts and modules
## languages
- cplusplus is the core programming language of nytecode
- lua is the loyal servant for configuration and scipting
    - (TODO) nytecode uses own modified lua version though
## build
- "make" is the main way to build this project
- there are some commands for "make"
    - build - compile source into object and link object into binary
    - clean - delete binary and object files
    - start - build and run
    - again - clean and build
    - rerun - clean and build and run
    - setup - (TODO) download all resources and install the program
    - reset - (TODO) delete all resources and uninstall the program
    - print - output all of the information about the script
## layout
- local filesystem
    - all top-level folders have 3 characters long names
    - every folder has a specific purpose
        - bin - binary files - the result of linkage
        - obj - object files - the result of compillation
        - src - source files - the result of development
        - doc - documentation
        - rsc - resources like audio and images
        - lib - dependency projects and submodules
    - .git* - version control specific files
    - makefile - explained in the build section
    - license.md
    - readme.md this file
## workflow
- system version control - git only
    - work branch
        - source code modification, placeholder usage
        - can have "feature branches"
    - test branch
        - merged from work, testing for bugs, polishing
    - main branch
        - merged from test
        - default protected branch that others originate from
        - the cleanest history must be kept here
## info
- "nytecode" - pronounced as "naitkoud"
    - "nyte" means "enjoy" from Norwegian
        - but for this case it sounds like "byte"
    - "code" is the code that i write, as a developer
- i wanted to make it much bigger until i found suckless.org
    - support for 4-5 programming languages
    - multiple building systems and ide's
    - all of that is just overwhelming and unnecessary garbage
    - now it is more ide agnostic, minimal, cpp-written project
- i love neovim, i love cplusplus, i love pain
# endofile #
