# kubernetes utilizando Azure

Comandos utilizados :

1 - kubectl create ns nomeDoSpace ( para a criação do namespace ) 

2 - kubectl get ns ( validar se o namespace foi criado ) 

3 - kubectl apply nomeDoArquivo.ymal 

4 - kubectl get all -n mba ( para validar os POD's e services criados ) 

5 - kubectl exec -it nomeDoPOD -- sh ( para se conectar nos POD's ) 

6 - curl nomeDoPODouService ( para testar a conexão html ) 

7 - kubectl describe pod nomeDoPODouService -n nomeDoSpace ( para pegar as informações do POD ou service )
