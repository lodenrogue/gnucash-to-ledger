# Gnucash to Ledger

Unzip Gnucash files and convert to ledger file format. Supports arbitrary decimal places.

## Install requirements

```
pip install -r requirements.txt
```

## How to run

The script takes a required gnucash file as the first argument and an optional output file. 
If no ouput is given the output will be redirected to stdout.
If a file already exists with the same name as output file nothing is written.

```
python gnucash2ledger.py gnucash_file.gnucash output
```

Original code source found here: https://gist.github.com/nonducor/ddc97e787810d52d067206a592a35ea7/
