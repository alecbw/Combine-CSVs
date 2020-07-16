# Combine_CSVs
A quick CLI to concatenate CSVs or TXT files into one CSV. Supports mismatched columns and partial data. Requires minimal technical background to use.

### Usage

To combine multiple .csv files:
```py
python3 combine_files.py -type csv -output_filename custom_filename.csv
```

To combine multiple .json files:
```py
python3 combine_files.py -type json  -output_filename custom_filename.csv 
```

To combine multiple .txt files (the following shows a permutation of every available option):
```py
python3 combine_files.py -type txt -engine python -output_filename custom_filename.csv -separator " " -break_on_errors True
```
