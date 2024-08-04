### Serviços

#### Cloud Spanner

Banco de dados Relacional - tipo sql server, postgres...
escalabilidade horizontal - mais maquinas horizontalmente
consistência transacional, 
replicação global
acesso via jdbc e compativel com varias linguagens
preço por nó
**banco para escala global e com grande volume**

#### Cloud SQL

Banco de dados Relacional
ofere ou postgresql ou mysql - sql server em testes
distribuição por zona
alta disponibilidade e escalabilidade
gerenciado
preço pelo tamanho da máquina


#### Cloud Firestore

Banco de dados NoSQL, baseado em chave valor, json, time seriasl etc...
baseado em document
distribuição global
**Servless** google cuida de toda escalabilidade e infra
atualização automatica

Sincronização on e offline, bom para os devs, quando o app cai, ele continua gravando os dados e depois retorna assim que subir a aplicação
ideal para apps mobile, Iot e Web
Preço por leitura/ Gravação/ Rede/ Armazenamento

#### Firebase Realtime Database

Banco de dados NoSQL, baseado em chave valor, json, time seriasl etc...
google aconselha a migrar para o firestore
igual o firestore porém o preço é por armazenamento e conexões

#### Cloud BigTable

Banco de dados NoSQL, baseado em chave valor, json, time seriasl etc...
document, key par ou time series
distribuição GLOBAL - petabytes
latência 10 ms (mili segundos)
alta disponibilidade, replicação
ideal para banco, transações financeiras, IoT, machine learning
Preço por nós (por maquinas)

#### Cloud Memstore

Banco não relacional, em memoria
basiamente é implementação do redis
banco de dados em memória
distribuição por zona
gerenciado, alta escalabilidade
latência 1 ms
Ideal para jogos online, cache, outros
preço por tamanho de máquina.