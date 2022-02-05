# file_dissector

## What this project do

### 1. Attribute of the file
This project is for studying different kinds of file and its attribute.

As file is uploaded, installed function will dissect the file to gather information of the file.
Expected information follows,

- Extension of the input file.
- Size of the file.
- How it is encoded.
- Extesion's metadata.(This porject will customize its template)
- If it is a image, how many channels does it has( RGB? WB? ).
- If it is a text, how many characters does it has.
- ...and so on.

#### Different extension, different outcome(visable result)
Each extension or foramt of the file will have different kind of metadata.

If it is a text data like ' .csv ', it will have length of the file, size of the file,..., as a dissected result.
But it doesn't require information about how many channles it has.(Because its format is not image!)

### 2. Converting one file format to another
In case of famous Python library, 'pandas', using function 'to_excel','read_excel','to_csv' can let us converting
different file format to another.
More complicated file format would have more difficulty in converting.
In this topic, the subject is to figuring out how converting is processed. 
