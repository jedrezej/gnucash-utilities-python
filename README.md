# gnucash-utilities-python

Python scripts leveraging the GnuCash API to help with some tedious tasks.

Prerequisites:

For ubuntu: `apt-get install gnucash python3-gnucash python3-loguru`

Note the python API will not work without a native gnucash installation

Other setups: you are on your own.

## creating a new year's gnucash file from the previous year's file

`create_new_year_including_opening_transactions.py`

When you use one gnucash file per year, this can create the new year's
file, retaining the learned automatic transaction assignment rules.

Thoroughly check the assumptions the script makes! Extend
as you need!

