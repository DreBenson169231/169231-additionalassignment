1.Clone the repository
git clone https://github.com/<DreBenson169231>/<169231-additionalassignment>.git
cd <169231-additionalassignment>

2.Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install Dependencies
pip install -r requirements.txt

4.Run Migrations
python manage.py makemigrations
python manage.py migrate

5.Start the development Server
python manage.py runserver

6.Access the Api
Open your Browser or Api testing tool and visit:
.Flights:
http://127.0.0.1:8000/passengers/

Requirements
Python 3.8+
django 4.x
django Rest Framework
