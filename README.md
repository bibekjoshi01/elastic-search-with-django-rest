# Elastic Searching with django rest

1. Download code and open in your preferred code editor
2. Create a Virtual Environment. If you are using Visual Studio Code, open the terminal and type:

```
python -m venv venv
```

3. Activate venv

```
.venv\Scripts\activate
```

4. Now install the dependencies

```
pip install -r requirements.txt
```

5. You will need docker for this project. Go ahead and install docker desktop if you havent already done so

6. Start the new containers

```
docker-compose up -d
```

```
python manage.py demo-fixtures
```

7. Start the server and check it out

```
python manage.py runsever
```


### To Perform Product Search 
    http://127.0.0.1:8000/api/search/<str:query>/

    
