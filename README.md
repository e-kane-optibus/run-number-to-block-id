# trip-run-number-to-block-id

## Purpose
This script replaces all values in the run_number column with the corresponding values in the block_id column of runcut.txt.

## Usage
Tested with Python 3.9.<br>
```python run-to-block.py runcut.txt``` <br>
Adjusted file is exported to the current directory as runcut_syncro.txt, after which the file name can be updated and added to the feed's .zip file to replace the original runcut.txt. 
