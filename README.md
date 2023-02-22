# forms
Basic forms using Django


## steps to activate server
```
cd forms
python manage.py runserver
```

Virtualenv can also be used

## Hosting using ngrok
1. Signup in ngrok and get the token<br>
2. Install ngrok executable in `/forms` dir<br>
3. start ngrok with the following <br>
```batchfile
ngrok config add-authtoken <TOKEN>
ngrok http 8000
```
Note python by default uses port 8000<br>
4. After firing up ngrok ngrok will return unique tunneling URL<br>
5. Add the tunneling URL in allowed host and restart server<br>