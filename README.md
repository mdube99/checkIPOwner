# checkIPOwner


Requires `python-whois` library, you can install via:

```
pip install -r requirements.txt
```

Example usage:

```bash
./checkIPOwner -F file.txt
```

The above command would output the list of IP addresses along with the WhoIS into `file_list.txt`. This file will contain the IP Address, IP Owner, and IP registrar.
