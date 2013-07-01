Ifbyphone API Module
====================
 
This is a minimalistic API client for Ifbyphone REST API

Usage:
------

```python

from client import IfbyphoneClient

c = IfbyphoneClient('YOUR API KEY')
c.clicktovoicemail._call(vmail_box_id=26271, 
                         phone_to_call=7739777935);
                 
```

```python

from client import IfbyphoneClient

c = IfbyphoneClient('YOUR API KEY')
c.sms.send_message(_from=1112223333, 
                   to=3334445555
                   message='Test message');
```
                 
