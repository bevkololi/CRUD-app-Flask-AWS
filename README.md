# CRUD-app-Flask-AWS
A simple application that enables users to upload, view, edit and download their finances, that uses Flask and Amazon Web Services.

## Setup
Clone the repository using the command
`git clone XXXX`

Setup your configurations in a `.env` file:
- `source venv/bin/activate`
- `export FLASK_APP=app.py`
- `export FLASK_DEBUG=1`
- `export FLASK_ENV=development`
- `export S3_BUCKET=<insert name of bucket>`

Update your AWS credentials in the files `.aws/config` and `.aws/credentials`. Ensure to have an active AWS account ready beforehand.

## Run the application
Run the application using the command `flask run`

## Screenshots
### On accessing the index page
<img width="1440" alt="Screenshot 2019-03-20 at 15 00 52" src="https://user-images.githubusercontent.com/26184534/54682820-01571900-4b21-11e9-9913-43f508613f1f.png">

### On clicking on any of the buckets, or on the files button in the nav bar
<img width="1440" alt="Screenshot 2019-03-20 at 12 47 25" src="https://user-images.githubusercontent.com/26184534/54682778-df5d9680-4b20-11e9-80b2-971512f1b901.png">

### Confirm that the buckets and objects have been created by accessing the 's3' resources page in AWS. 
![Screenshot 2019-03-20 at 15 01 51](https://user-images.githubusercontent.com/26184534/54682878-31062100-4b21-11e9-9329-25821ce357cb.png)


Happy coding.
