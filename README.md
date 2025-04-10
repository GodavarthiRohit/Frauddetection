## Run from terminal:

docker build -t creditcard1.azurecr.io/cc:latest .

docker login creditcard1.azurecr.io

docker push creditcard1.azurecr.io/cc:latest
