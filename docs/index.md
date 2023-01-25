# Team Docs

This documentation tool is created so that the co-operation can be more efficient, and the knowledge can be preserved and re-used.    
We can keep track of all our works here in a centralized place, and link contents to different places such as team drive, google docs etc.      
Can be deployed on our own server and managed through git. 

## Basics
* MarkDown is used to edit the pages.
* To facilitate the colaboration on coding, the overall frameworks and a set of interfaces should be defined on the initiation.
* Each part in one project page should be kept as reusable as possible to be referrable in other projects.


## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
* See [MkDocs](https://www.mkdocs.org/getting-started/) for more commands.

## Project layout
For different projects, please see [Projects](./projects/project1.md) for its own details.
 
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        projects/project1.md # The page is about the projects finished or ongoing 
        projects/project2.md # The page is about the projects finished or ongoing 
        
