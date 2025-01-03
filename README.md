# Marksheet Generator

## Marksheet Features:
- web display
- printable from the web
- bulk pdf print
- storage
- verification

## Subjectwise Marks

JSON Fields for the individual subjects:

| Key         | Sample Value | Description |
|-------------|--------------|-------------|
| code        | COD          | Subject Code
| name        | Mathematics  | Name of the subject
| thfm        | 100          | Theory Full Marks
| thpm        | 40           | Theory Pass Marks
| prfm        | 20           | Practical Full Marks
| prpm        | 10           | Practical Pass Marks
| thmo        | 85           | Theory Marks Obtained
| prmo        | 10           | Practical Marks Obtained
| gpa         | 3.8          | Grade Point Avegrage
| grade       | A            | Letter Grade
| percentage  | 85.00        | Percentage
| remarks     | Pass         | Remarks


## Marksheet Generation

```
python code/marksheet.py
```

It produces pdfs/combined.pdf pages

## @todo
- Remove white background from css and make pages transparent.


## Media Types
| Type | Description
|------|-------------
|.pdf  | 
|.png  |-------------
|.svg  |-------------
|.epgz |-------------
|.al4  |-------------