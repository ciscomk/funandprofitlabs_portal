# Fun and Profit labs Portal 2.0
Verison 2.0 of the portal used in the 'fun and (fake) profit' lab series at the [CiscoLive](https://www.ciscolive.com/global/) conference.

## Install instructions
*coming soon*

### Notes
Ran the following in OSX to setup virtualenv to reduce errors within vscode:
virtualenv venv
source venv/bin/activate
python venv/bin/pip install -r requirements.txt
python venv/bin/pip install pep8 pylint
deactivate

## To-do
~~Integrate spark~~

~~Update adminstrator's page (Mass-change lab number for all students)~~

* Fix routing (admin page - get rid of user count)~~
~~Fix 'refreshmoney' script so that it loads in portal page only~~
* Update portal aesthetic (header/footer, login form, user edit page)
~~Import all emails~~
* Double check emails
~~Use local fontawesome instead of CDN (CDN is too slow)~~
* Clean up configuration files for version control
* Upload to version control
* Display student port numbers based on student number
* Ensure students cannot have the same student number
* Validate student number when existing user logs in
* Clean up unused code
* Complete installation instructions