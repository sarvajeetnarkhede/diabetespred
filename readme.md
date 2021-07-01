## Installation

__Go To Directory Where you have to install virtual Environment__

#### then,

```
pip3 install virtualenv
```
#### Now Create Virtual Environment
```
virtualenv venv
```

#### Activate Virtual Environment
> If your are using **vscode**, You will get a prompt that it has detected virtual environment

**_or just_**

```
venv\Scripts\activate
```

##### __*Once You have Activated Virtual Environment, You will see `(venv)` just before the path*__

#### Now to install all the packages, just

```
pip install -r requirements.txt
```
##### It will install all the required Packages

#### Now Run the following commands one by one
```
python manage.py migrate

python manage.py createsuperuser
```
> Enter the necessary details...(username & password remember)


#### DONE...
## `python manage.py runserver`
#### In Case of Errors
* Install the required python package
* `CTRL + Shift + R` for hard reload in Browser, if something goes wrong


