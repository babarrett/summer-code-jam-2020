![Proud Puffins](djangoProject/static/images/Proud_Puffin_banner.png)
# Proud Puffins

This is the default README of your team's project. Please replace this by a README with more information on your project. At the very least, your README should contain information on how to set-up and run your project.

We be Puffins, and we be proud!
* ergomacros
* ImaMoonky
* PDXCardinal78
* rr
* XPOjabar


## Dev stuff

### [Populating profiles database](https://docs.djangoproject.com/en/3.0/howto/initial-data/)
- Add new entries into `earlydating/fixtures/profiles.json`
- Run ```python3 manage.py makemigrations```
- Run ```python3 manage.py migrate```
- Run ```python3 manage.py loaddata users.json```
- Run ```python3 manage.py loaddata profiles.json``` (First users.json then profiles.json)
- Run server :)


### Code organisation

- Dev dependencies go in `requirements-dev.txt`
- Normal dependencies go in `requirements.txt`


## [MIT license](../LICENSE)

## [Credits and sources](Credits%20and%20sources.md)

