# microservices_implementation
step1: created Git repository
clone repo and open in vscode.
step2: added a virtual environment
configured the necessary pacakages

Notes:
pip freeze > requriments.txt -- creates a file with all the requirements
pip install -r requirements.txt -- to install requirements.txt

install minikube- install WSL - install docker desktop - after that confiqure docker
start minikube- in=t connects to docker and can see a node running on docker - each and every time need to start docker and run minikube and then from CMD start minikube, 

docker commands: 
docker build -t webapp:1.0 .
docker run -d -p 5000:5000 --name web webapp:1.0