# The Readme

SET FLASK Environment
export FLASK_APP=microblog.py


export FLASK_DEBUG=1

### Test keys
Publishable     pk_test_Hnk2aamRWmaYlKyKC9AcYd8k
Secret          sk_test_qjb4pUfzcKEpd8XiWJf66Ym6



#### Notes
database migration
- flask db migrate -m "new fields in user model"
- flask db upgrade

progress:
Currently at sending email. Completed but  Need to then make sending mail asyncrounous



Gmail Settings
(venv) $ export MAIL_SERVER=smtp.googlemail.com
(venv) $ export MAIL_PORT=587
(venv) $ export MAIL_USE_TLS=1
(venv) $ export MAIL_USERNAME=<your-gmail-username>
(venv) $ export MAIL_PASSWORD=<your-gmail-password>

Test email Settings
(venv) $ export MAIL_SERVER=localhost
(venv) $ export MAIL_PORT=8025

python -m smtpd -n -c DebuggingServer localhost:8025
