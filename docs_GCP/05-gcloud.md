### Comandos gcloud 

https://cloud.google.com/sdk/gcloud/reference/

para logar:
```
gcloud auth login
```

para trocar o projeto:
```
gcloud config set project PROJECT_ID
```

listar instancias:
```
gcloud compute instances list
```

parar uma máquina ou iniciar
```
gcloud compute instances stop <nome_maquina>
gcloud compute instances start <nome_maquina>
```

para listar instancias do banco
```
gcloud sql instances list
```

### Comandos gsutil para o bucket 

lista o repositorio
```
gsutil ls gs://bd-lab-gcp
```

copia algo para a bucket
```
gsutil cp  repositorios/GCP/img/bd_auth_networks.png gs://bd-lab-gcp
```

sincronizar
```
gsutil rsync  repositorios/GCP/img/ gs://bd-lab-gcp
```

remover
```
gsutil rm gs://bd-lab-gcp/*
```

copiar d e dentro pra fora
```
gsutil cp  gs://bd-lab-gcp/* .
```