# Treinamento K8s_XP

Executar os seguintes comandos:

```sh
$ nano /etc/exports (Adicionar diretório onde ficará o arquivo HTML)
$ exportfs -ar
$ kubectl create -f deployment.yaml
$ kubectl create -f service.yaml
$ kubectl create -f pv.yaml (Atualizar diretório para o mesmo do export)
$ kubectl create -f pvc.yaml
```
