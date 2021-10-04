# docker-sample
essai dockerfile

docker run -it ubuntu
apt-get update
apt-get -y install python3 python3-pip vim 
cat > /opt/app.py
pip3 install flask

    
FLASK_APP=/opt/app.py flask run --host=0.0.0.0

