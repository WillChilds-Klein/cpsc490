# cpsc490
#### Will Childs-Klein
#### Spring '15

## prospectus/
This directory contains the course project's prospectus. Its source is a `.md` file, which is compiled to a `.pdf` (after being converted interstitially to LaTeX) with the included `./build` script via [pandoc](http://johnmacfarlane.net/pandoc/) (installation instructions [here](http://johnmacfarlane.net/pandoc/installing.html)). It should be noted that the prospectus references `.png` images in the `prospectus/diagrams/` subdirectory via a relative path from the `/prospectus` directory. The build script has some copy instructions unique to my computer, so i suggest that you instead build it manually from the command line with the following command:
    
    $ pandoc -o cpsc490-prospectus.pdf cpsc490-prospectus.md

