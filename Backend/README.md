# Make your api key 
    from https://openweathermap.org/api/one-call-api

## To set up the dependencies follow:
```
sudo apt install python3-venv[I am using Ubuntu need to install first]
python3 -m venv venv
source venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## To run the backend server:

```
python app.py
```

## Check Open API V3 auto generated EndPoint

Open: http://localhost:8000/apidocs/

## To run the integration battery of tests:

```
python test_app.py
```


