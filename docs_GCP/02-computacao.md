### Computação

#### Compute Engine GCE

serviço de maquina virtual, windows ou linux, com hdd ou sdd
pode ser pré configuravel ou vc define seu tamanho
faturamento por segundos
desconto por uso prolongado e contínuo
MAQUINAS PREEMPTIVAS: baratas que logo somem em 24 horas

#### App Engine GAE

plataforma como serviço, usa o conceito de servelles
vc coloca apenas o código da aplicação
escalonamento automatico e etc
permite versionamento
divisao de trafego por versões, teste de uma nova versão
monitoramento e diagnostico
ambiente standard (o google gerencia o tamanho )
ambiente flexivel (vc define o tamanho das instancias)
**1 applicação por projeto**
vc pode desabilitar a aplicação, mas nao pode apagar
tem que ter outro projeto para criar o app engine

#### Kubernetes Engine GKE

aplicativos em containers
gestão pode kubernetes
usar um so especifico para containers
upgrande e reparo automaticos 
tamanho maximo de recurso para os containers

#### Cloud Functions

função como serviço, parecido com o app engine pois é servless
leva apenas uma função a ser executada em determinado momento
cobrança por execução 

#### Cloud Run

aplicativos em containers, serviço serveless
não passa configurações de ambiente igual no kubernetes engine
apenas passamos o container para eles
são para container sem estado, que não salvam informações
invocado por http


mi%|5:W[*i12[c5


#### mão na massa !

Criando chave ssh para acessar servidor linux
gere a chave com o caminho e nome e usuário
ssh-keygen -t rsa -f ~/.ssh/gcp_rsa -C danielferreira_emp

após issto só conectar com a chave privada, não esqueça de dar um chmod 400 nela

