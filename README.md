FastQ2A
=======

A simple and quick FastQ to FastA converter with reverse complement options.
Use the --append option to add a string to each sequence header.

Based on KSeq library from Heng Li.

Installation
------------

Clone this repository and run make.

Usage
-----

    FastQ2A sequences.fastq > sequences.fasta
    FastQ2A sequences.fastq --rev > reverse_complement.fasta
    FastQ2A sequences.fasta --append /1 > forward_sequences.fasta
    FastQ2A sequences.fasta --append /2 --rev > reverse_sequences.fasta

License
-------

     Permission is hereby granted, free of charge, to any person obtaining
     a copy of this software and associated documentation files (the
     "Software"), to deal in the Software without restriction, including
     without limitation the rights to use, copy, modify, merge, publish,
     distribute, sublicense, and/or sell copies of the Software, and to
     permit persons to whom the Software is furnished to do so, subject to
     the following conditions:

     The above copyright notice and this permission notice shall be
     included in all copies or substantial portions of the Software.

     THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
     EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
     MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
     NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
     BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN
     ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
     CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
     SOFTWARE.

Copyright
---------

Copyright (c) 2012 Francesco Strozzi

