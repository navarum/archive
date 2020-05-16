This tarball is downloaded from http://sgrep.sourceforge.net/

> Introduction

> Sgrep (sorted grep) searches sorted input files for lines that match a search key and outputs the matching lines. When searching large files sgrep is much faster than traditional Unix grep, but with significant restrictions.

   > All input files must be sorted regular files.
   > The sort key must start at the beginning of the line.
   > The search key matches only at the beginning of the line.
   > No regular expression support.

> Sgrep uses a binary search algorithm, which is very fast, but requires sorted input. Each iteration of the search eliminates half of the remaining input. In other words, doubling the size of the file adds just one iteration.


