# Garbage 

`gb` is a lightweight trash utility intended to be a replacement for the dangerous `rm`. Other trash utilities are written in heavy interpreted languages that add unnecessary overhead to your lighning-fast workflow. `gb` intends to be a quicker alternative within your shell.

### Usage

`gb somefile.txt`
`gb --log 10`
`gb --restore ~/important/file.txt`

### TODO

This is not a complete utility. Some things that need to be added, improved, or fixed are as follows:
 - Robust searching, viewing, and restoring of trashed files
 - Ensure that permissions are preserved in all cases
