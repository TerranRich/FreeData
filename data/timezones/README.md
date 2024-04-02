# Time Zones

This dataset lists each time zone name along with its offset and associated country. For the SQL dataset, the offset is stored as two values: an integer (whole number) offset, along with a digit representing the number of quarter-hour segments to add to the offset hour. So, for example, if the `utc_offset` is `-9` and the `added_quarter_hour` is `3`, that would correspond to a final offset of **-9:45**. This is a bit more efficient to store than a string (e.g. `"-9:45"`) or a decimal (e.g. `-9.75`), and can be easily parsed.

Select by data format:
* [CSV](timezones.csv)
* [JSON](timezones.json)
* [MySQL](timezones.sql)
* [XLSX (Excel)](timezones.xlsx)
