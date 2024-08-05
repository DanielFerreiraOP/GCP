### GKE

Cluster -> Node pool -> nodes

Caso vc quiser trocar o tipo de máquin, vc tem que criar um node pool node, mas não precisa remover o cluster

para conectar no cluster, clica nos 3 pontos e roda o comando que ele te mostrar
gcloud container clusters get-credentials cluster-lab --zone us-central1-a --project nodeapp-431516