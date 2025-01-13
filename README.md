## End to End Machine Learning Project including Azure Cloud Deployment
## Run from terminal:

docker build -t testdockersrini.azurecr.io/mltest:latest .

docker login testdockersrini.azurecr.io

docker push testdockersrini.azurecr.io/mltest:latest
