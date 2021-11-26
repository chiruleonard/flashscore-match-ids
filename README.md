# Python script to scrape Flashscore match IDs

Python v3.9

## Scrape match IDs from main page
```python .\match_ids.py --help```

Usage: ```match_ids.py [-h] --days DAYS --email EMAIL --password PASSWORD --format FORMAT``` <br>

optional arguments: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -h, --help            show this help message and exit <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -d DAYS, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --days DAYS &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Number of days before <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -e EMAIL, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --email EMAIL &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Email for login <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -p PASSWORD, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --password PASSWORD &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Password for login <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -f FORMAT, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --format FORMAT &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Format data <br>

Example: ```python .\match_ids.py --days 1 --email 'chiru.leonard@gmail.com' --password 'Leopard1986@' --format 'json'```
