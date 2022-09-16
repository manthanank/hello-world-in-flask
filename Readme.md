# Hello World In Flask

## **Virtual environments**

### **Create an environment :**

```jsx
//In Windows
> mkdir myproject
> cd myproject
> py -3 -m venv venv
```

### **Activate the environment :**

```jsx
> venv\Scripts\activate
```

### Install Flask :

```jsx
pip install Flask
```

## Hello World! in Flask :

```jsx
//save as hello.py
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<p>Hello, World!</p>"
```

### Run the application:

```jsx
flask --app hello run
```