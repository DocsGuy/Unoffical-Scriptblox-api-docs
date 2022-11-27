# Hey !
# These are the unoffical scriptblox api docs
- Have fun reading / using the scriptblox api.

# Note:
- One note tho. Everything that I put in brackets and that I not like put any comment to it (e.g a comment with header) to it then it's the json data.
- If you try to request something and it doesn't work try adding this authorization to the headers 
- Example how to use the json data (in py):
```python
import requests
jsonData = {"email":"testmail@gmail.com"}
headers = {"Authorization":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzODM5YjA3ZTk4MjU1MjRkMDFjOTNkZiIsInJlc2V0UGFzc3dvcmQiOnRydWUsImVtYWlsIjoic2l4b2JlMTA4OUBydWJlc2hpLmNvbSIsImlhdCI6MTY2OTU3MTA1MCwiZXhwIjoxNjY5NTcxNjUwfQ.JHJ0-rBoaum0ZTU5M2rls2XmCh2uZXMXrPCg4VfLHmE"} # this a test token so don't evne try to use it
requests.post(url="https://scriptblox.com/api/user/reset-password",json=jsonData,headers=headers)
```
