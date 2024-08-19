# Mesageria 
É a troca de mensagens entre diferentes componentes ou sistemas.

### Conceitos fundamentais:
* _Mensagens:_ Cada mensagem pode conter um dado real e metadados.
* _Publicadores e Assinantes:_ um publicador envia mensagens para um tópico, enquanto um assinante se inscreve em tópicos para receber mensagens.
* _Tópicos e Filas:_ Tópicos é onde as mensagens são enviadas, e filas é onde fica armazenando mensagens até que possam ser processadas.
* _Broker de Mensagens:_ garante que as mensagens sejam entregues aos destinatários corretos.
* _Desacoplamento:_ permite que os sistemas se comuniquem sem a necessidade de um conhecimento direto sobre o estado ou a disponibilidade dos outros sistemas.
* _Assíncrono:_ o remetente não precisa esperar que o destinatário receba ou processe a mensagem antes de continuar com sua própria execução.

### Tipo:
* _Pub/Sub:_  permite que um componente envie mensagens para um tópico, e os componentes interessados recebem essas mensagens.
* _Fila de Mensagens:_ garante que as mensagens sejam processadas em ordem e para balacear carga.
* _Mensagem de Ponto a Ponto:_ é a troca de mensagem sem intermediários.

### Benefícios:
* Desacoplamentos;
* Resiliência e Tolerância a Falhas;
* Escalabilidade;
* Flexibilidade;
* Desempenho.

### Exemplo de Sistemas de Mensageria:
* RabbitMQ;
* Apache Kafka;
* Google Cloud Pub/Sub.

# Introdução ao Google Cloud Pub/Sub
é um serviço de mensageria em tempo real fornecido pela Google Cloud Platform que faz uma comunicação entre sistemas e aplicativos.

### Características:
* Pub/Sub Model;
* Escalabilidade Automática;
* Baixa Latência e Alta Disponibilidade;
* Suporte a Mensagens Duráveis;
* Segurança.

### Componentes Principais:
* Tópico;
* Assinaturas;
* Mensagens;
* Publicadores;
* Consumidores.

### Casos de Uso:
* Processamento de Eventos em Tempo Real;
* Integração de Sistemas;
* Arquiteturas de Microserviços;
* Análise de Dados em Streaming;
* Notificsções e Alertas.

### Benefícios:
* Escalabilidade;
* Simplicidade;
* Durabilidade e Confiabilidade;
* Integração com o Google Cloud.


