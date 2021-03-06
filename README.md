# Kaitai Struct: visualizer

This is a simple visualizer for [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct) project.

Kaitai Struct is a declarative language used for describe various
binary data structures, laid out in files or in memory: i.e. binary
file formats, network stream packet formats, etc.

The main idea is that a particular format is described in Kaitai
Struct language (`.ksy` files) only once and then can be compiled with
this compiler into source files in one of the supported programming
languages. These modules will include a generated code for a parser
that can read described data structure from a file / stream and give
access to it in a nice, easy-to-comprehend API.

Please refer to [documentation in Kaitai Struct project](https://github.com/kaitai-io/kaitai_struct)
for details on `.ksy` files and general usage patterns.

## Downloading and installing

### Generic

KS visualizer is written in Ruby and is available as .gem package. 

### Source code

If you're interested in developing the visualizer itself, you can check
out source code in repository:

    git clone https://github.com/kaitai-io/kaitai_struct_visualizer

## Usage

`ksv <binary-file> <ksy-file>...`

## Licensing

Kaitai Struct visualizer itself is copyright (C) 2015-2016 Kaitai
Project.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or (at
your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Note that it applies only to compiler itself, not `.ksy` input files
that one supplies in normal process of compilation, nor to compiler's
output files — that consitutes normal usage process and you obviously
keep copyright to both.
