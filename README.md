[//]: # (Markdown: dillinger.io/ shows a nice example of Markdown commands with a viewer.)
[//]: # (Comments in Markdown: http://stackoverflow.com/questions/4823468/comments-in-markdown)
[//]: # (C++ Project Structure: http://hiltmon.com/blog/2013/07/03/a-simple-c-plus-plus-project-structure/)
[//]: # (C++ Library Creation: http://www.adp-gmbh.ch/cpp/gcc/create_lib.html)

# 2D Binary Matrix Visualization

This Perl script produces a 2D graphical representation of a binary matrix.

### Installation

```sh
$ git clone git@github.com:jcasse/2D-matrix-viz.git
$ export PATH=$PATH:PREFIX/2D-matrix-viz/src
```
where PREFIX is the current directory from which git clone was executed.


### Usage

```sh
$ txt2pgm < <binary_matirx_file> > <output_file.pgm>
```
Example data included in the data directory:
```sh
$ cd 2D-matrix-viz/data
$ txt2pgm < blocked_matrix.txt > blocked_matrix.pgm
```
To view the output:
```sh
$ eog blocked_matrix.pgm
```

License
----

[//]: # "A short snippet describing the license (MIT, Apache, etc.)"

[//]: # (http://choosealicense.com/)

Copyright (C) 2011 Juan Casse

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
