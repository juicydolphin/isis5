ИСИС лабораторная 2

Создать образ:

<code>docker build -t docker-image .</code>

Запустить приложение:

<code>docker run -ti -p 80:8080 docker-image</code>

ИСИС лабораторная 4

Создать Pod

<code>kubectl apply -f .\node-pod.yaml</code>

Создать Deployment

<code>kubectl apply -f .\node-deployment.yaml</code>

Создать ReplicaSet

<code>kubectl apply -f .\node-replicaset.yaml</code>

#   i s i s 5  
 