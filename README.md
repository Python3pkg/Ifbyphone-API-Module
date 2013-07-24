Ifbyphone API Module
====================
 
This is a comprehensive API client that provides a
convenient interface to Ifbyphone's REST API.

Installation:
------------

You can quickly install this moduel using easy_install:

```bash
    easy_install Ifbyphone-API-Module
```

Usage:
------

```python
from Ifbyphone import IfbyphoneClient

c = IfbyphoneClient('YOUR API KEY')

c.clicktovoicemail._call(vmail_box_id=26271, 
                         phone_to_call=7739777935)
```

```python
from Ifbyphone import IfbyphoneClient

c = IfbyphoneClient('YOUR API KEY')

c.sms.send(from_=1112223333, 
           to=3334445555,
           message='Test message')
```

Additional Documentation:
-------------------------

https://secure.ifbyphone.com/developers.php
              
License:
--------
MIT