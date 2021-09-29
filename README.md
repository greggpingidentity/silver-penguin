# silver-penguin
 
Deploy values.yaml file:
"helm upgrade --install silver-penguin pingidentity/ping-devops -f values.yaml"

To Remove deployment:
"helm uninstall silver-penguin"
"kubectl delete pvc --selector=app.kubernetes.io/instance=silver-penguin"