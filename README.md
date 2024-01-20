# bd-filter_1col

### Installation using conda:
``` conda install -c molinerislab filter_1col ``` 

### Description:
Bioinformatics and data analysis power tool to filter a table based on a single column (more efficient and less error prone than grep -f).

### Usage and options:
```
filter_1col [-i] [-v] [-w] [-s SEPARATOR] COL_NUM filter_file < input_file

Filter input_file based on a filter_file that acts on the column COL_NUM (filter_file must be a single column file).
        -i ignore case
        -v invert the filter: in output are printed lines that do not have in COL_NUM an element present in filter_file
        -w COL_NUM may have more than one field separed by ';', input rows are reported if at least one word is present in filter_file
        -s set the separator
        -f each row starting by '>' is always passed to the standard output
```
