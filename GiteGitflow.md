# Git e Gitflow

Nome do Estagiário: Julia de Lima Torres

Data: 02/08/2024


### Introdução de Git 
Git é uma forma de rastrear todos os arquivos dentro do seu projeto e fazer marco histórico de cada funcionalidade e estágio do seu projeto, há a possibilidade de você voltar ao seu estágio anterior ou ir para um estágio mais a frente.

#### Objetivo: 
* Velocidade;
* Integridade de dados;
* Suporte para fluxos de trabalho;

#### Benefícios:
* Controle de versão:podendo voltar a sua versão passada ou sua versão atual;
* Colaboração:trabalhar simultaneament no mesmo projeto que outros desenvolvedores estão porém em partes diferentes;
* Distribuído:cada desenvolvidor poderar tem uma cópia do projetp.

#### Conceitos:
* Repositório: O diretório onde o Git armazena o histórico completo de alterações do projeto, incluindo arquivos e pastas.
* Comprometer: um instantâneo de um projeto em um momento específico. Cada commit possui um identificador exclusivo (hash).
* Branches: Branches do projeto que permitem trabalhar em diferentes desenvolvimentos ao mesmo tempo. O branch master é frequentemente chamado de “main” ou “master”.
* Mesclar: Mesclar alterações de diferentes ramificações em uma ramificação.
* Pull: atualiza a cópia local do repositório com as alterações mais recentes no repositório remoto.
* Push: Envie alterações locais para o repositório remoto.
* Clone: ​​Crie uma cópia local de um repositório remoto.
* Fork: Crie uma cópia independente de um repositório, para contribuir com um projeto sem afetar o repositório original.


### Introdução de Gitflow
Giflow é outro modelo de ramificação do Git que envolve o uso de ramificações de recursos e várias ramificações principais ao longo do ciclo de vida do software. Se você trabalha em equipe, precisa ter um fluxo de trabalho muito claro, e o GitFlow faz exatamente isso, auxiliando você em todo o ciclo do seu projeto e software.

#### Objetivo:
Pode ser usado para projetos com ciclos de lançamento agendados e práticas recomendadas de DevOps de entrega contínua.

#### Componentes:
##### Branches Principais:
* main: Contém o código de produção estável. Cada commit nesta branch representa uma nova versão de lançamento.
* develop: Contém o código em desenvolvimento com as últimas alterações aprovadas. Serve como a base para novas funcionalidades e integrações.
##### Branches de Suporte:
* feature: Usada para desenvolver novas funcionalidades. Deriva de develop e é mesclada de volta a develop quando a funcionalidade está concluída.
* release: Preparada para o lançamento de uma nova versão. Deriva de develop e, após ajustes finais, é mesclada em main e develop.
* hotfix: Criada para correções urgentes em produção. Deriva de main e é mesclada de volta em main e develop após a correção.

#### Benefícios:
* Organização: Uma estrutura clara para gerenciar diferentes tipos de trabalho.
* Paralelismo: Facilita o processamento de vários recursos e correções simultaneamente.
* Estabilidade: Garanta que o código em produção esteja sempre em estado estável.

Links de Laboratórios 
* [Github](<https://github.com/2RP-Squad404/Data_Science/blob/main/wiki/subpages/git.md>)
