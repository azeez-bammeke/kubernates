# kubernates

Kubernates


1. kubectl config get-contexts   - whenever we want to give intstruction to kubernates and it returns list of context available on the local system. Here context is an isolatied environment where client app can interact with kubernate cluster
2. kubectl config get-clusters  - 
3. kubectl config use-context docker-desktop - If you have many context
4. kubectl get nodes

Setup kubernates UI/Admin dashboard

kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml

kubectl proxy

http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/.
