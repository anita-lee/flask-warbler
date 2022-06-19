# Warbler

## Description
Warbler is a Twitter clone built using Python, Flask, and PostgreSQL. Authentication and Authorization routes are built in.  One to Many Database Relationships have been mapped to keep track of likes, follows, and messages.  

<span> <img width="35%" alt="warbler_home" src="https://user-images.githubusercontent.com/72634901/174489823-3496cbfe-1090-41c7-874d-416e69fa29de.png">
<img width="60%" alt="warbler_users" src="https://user-images.githubusercontent.com/72634901/174490190-b32278db-1a53-430f-ad94-dc02ea8d900f.png"> </span>

## Demo
[https://warbler-demo-8888.herokuapp.com/](https://warbler-demo-8888.herokuapp.com/)

[https://warbler-demo-8888.herokuapp.com/users](https://warbler-demo-8888.herokuapp.com/)

## Getting Started

### Installing Dependencies

```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip3 install -r requirements.txt
```

### Running the app

To run the app, first run the `seed.py` file directly to create the database tables:

```
$ python3 seed.py
```

You only need to do this once, unless you change your model definitions.

Then run the app itself:

```
$ flask run -p 5001
```

Visit [http://localhost:5001/](http://localhost:5001/) in your browser to see the results.
`
## Contributions

* Create database using Flask-SQLAlchemy
* Create forms using Flask-WTF
* Backend server routes
* Wrote unit and integration tests

## Future

1. More Testing
2. Allow Private Accounts
3. Add Admin Users
4. User Blocking
5. Direct Messages

## Acknowledgments

Rithm School

