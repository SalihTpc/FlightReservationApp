git clone https://github.com/SalihTpc/FlightReservationApp.git <br>
cd .\FlightReservationApp\ <br>
py -m venv env OR python3 -m venv env <br>
.\env\Scripts\activate OR source env/bin/activate <br>

pip install -r requirements.txt <br>
py manage.py migrate <br>
py manage.py runserver <br>
