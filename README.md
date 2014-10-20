explain
=======

Code comprehension toolset for big django projects, motivated by real problems in
comprehending a relatively big django code base with minimal documentation and no
original developer available. The goal is to provide useful scripts for explaining
different parts of the project and source code to developers new to a project or
part of it.

Currently, most of the scripts are written in bash and only tested on Ubuntu, but
may work on other *nix system. There is plan to rewrite the scripts in python after
the project has reached a usable state.


## Installation

In project's main directory, run:

    wget https://raw.githubusercontent.com/amiraliakbari/explain/master/explain
    chmod +x explain


## Usage

* `./explain fixtures` displays a list of distict fixture names in project, and a
  list of  all files associated with them.
