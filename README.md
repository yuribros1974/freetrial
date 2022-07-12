# freetrial

to run API:
python3 -m venv venv;
source venv/bin/activate;
pip install wheel;
pip install flask;
pip install flask-restful;
export FLASK_APP=freetrail.py;
flask run


#Test call
curl -X PUT -H "Content-Type: application/json" -d '{"password": "24Tango", "email": "urib@iguazio.com"}' http://127.0.0.1:5000/ 


