# merey_kamila_SE-2010

## Title
This assignment is about tokens

### Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [License](#lisense)

---

## Installation

* ### Create a virtual environment:
$ virtualenv env
* ### Activate a virtual environment:
For Windows:
env\Scripts\activate

For Mac OS:
source venv/bin/activate

* ### Flask
$ pip install flask

* ### SQLAlchemy
This command will download the latest released version of SQLAlchemy from the Python Cheese Shop and install it to your system.
$ pip install SQLAlchemy

In order to install the latest prerelease version, such as 1.4.0b1, pip requires that the --pre flag be used:
$ pip install --pre SQLAlchemy

* ### pyjwt
$ pip install pyjwt
* ### PostgreSQL Database [Download](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)



[Back To The Top](#merey_kamila_SE-2010)

## Usage

```python
from flask import Flask, render_template
from flask import request
from flask.json import jsonify
import jwt
from flask_sqlalchemy import SQLAlchemy
import psycopg2
```
[Back To The Top](#merey_kamila_SE-2010)
## Examples
```html
Datas:
login:Merey password:123asd
login:Kami  password:kami45
login:Balzy password:b123

```
[Back To The Top](#merey_kamila_SE-2010)

## License

MIT License

Copyright (c) 2021 Overexm

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#merey_kamila_SE-2010)

