# AOSC Mentorship 1.0 - Agosto de 2023 até Setembro de 2023

Estado: Pleaneando

A primeira edição do `AOSC Mentorship` está prevista para Agosto de 2023 até Setembro de 2023.
O programa terá duração de 1 mês.

### Timeline

| actividade | data |
| --- | --- |
| ~~Submissão dos projectos~~ | ~~25 à 04 de Agosto~~ |
| ~~Pre-mentoring Talk~~ | ~~31 de Julho(Tentativa)~~|
| Inscrições de participantes | 05 à 11 de Agosto |
| Avaliações das inscrições | 11 à 13 de Agosto |
| Anúncio de mentorados seleccionados | 14 de Agosto de 2023 |
| Pre-mentoria workshop | 15 à 18 de Agosto |
| Fase da mentoria | 21 de Agosto |
| Submissão dos blogs | 04 à 08 de Setembro |
| Fim do programa | 09 de Setembro |


### Instruções de submissão de projectos

Mantenedores de projectos e potenciais mentores são convidados a submeter descrição de seus projectos através da submissão de um PR no GitHub aqui [AOSC Mentorship Program]() até 04 de Julho de 2023. Encontre o modelo de submissão [aqui](https://github.com/angolaosc/mentorship/blob/main/PROJECT_IDEA_TEMPLATE.md).

Porfavor, encorajamos os mantenedores de projectos a submeterem seus projectos o mais cedo possível para que os participantes tenham tempo suficiente para se familiarizarem com os projectos e fazerem suas escolhas.

### Instruções de inscrição para participantes

Os participantes são convidados a se inscreverem através do formulário de inscrição [AOSC Mentorship Program]() até 11 de Agosto de 2023. Para mais informações sobre o processo de inscrição, consulte o [AOSC Mentorship Program Guide](https://github.com/angolaosc/mentorship/blob/main/resources/AOSC_Mentorship_Program_Guide.pdf).

---

### Projectos participantes na primeira edição

Encontre a lista de projectos participantes na primeira edição abaixo. Os participantes são encorajados a se familiarizarem com os projectos e fazerem suas escolhas antes do início do programa.

#### AOSC - Introdução ao Open-source
##### Tradução de inglês para português, um curso introdutório ao desenvolvimento open-source

- Descrição: O [open-sauced-intro](https://github.com/open-sauced/intro) é um curso introdutório ao desenvolvimento open-source e guia para fazer a primeira contribuição.
O curso foi elaborado pela [OpenSauced](github.com/open-sauced) e está completamente em Inglês. Precisamos criar uma cópia não oficial deste curso em Português.
Mais informações sobre o projecto aqui: https://github.com/open-sauced/intro/issues/16
- Resultado esperado: Traduzir pelo menos 15% do curso.
- Habilidades recomendadas: Inglês intermediário, HTML, CSS, e Javascript
- Mentor(s): Nurul Carvalho([@Nurul-GC](https://github.com/Nurul-GC))
- Problema de Origem (URL): https://github.com/angolaosc/intro-em-portugues/issues/1
- Nível de dificuldade: Fácil

#### Risk Place Angola - É uma plataforma (open-source) para mapear (ou reportar) locais de riscos.
##### Remover Websocket Client do controller de criação de alertas e adicionar metodo write do websocket server para enviar alertas para o cliente.

- Descrição: O [RiskPlace](https://github.com/risk-place-angola/risk-place-angola) é uma plataforma (open-source) para mapear (ou reportar) locais de riscos, Risk Place Angola visa facilitar a chamada de emergência e reportar locais de risco.
O Risk Place Angola possui uma funcionalidade de comunicação em tempo real, que permite que os usuários recebam alertas em tempo real, mas o websocket client está no controller de criação de alertas, o que não é uma boa prática, o ideal seria remover o websocket client do controller de criação de alertas e adicionar metodo write do websocket server para enviar alertas para o cliente.
Mais informações sobre o projecto aqui: https://github.com/risk-place-angola/backend-risk-place/issues/84
- Resultado esperado: Criar alertas em tempo real sem o websocket client no controller de criação de alertas.
- Habilidades recomendadas: Golang
- Mentor(s): Pedro Lopes Estevão([@Paulo-Lopes-Estevao](https://github.com/Paulo-Lopes-Estevao))
- Problema de Origem (URL): https://github.com/risk-place-angola/backend-risk-place/issues/85
- Nível de dificuldade: Médio

#### Client Code Generators - É uma Biblioteca (open-source) para Converter pedidos HTTP em diferentes linguagens à sua escolha, gerando código de pedido HTTP para o mesma linguagenm.
##### Adicionar variante Dio na linguagem Dart - raw data body
- Descrição: O [Client Code Generators](https://github.com/Paulo-Lopes-Estevao/client-code-generators) é uma Biblioteca (open-source) para Converter pedidos HTTP em diferentes linguagens à sua escolha, gerando código de pedido HTTP para o mesma linguagenm.
É um pacote escrito em dart baseado no pacote [Postman Code Generators](https://github.com/postmanlabs/postman-code-generators) do Postman.
O pacote possui 1 variante em dart, que é o http, mas precisamos adicionar mais uma variante, que é o dio.
A variante Dio deve dar suporte a raw data body e headers.
Mais informações sobre o projecto aqui: https://github.com/Paulo-Lopes-Estevao/client-code-generators/issues/4
- Resultado esperado: gerar código de pedido HTTP para a linguagem Dart com a variante Dio, que deve dar suporte a raw data body, headers e o método de pedido HTTP POST.
- Habilidades recomendadas: Dart, HTTP, Inglês básico.
- Mentor(s): Paulo Lopes Estevão([@Paulo-Lopes-Estevao](https://github.com/Paulo-Lopes-Estevao))
- Problema de Origem (URL): https://github.com/Paulo-Lopes-Estevao/client-code-generators/issues/5
- Nível de dificuldade: Médio

#### Predictlow - Uma pequena biblioteca para fazer previsão em grandes conjuntos de dados sem sofrer o problema de out-of-memory.
##### Um projecto ponta-a-ponta para resolver o problema de out-of-memory nos principais algoritmos de aprendizagem de máquina.
- Descrição: O fenômeno "out of memory" ocorre quando um modelo de aprendizagem de máquina esgota a memória disponível durante o treinamento. Isso geralmente acontece quando o conjunto de dados é muito grande ou quando o modelo é muito complexo para a capacidade de memória do sistema. Este é um problema comum em quase todos os algoritmos de aprendizagem de máquina, para superar esse problema, pode-se reduzir o tamanho do conjunto de dados, mas isso só na fase de treinamento, o problema ainda pode persistir na fase de previsão, e aqui entra o predictlow, para permitir fazer previsão de grandes conjunto de dados sem ocorrer o problema de out-of-memory.
- Resultado esperado:  Módulo python (Predictlow) e disponibilizá-lo para instalação via [PIP] (https://pypi.org/project/pip/) para a comunidade opensource consumir com facilidade.
- Problema de Origem (Referência Bibliográfica): https://en.m.wikipedia.org/wiki/Out_of_memory
- Habilidades recomendadas: É desejável python e básico de álgebra linear. Noções de aprendizagem de máquina é um diferencial.
- Mentor(s): Kayenga Campos([@Kissabi](https://github.com/Kissabi))
- Nível de dificuldade: Fácil.

#### Jogos de Cassino em Delégua - Implementando Jogos em Console usando Linguagem 100% em Português
##### Um projeto para aprender programação do zero

- Descrição: Gostaria de aprender a programar do zero e não sabes por onde começar? Podes experimentar [Delégua, uma linguagem de programação 100% em português](https://github.com/DesignLiquido/delegua), que implementa todos os recursos de linguagens de mercado, como orientação a objetos, paradigmas imperativo e funcional. Neste projecto, irás aprender como implementar jogos de cassino como Roleta, Craps e Blackjack.
- Resultado esperado: Um conjunto de jogos que executam em qualquer sistema operacional e qualquer dispositivo.
- Habilidades recomendadas: Ler, escrever e falar português.
- Mentor(s): Leonel Sanches da Silva ([@leonelsanchesdasilva](https://github.com/leonelsanchesdasilva))
- Problema de Origem (URL): https://www.cassino.org/escola/como-jogar-craps, https://www.cassino.org/escola/como-jogar-roleta, https://www.cassino.org/escola/como-jogar-blackjack
- Nível de dificuldade: Fácil

#### RedTeam - Desenvolvimento de softwares focados em segurança ofensiva
##### Um projeto para aprender a desenvolver softwares de segurança ofensiva usados em testes de segurança e operações de equipe vermelha (RedTeam)

- Descrição: Você gosta de cibersegurança e quer aprender a desenvolver ferramentas reais usadas no mundo real? Você vai criar ferramentas de RedTeam, que em cibersegurança é o nome dado a uma equipe de especialistas de segurança que simulam o comprometimento de uma empresa de ponta a ponta, simulando o mais real possível de um ataque real [com 100 Projetos diferentes usados em situações reais no mundo](https://github.com/kurogai/100-redteam-projects). Você tem a liberdade de escolher qualquer item da lista durante esta aventura.
- Resultado esperado: Conhecer e desenvolver ferramentas de segurança ofensiva usadas em ambientes reais
- Habilidades recomendadas: Qualquer linguagem de programação (que suporte o uso do http e sockets), conhecimento básico de redes
- Mentor(s): Héber Júlio ([@kurogai](https://github.com/kurogai))
- Problema de Origem (URL): https://github.com/kurogai/100-redteam-projects-aosc
- Nível de dificuldade: Médio

#### Omunga - Plataforma Angolana de Artigos de TI
 ##### Refatoração geral do projeto

- Descrição: O [Omunga](https://github.com/OMUNGA) é uma plataforma Angolana de Artigos de TI, a versão atual do projeto esta com uma arquitetura não muito aconselhavel, e código não muito legivel.
 - Resultado esperado:
   - Revisar o código existente em busca de melhorias, remoção de redundâncias e simplificação do código.
   - Adotar boas práticas de programação e padrões de design para aumentar a qualidade e a manutenibilidade do código.
- Habilidades recomendadas: Javascript | Nextjs | Clean code
- Mentor(s): Miguel Buca ([@miguelbuca](https://github.com/miguelbuca))
- Problema de Origem (URL): https://github.com/OMUNGA/Front-end/issues/44
- Nível de dificuldade: Médio

#### DoeSangue - Plataforma para conectar doadores de sangue ao Instituto Nacional de Sangue 
##### Refactoração e upgrade

- Descrição: Doesangue/Giveblood é uma plataforma (API as a Service) que visa servir de um ponto de ligação entre pessoas doadoras de sangue e instituições responsáveis por colheita de sangue (hospitais e Instituto Nacional de Sangue). 
- Resultado esperado:
   - Actualizar para versão mais recente do Laravel (v10 até a data)
   - Refactorar as funcionalidades de cadastro de doadores para marcar como "em espera" para validação dos dados antes de marcar como doador válido
   - Aplicar boas práticas e evitar duplicação de funções
   - Cadastrar hospitais
- Habilidades recomendadas: PHP/Laravel, Angular
- Mentor(s): José Cage([@JoseCage](https://github.com/JoseCage))
- Problema de Origem (URL): https://github.com/givebloodorg/doesangue-core/issues/57

#### pREST - API REST para o Postgres
##### Feature para escolha do modo JOIN

- Descrição: O [pREST](https://github.com/prest/prest) é uma API REST criada para facilitar o desenvolvimento ágil. A versão atual obriga o desenvolvedor a usar o novo método de JOIN da API, mas isto apesar de melhorar o desempenho para a maioria quebrou alguns usuários, o que os impede de atualizar para versões mais novas.
 - Resultado esperado:
   - Através de uma nova configuração possibilitar que o usuário escolha seu método de JOIN na API.
- Habilidades recomendadas: Golang | Postgres | Clean code | Docker
- Mentor(s): Arthur Silva ([@arxdsilva](https://github.com/arxdsilva))
- Problema de Origem (URL): https://github.com/prest/prest/issues/746
- Nível de dificuldade: Médio


#### Rede Angolana de Monitoramento de Desastres Naturais - Sistema de Prevenção de Desastres Naturais
Member

##### Sistema de Prevenção de Desastres Naturais

- Descrição: Criar uma POC de uma Plataforma de IOT para monitoramento de Desastres Naturais
- Resultado esperado: 
   - Projeto (POC) de um framework para criar clientes que possam enviar dados para a plataforma
   - Projeto (POC) do servidor que irá receber os dados do cliente
- Habilidades recomendadas:
   - Lógica de programação | JAVA | Orientação a objetos | Postgres | Docker
- Mentor(s): Bruno Alves dos Santos
- Problema de Origem (URL): https://github.com/orgs/angolaosc/projects/1
- Nível de dificuldade: Médio | Difícil


##### Criar servidor
- Descrição: Precisamos criar um servidor que irá aceitar registros de clientes e envio de dados através do protocolo MQTT.
Estes dados serão salvos em banco de dados criando uma base única para consulta.
- Resultado esperado: Na nossa POC iremos registrar clientes e receber dados simples para armazenar no banco de dados.
- Habilidades recomendadas: Lógica de programação | JAVA | Orientação a objetos | Postgres | Docker
Mentor(s): Bruno Alves dos Santos
Problemas de Origem (URL): 
https://github.com/angolaosc/monitora-angola/issues/1
https://github.com/angolaosc/monitora-angola/issues/2
https://github.com/angolaosc/monitora-angola/issues/5
https://github.com/angolaosc/monitora-angola/issues/6
https://github.com/angolaosc/monitora-angola/issues/8
Nível de dificuldade: Médio | Difícil

##### Criar um Cliente IOT

Descrição: Precisamos implementar um cliente para fazer o envio dos dados - por exemplo - nível dos rios - para o servidor. Para isso, este
cliente irá se comunicar através do protocolo MQTT.
Resultado esperado: O cliente deverá simular dados para envio ao servidor. Também deverá ser capaz de ao inicializar, enviar o registro para depois começar o envio dos dados.
Habilidades recomendadas: Lógica de programação | JAVA | Orientação a objetos | Postgres | Docker
Mentor(s): Bruno Alves dos Santos
Problemas de Origem (URL): 
https://github.com/angolaosc/monitora-angola/issues/3
- Nível de dificuldade: Médio | Difícil

### Comunicação

Encorajamos os participantes a se juntarem aos nossos canais de comunicação para se conectarem com outros participantes e mentores. O link para o canal será compartilhado com os participantes selecionados.

Para disucssões gerais, porfavor, use o canal `#aosc-mentorship` no [AOSC Discord](https://discord.gg/tuUDNdRzvze).
