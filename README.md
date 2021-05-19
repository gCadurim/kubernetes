# kubernetes utilizando Azure

Instalar o Az cli : https://docs.microsoft.com/pt-br/azure/aks/kubernetes-walkthrough-portal

Comandos utilizados :

1 - kubectl create ns nomeDoSpace ( para a criação do namespace ) 

2 - kubectl get ns ( validar se o namespace foi criado ) 

3 - kubectl apply nomeDoArquivo.ymal 

4 - kubectl get all -n mba ( para validar os POD's e services criados ) 

5 - kubectl exec -it nomeDoPOD -- sh ( para se conectar nos POD's ) 

6 - curl nomeDoPODouService ( para testar a conexão html ) 

7 - kubectl describe pod nomeDoPODouService -n nomeDoSpace ( para pegar as informações do POD ou service )


* az aks get-credentials --resource-group rg-aulainfra -- teste-aks = conexão na azure 
* kubectl get nodes = lista a máquinas 
* kubectl run ngpod --image=nginx = baixa a imagen do docker 
* kubectl get pods = lista os pods 
* kubectl get pods --watch = trava o termina para monitorar os pods 
* kubectl exec -it ngpod --sh = conectar no pod
* kubectl delete pod ngpod = para deletar o pod 
* kubectl get all = mostra todos os servicoes e pods 
* kubectl describe pod ngpod  = informacoes do pod 
* kubectl top pod 
* kubectl get events 
